FROM ubuntu:xenial
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install -y software-properties-common wget && \
    add-apt-repository "deb http://apt.llvm.org/xenial/ llvm-toolchain-xenial-7 main" && \
    wget -O - https://apt.llvm.org/llvm-snapshot.gpg.key | apt-key add - && \
    apt-get update && \
    apt-get install -y clang-7 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/clang++-7 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/clang-7 10 && \
    update-alternatives --quiet --install /usr/bin/c89 c89 /usr/bin/clang-7 10 && \
    update-alternatives --quiet --install /usr/bin/c99 c99 /usr/bin/clang-7 10

CMD [ "/bin/bash" ]
