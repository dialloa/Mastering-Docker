#Get the OS
FROM ubuntu:latest

#Owner
<<<<<<< HEAD
MAINTAINER AKD “Mastering docker”
=======
MAINTAINER AKD "Mastering docker"
>>>>>>> e1583b7c22d2f4c08ee6b9542a641be85bc22b9b

#Running command
RUN apt-get update \
  && apt-get install -y python python-pip wget \
  && pip install Flask \
  && wget https://raw.githubusercontent.com/odewahn/docker-jumpstart/master/examples/hello.py \
  && cp hello.py /home/hello.py

#Add a file in the container
#ADD hello.py /home/hello.py

#Setting default directory for when the container start
WORKDIR /home

#You can use CMD to run a command when the container start
