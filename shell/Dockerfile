FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
    git \
    vim \
    man

RUN mkdir /project
WORKDIR /project

ENTRYPOINT ["bash"]
