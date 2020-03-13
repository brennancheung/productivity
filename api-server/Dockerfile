FROM rustlang/rust:nightly

WORKDIR /usr/src/app
COPY . .

# build the dev version for now
RUN cargo build
CMD ["cargo", "run"]