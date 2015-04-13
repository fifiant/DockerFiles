# VERSION 0.1
# DOCKER-VERSION  1.5.0
# AUTHOR:         Fawaz PARAISO <fifiant@gmail.com>
# DESCRIPTION:    Image with docker-registry project and dependecies
# TO_BUILD:       docker build -rm -t registry .
# TO_RUN:         docker run -p 5000:5000 registry

FROM ubuntu:14.04
MAINTAINER Fawaz PARAISO <fifiant@gmail.com>
RUN apt-get update && apt-get install -y ruby ruby-dev
RUN gem install sinatra