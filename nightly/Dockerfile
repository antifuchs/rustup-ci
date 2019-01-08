FROM liuchong/rustup:nightly
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN apt-get update -qy && apt-get install -y git && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN (rustup component add clippy || cargo install --git https://github.com/rust-lang/rust-clippy/ --force clippy) && rustup component add rustfmt
