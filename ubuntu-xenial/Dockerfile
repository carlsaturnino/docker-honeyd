FROM ubuntu:xenial
MAINTAINER Carl Saturnino

RUN apt-get update
RUN apt-get install -y wget \
      libdumbnet-dev \
      libevent-1.4-2 \
      libpcap-dev \
      farpd \
      libdnet \
      libevent-dev \
      libpcre3-dev \
      libedit-dev \
      bison \
      flex \
      libtool \
      zlib1g-dev \
      automake

      RUN wget http://launchpadlibrarian.net/121918272/honeyd_1.5c-10ubuntu1_amd64.deb
      RUN dpkg -i honeyd_1.5c-10ubuntu1_amd64.deb \
        && rm honeyd_1.5c-10ubuntu1_amd64.deb

        RUN apt-get install -y nmap
        RUN apt-get install -y rrdtool

