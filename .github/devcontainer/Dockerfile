FROM buildpack-deps:noble-curl

LABEL dev.containers.features="common"

ARG TARGETOS
ARG TARGETARCH

RUN apt-get update && apt-get -y install --no-install-recommends \
        jq \
        yq \
        xdg-utils \
        unzip
