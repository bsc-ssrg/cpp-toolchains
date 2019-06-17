FROM ubuntu:xenial
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install -y clang-5.0 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/clang++-5.0 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/clang-5.0 10 && \
    update-alternatives --quiet --install /usr/bin/c89 c89 /usr/bin/clang-5.0 10 && \
    update-alternatives --quiet --install /usr/bin/c99 c99 /usr/bin/clang-5.0 10

CMD [ "/bin/bash" ]
