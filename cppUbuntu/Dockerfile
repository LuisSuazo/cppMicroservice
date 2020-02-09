FROM ubuntu:latest
 
RUN apt-get -y update && apt-get install -y

RUN echo "yes" | apt-get install build-essential
RUN echo "yes" | apt-get install libssl-dev
RUN echo "yes" | apt-get install zlib1g-dev
RUN echo "yes" | apt-get install libboost-all-dev
RUN echo "yes" | apt-get install cmake
RUN echo "yes" | apt-get install git
RUN echo "yes" | apt-get install vim


LABEL Name=ubuntu-cpp Version=1
