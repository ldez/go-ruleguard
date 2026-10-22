FROM golang:1.27-alpine AS build

ARG release
COPY . /root

RUN /root/test.bash $release
