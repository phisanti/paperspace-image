# Paperspace files for the image

*JupyterLab version*

## Overview

Designed to install conda, CUDA and related packages.

## Requirements:

[Docker CE](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)

[NVIDIA-docker](https://github.com/NVIDIA/nvidia-docker)

Nvidia Drivers


## Build

`sudo docker build -t paperspace/fastai .`

## Pre-built runtimes

You can also just run the following without having to build the entire container yourself. This will pull the container from Docker Hub.

`sudo docker run --gpus all -d -p 8888:8888 paperspace/fastai:2.0-CUDA9.2-complete-4.0-v0.0.15-lab /run.sh`
