FROM ubuntu:trusty
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install --no-install-recommends -y software-properties-common && \
    add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
    apt-get update && \
    apt-get install --no-install-recommends -y g++-4.8 && \
    update-alternatives --quiet --install /lib/cpp cpp /usr/bin/cpp-4.8 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/gcc-4.8 20 && \
    update-alternatives --quiet --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 20 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/g++-4.8 20 && \
    update-alternatives --quiet --install /usr/bin/g++ g++ /usr/bin/g++-4.8 20 && \
    rm -rf /var/lib/apt/lists/*

CMD [ "/bin/bash" ]
