FROM liuchong/rustup:nightly
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN cp -Rp ~/.rustup ~/.rustup-new
RUN env RUSTUP_HOME=$HOME/.rustup-new rustup update nightly
RUN rm -rf ~/.rustup ; mv ~/.rustup-new ~/.rustup
