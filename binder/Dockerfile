FROM quay.io/dkhider/coral-visualization

# Set working directory
WORKDIR /home/jovyan

# Ensure Jupyter is available
RUN pip install --no-cache-dir jupyter jupyterlab

# Copy repository files into the container
COPY . /home/jovyan/

# Set the default command to start Jupyter
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser"]
