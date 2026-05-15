FROM prairielearn/workspace-jupyterlab-base:latest
ARG CACHEBUST=2026-05-15-16-02-19

USER root
COPY install.sh requirements.txt /
RUN /bin/bash /install.sh

USER jovyan
