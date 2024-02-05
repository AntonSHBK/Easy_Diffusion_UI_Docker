FROM debian:latest

# Set work directory
RUN mkdir /app
WORKDIR /app

# Install dependences
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y \
        # build-essential \
        # cmake \
        sudo \
        wget \
        git \
        curl \
        unzip \
        python3 \
        python3-pip \
        python3-venv \
        libgl1-mesa-dev \
        libglib2.0-0 \
        pybind11-dev

RUN wget https://github.com/cmdr2/stable-diffusion-ui/releases/latest/download/Easy-Diffusion-Linux.zip

RUN unzip Easy-Diffusion-Linux.zip && cd easy-diffusion && ./start.sh
RUN cd easy-diffusion/models/stable-diffusion

# Download models
# RUN wget https://huggingface.co/runwayml/stable-diffusion-v1-5/resolve/main/v1-5-pruned.ckpt 

# install dependencies
# COPY ./requirements.txt /tmp/requirements.txt
# RUN pip install --upgrade pip
# RUN pip install --no-cache-dir -r /tmp/requirements.txt