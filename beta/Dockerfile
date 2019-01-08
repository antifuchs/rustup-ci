FROM liuchong/rustup:beta
MAINTAINER Andreas Fuchs <asf@boinkor.net>

RUN apt-get update -qy && apt-get install -y git && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN rustup component add clippy && rustup component add rustfmt
