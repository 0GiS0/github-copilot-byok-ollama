FROM mcr.microsoft.com/devcontainers/base:jammy

# Install socat
RUN apt-get update \
    && apt-get -y install socat \
    && rm -rf /var/lib/apt/lists/*
    