FROM ubuntu:18.04

RUN apt update && apt install -y git make curl

RUN git clone https://github.com/sh19910711/dotfiles.git && \
    cd dotfiles && \
    make setup

RUN apt update && apt install -y gcc g++ gdb