FROM golang:latest
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN env GO111MODULE=on go get github.com/golangci/golangci-lint/cmd/golangci-lint@v1.15.0 && \
        go get -v github.com/wadey/gocovmerge && \
        go get github.com/cespare/prettybench
