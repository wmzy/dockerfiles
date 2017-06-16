FROM golang:1.8.1-alpine

RUN apk add --no-cache git make openssh openssl curl && \
    curl https://glide.sh/get | sh && \
    apk del curl && \
    rm -rf /tmp/*
