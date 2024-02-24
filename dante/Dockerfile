FROM registry.fedoraproject.org/fedora:39
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf -y update && \
    dnf -y install dante-server && \
    dnf clean all

COPY sockd.conf /etc/sockd.conf

EXPOSE 3128
ENTRYPOINT ["/usr/sbin/sockd"]
