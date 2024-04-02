FROM registry.fedoraproject.org/fedora-toolbox:39
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"
LABEL org.label-schema.name="fale/beets"
LABEL org.opencontainers.image.source=https://github.com/fale/containers

RUN dnf update -y \
    && dnf install -y python3-pip beets beets-plugins \
    && pip install python3-discogs-client \
    && dnf clean all
