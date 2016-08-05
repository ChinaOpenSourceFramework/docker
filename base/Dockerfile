############################################################

# Dockerfile to build base container images

# Based on Ubuntu

############################################################

# Set the base image to Ubuntu

FROM ubuntu:14.04

# File Author

MAINTAINER liQiWei 2452403243@qq.com

# Update the repository sources list

RUN echo "deb http://cn.archive.ubuntu.com/ubuntu/ trusty main restricted">/etc/apt/sources.list 
RUN apt-get update

# create content
RUN mkdir /project

# Install tool
RUN apt-get -y install dialog wget vim tar git

# config git
ADD . /root

