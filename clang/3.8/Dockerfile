FROM ubuntu:xenial
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install -y clang-3.8 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/clang++-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/clang-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/c89 c89 /usr/bin/clang-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/c99 c99 /usr/bin/clang-3.8 10

CMD [ "/bin/bash" ]