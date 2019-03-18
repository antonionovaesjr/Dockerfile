FROM jenkins/jenkins:lts
#############
## Docker
############
USER root
RUN apt-get update && apt-get install curl tar python-pip -y && pip install anchorecli
ARG DOCKER_VERSION=18.09.0
RUN curl -fsSL https://download.docker.com/linux/static/stable/`uname -m`/docker-$DOCKER_VERSION.tgz | tar --strip-components=1 -xz -C /usr/local/bin docker/docker
#RUN pip install anchorecli

