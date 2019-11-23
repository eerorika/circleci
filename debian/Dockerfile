# https://docs.docker.com/engine/reference/builder/

ARG  BASE
FROM ${BASE}

USER root:root

RUN  apt-get update \
  && apt-get install --no-install-recommends -y \
    git \
    openssh-client \
    tar \
    gzip \
    ca-certificates \
  && apt-get clean -y
