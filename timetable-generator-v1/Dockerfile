FROM debian:stable-slim AS os
ENV DEBIAN_FRONTEND=noninteractive

FROM os AS base
RUN apt update -y && apt install -y protobuf-compiler;

FROM base as devcontainer