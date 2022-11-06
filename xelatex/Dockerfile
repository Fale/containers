FROM registry.fedoraproject.org/fedora-toolbox:36
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf update -y && \
    dnf install -y inkscape \
                   make \
                   neovim \
                   neovim-ale \
                   overpass-fonts \
                   redhat-display-fonts \
                   redhat-mono-fonts \
                   redhat-text-fonts \
                   s3cmd \
                   texlive \
                   texlive-babel-italian.noarch \
                   texlive-beamertheme-metropolis \
                   texlive-cdpbundl \
                   texlive-collection-latex \
                   texlive-collection-latexrecommended \
                   texlive-collection-xetex \
                   texlive-comfortaa \
                   texlive-datetime2 \
                   texlive-dejavu \
                   texlive-fontawesome \
                   texlive-glossaries \
                   texlive-hyphenat \
                   texlive-latex \
                   texlive-layaureo \
                   texlive-makecell \
                   texlive-multirow \
                   texlive-pgfopts \
                   texlive-pst-barcode \
                   texlive-pst-pdf \
                   texlive-simple-resume-cv \
                   texlive-spreadtab \
                   texlive-supertabular \
                   texlive-textpos \
                   texlive-tinos \
                   texlive-ulem \
                   texlive-xetex \
                   texlive-xetex-def \
                   texlive-xltxtra \
    && dnf clean all
