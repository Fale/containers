FROM registry.fedoraproject.org/fedora-toolbox:36
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf update -y \
    && dnf install -y ansible \
    && dnf clean all
