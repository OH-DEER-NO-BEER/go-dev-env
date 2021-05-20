FROM golang:1.16.4-alpine3.13

RUN apk update && apk add git
RUN mkdir -p /go/src/goapp
# receive ARG from docker-compose.yml
# args: HOME=${HOME}
ARG HOME

# COPY ${HOME}/go/* /go
WORKDIR /go/src/goapp
