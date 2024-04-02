FROM registry.fedoraproject.org/fedora-toolbox:39
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf update -y \
    && dnf install -y golang \
    && dnf clean all
