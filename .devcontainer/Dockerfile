FROM alpine:3.10.2

RUN apk update && \
    apk add gcc g++ gdb git make bash curl vim openssh-client

RUN git clone https://github.com/sh19910711/dotfiles.git && \
    cd dotfiles && \
    make setup