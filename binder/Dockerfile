FROM quay.io/dkhider/coral-visualization

# Set working directory
WORKDIR /home/jovyan

# Copy repository files into the container
COPY . /home/jovyan/

# Ensure correct permissions for working directory
RUN chmod -R 777 /home/jovyan

# Set the default command to start Jupyter
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--port=8888", "--no-browser"]
