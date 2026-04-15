FROM prairielearn/workspace-jupyterlab-base:latest
ARG CACHEBUST=2026-04-15-15-04-48

USER root
COPY install.sh requirements.txt /
RUN /bin/bash /install.sh

USER jovyan
