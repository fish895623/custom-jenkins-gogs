FROM jenkins/jenkins:latest

LABEL org.opencontainers.image.source="https://github.com/fish895623/custom-jenkins-gogs"

USER root
RUN apt-get update \
    && apt-get install curl -y \
    && curl -fsSL get.docker.io | bash \
    && usermod -aG docker jenkins

USER jenkins