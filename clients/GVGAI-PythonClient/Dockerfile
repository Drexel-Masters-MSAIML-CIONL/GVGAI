FROM python:3.5

WORKDIR /workspace

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive \
    apt-get -y install default-jre-headless openjdk-11-jdk && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN pip3 install pillow
