FROM ubuntu:xenial
MAINTAINER Carl Saturnino

RUN apt-get update
RUN apt-get install -y build-essential \
      libpcap-dev \
      libdnet-dev \
      libevent-dev \
      libpcre3-dev \
      make \
      bzip2 \
      nmap \
      psmisc \
      libtool \
      libdumbnet-dev \
      zlib1g-dev \
      rrdtool \
      net-tools \
      git-core \
      libreadline-dev \
      libedit-dev \
      bison \
      flex \
      automake

RUN apt-get install -y farpd
RUN apt-get install -y iputils-ping
RUN apt-get install -y sudo
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN git clone https://github.com/DataSoft/Honeyd.git
RUN cd Honeyd \
  && ./autogen.sh \
  && ./configure \
  && make \
  && make install

