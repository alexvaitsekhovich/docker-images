FROM ubuntu:latest
RUN apt-get update
ENV DEBIAN_FRONTEND=noninteractive 
RUN apt-get install -y apt-transport-https ca-certificates curl software-properties-common
RUN curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add -
RUN add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu  $(lsb_release -cs)  stable"
RUN	apt-get update
RUN apt-get -y install docker-ce=5:19.03.12~3-0~ubuntu-focal
