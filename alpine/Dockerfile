# https://docs.docker.com/engine/reference/builder/

ARG  BASE
FROM ${BASE}

USER root:root

RUN  rm -rf /var/cache/apk/* \
  && apk update \
  && apk add --no-cache \
    git \
    openssh-client \
    tar \
    gzip \
    ca-certificates \
  && rm -rf /var/cache/apk/*
