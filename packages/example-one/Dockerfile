FROM debian:bookworm-slim

ARG TARGET

COPY target/${TARGET}/release/example-one /usr/local/bin/example-one

ENTRYPOINT ["example-one"]
