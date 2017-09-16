FROM liuchong/rustup:nightly
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN cp -a ~/.rustup ~/.rustup-new ; rm -rf ~/.rustup ; mv ~/.rustup-new ~/.rustup
RUN rustup update nightly
