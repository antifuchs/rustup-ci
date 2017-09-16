FROM liuchong/rustup:nightly
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN rm -rf ~/.rustup/{tmp,toolchains/nightly*}
RUN mkdir -p ~/.rustup/tmp

RUN rustup install nightly
