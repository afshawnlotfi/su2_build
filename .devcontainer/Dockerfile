FROM mcr.microsoft.com/devcontainers/python:0-3.10
RUN apt-get update && apt-get install -y \
    libopenmpi-dev \
    openmpi-bin
 && rm -rf /var/lib/apt/lists/*
RUN pip install numpy scipy mpi4py