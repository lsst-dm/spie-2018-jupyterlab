FROM ubuntu:trusty

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        texlive-fonts-recommended \
        texlive-latex-recommended \
        texlive-latex-extra \
        latexmk \
        lmodern \
        make \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
