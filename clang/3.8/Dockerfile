FROM ubuntu:trusty
MAINTAINER alberto.miranda@bsc.es

RUN apt-get update && \
    apt-get install -y clang-3.8 && \
    update-alternatives --quiet --install /usr/bin/c++ c++ /usr/bin/clang++-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/cc cc /usr/bin/clang-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/c89 c89 /usr/bin/clang-3.8 10 && \
    update-alternatives --quiet --install /usr/bin/c99 c99 /usr/bin/clang-3.8 10 && \
    ln -s /usr/bin/clang-3.8 /usr/bin/clang && \
    ln -s /usr/bin/clang++-3.8 /usr/bin/clang++ && \
    ln -s /usr/bin/clang-apply-replacements-3.8 /usr/bin/clang-apply-replacements && \
    ln -s /usr/bin/clang-check-3.8 /usr/bin/clang-check && \
    ln -s /usr/bin/clang-query-3.8 /usr/bin/clang-query && \
    rm -rf /var/lib/apt/lists/*

CMD [ "/bin/bash" ]
