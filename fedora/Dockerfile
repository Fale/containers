FROM registry.fedoraproject.org/fedora-toolbox:39
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf update -y && \
    dnf install -y make \
                   neovim \
                   neovim-ale \
                   fedora-packager \
                   fedora-packager-kerberos \
                   fedora-repos-rawhide \
                   fedora-review \
                   go2rpm \
    && dnf clean all
