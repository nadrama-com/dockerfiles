FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y cloud-init && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
