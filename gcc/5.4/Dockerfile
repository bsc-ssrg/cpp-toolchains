FROM ubuntu:xenial
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install software-properties-common && \
    add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
    apt-get update && \
    apt-get install -y g++-5 && \
    update-alternatives --quiet --install /lib/cpp cpp /usr/bin/cpp-5 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/gcc-5 20 && \
    update-alternatives --quiet --install /usr/bin/gcc gcc /usr/bin/gcc-5 20 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/g++-5 20 && \
    update-alternatives --quiet --install /usr/bin/g++ g++ /usr/bin/g++-5 20

CMD [ "/bin/bash" ]
