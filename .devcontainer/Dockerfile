FROM ubuntu:22.04

# Prevent interactive prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    build-essential \
    gdb \
    strace \
    valgrind \
    man-db \
    manpages-dev \
    cmake \
    git \
    && rm -rf /var/lib/apt/lists/*

# Set default shell to bash (or zsh if you prefer to install it)
ENV SHELL /bin/bash
