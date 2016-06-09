FROM ubuntu:trusty
MAINTAINER Carl Saturnino

RUN apt-get update
RUN apt-get install -y build-essential gcc
RUN apt-get install -y wget \
      farpd \
      libevent-1.4-2 \
      libpcap-dev \
      libdnet \
      libevent-dev \
      libdumbnet-dev \
      libpcre3-dev \
      libedit-dev \
      bison \
      flex \
      libtool \
      zlib1g-dev \
      automake \
      RUN wget http://launchpadlibrarian.net/121918272/honeyd_1.5c-10ubuntu1_amd64.deb
      RUN dpkg -i honeyd_1.5c-10ubuntu1_amd64.deb \
        && honeyd_1.5c-10ubuntu1_amd64.deb

