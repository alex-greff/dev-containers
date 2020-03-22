FROM ubuntu:latest
WORKDIR /app
RUN apt-get update && apt-get install -y build-essential curl
# Install perl
RUN curl -L http://xrl.us/installperlnix | bash
# Install python(s)
RUN apt-get -y install python3 python
# Install netpbm
RUN apt-get -y install netpbm