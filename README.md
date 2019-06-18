# Docker containers for the GCC and LLVM/Clang toolchains
[![Travis.com](https://img.shields.io/travis/com/bsc-ssrg/cpp-toolchains.svg)](https://travis-ci.com/bsc-ssrg/cpp-toolchains)
[![Docker Pulls](https://img.shields.io/docker/pulls/bscstorage/gcc-toolchain.svg?label=docker%20pulls%20%28GCC%29)](https://hub.docker.com/r/bscstorage/gcc-toolchain/)
[![Docker Pulls](https://img.shields.io/docker/pulls/bscstorage/clang-toolchain.svg?label=docker%20pulls%20%28LLVM%2FClang%29)](https://hub.docker.com/r/bscstorage/clang-toolchain/)
[![GitHub](https://img.shields.io/github/license/bsc-ssrg/cpp-toolchains.svg?color=blue)](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/LICENSE)

A collection of Docker :whale: containers with official GCC and LLVM/Clang releases under Ubuntu 16.04 Xenial.

## Containers for GCC:

| Tags  | Dockerfile | Image metadata |
|-------|------------|----------------|
| `4.8` | [/gcc/4.8/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/4.8/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/4.8.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/4.8.svg?style=flat-square)  |
| `4.9` | [/gcc/4.9/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/4.9/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/4.9.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/4.9.svg?style=flat-square)  |
| `5.4` | [/gcc/5.4/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/5.4/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/5.4.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/5.4.svg?style=flat-square)  |
| `6.5` | [/gcc/6.5/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/6.5/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/6.5.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/6.5.svg?style=flat-square)  |
| `7.4` | [/gcc/7.4/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/7.4/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/7.4.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/7.4.svg?style=flat-square)  |
| `8.1` | [/gcc/8.1/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/8.1/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/8.1.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/8.1.svg?style=flat-square)  |
| `9.1` | [/gcc/9.1/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/9.1/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/9.1.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/9.1.svg?style=flat-square)  |
| `latest` | [/gcc/latest/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/gcc/latest/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/gcc-toolchain/latest.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/gcc-toolchain/latest.svg?style=flat-square)  |

## Containers for LLVM/Clang:

| Tags  | Dockerfile | Image metadata |
|-------|------------|----------------|
| `3.6` | [/clang/3.6/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/3.6/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/3.6.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/3.6.svg?style=flat-square)  |
| `3.7` | [/clang/3.7/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/3.7/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/3.7.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/3.7.svg?style=flat-square)  |
| `3.8` | [/clang/3.8/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/3.8/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/3.8.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/3.8.svg?style=flat-square)  |
| `3.9` | [/clang/3.9/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/3.9/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/3.9.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/3.9.svg?style=flat-square)  |
| `4.0` | [/clang/4.0/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/4.0/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/4.0.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/4.0.svg?style=flat-square)  |
| `5.0` | [/clang/5.0/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/5.0/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/5.0.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/5.0.svg?style=flat-square)  |
| `6.0` | [/clang/6.0/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/6.0/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/6.0.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/6.0.svg?style=flat-square)  |
| `7.1` | [/clang/7.1/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/7.1/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/7.1.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/7.1.svg?style=flat-square)  |
| `8.0` | [/clang/8.0/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/8.0/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/8.0.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/8.0.svg?style=flat-square)  |
| `9.0` | [/clang/9.0/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/9.0/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/9.0.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/9.0.svg?style=flat-square)  |
| `latest` | [/clang/latest/Dockerfile](https://github.com/bsc-ssrg/cpp-toolchains/blob/master/clang/latest/Dockerfile) | ![](https://img.shields.io/microbadger/image-size/bscstorage/clang-toolchain/latest.svg?style=flat-square) ![](https://img.shields.io/microbadger/layers/bscstorage/clang-toolchain/latest.svg?style=flat-square)  |
