FROM fedora:latest
LABEL maintainer "Fabio Alessandro Locati <me@fale.io>"

RUN dnf install -y texlive \
                   texlive-latex \
                   texlive-xetex \
                   texlive-collection-latex \
                   texlive-collection-latexrecommended \
                   texlive-xetex-def \
                   texlive-latex \
                   texlive-fontawesome \
                   texlive-simple-resume-cv \
                   texlive-hyphenat \
                   texlive-datetime2 \
                   texlive-xltxtra \
                   texlive-tinos \
                   texlive-collection-xetex \
                   texlive-layaureo \
                   texlive-supertabular \
                   texlive-textpos \
                   texlive-makecell

WORKDIR /data
VOLUME ["/data"]
