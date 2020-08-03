FROM ubuntu:latest
ARG DEBIAN_FRONTEND=noninteractive
WORKDIR /app
RUN apt-get update && \
  apt-get install -y build-essential valgrind wget curl netcat