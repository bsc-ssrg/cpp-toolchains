FROM ubuntu:xenial
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install -y software-properties-common && \
    add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
    apt-get install -y g++-4.9 && \
    update-alternatives --quiet --install /lib/cpp cpp /usr/bin/cpp-4.9 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/gcc-4.9 20 && \
    update-alternatives --quiet --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 20 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/g++-4.9 20 && \
    update-alternatives --quiet --install /usr/bin/g++ g++ /usr/bin/g++-4.9 20 && \
    rm -rf /var/lib/apt/lists/*

CMD [ "/bin/bash" ]
