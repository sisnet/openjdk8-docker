# openjdk8-docker
---

## Description
This project builds a docker image which is the combination of openjdk:8-jdk-alpine and docker:latest docker images.
Image is built _FROM openjdk:8-jdk-alpine_ and then docker:latest's Dockerfile content is added.
 - openjdk:8-jdk-alpine: https://hub.docker.com/_/openjdk/
 - docker:latest: https://hub.docker.com/_/docker/


## Intented usage
This image is used in order to build docker images in a Java context (maven docker build through Gitlab runner).