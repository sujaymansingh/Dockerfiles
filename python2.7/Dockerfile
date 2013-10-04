# Take the base ubuntu image, and install python2.7 (and assorted utils).
#

FROM ubuntu
MAINTAINER Sujay Mansingh

RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get install -y build-essential
RUN apt-get install -y python2.7 python-dev python-virtualenv git
RUN apt-get install -y vim
