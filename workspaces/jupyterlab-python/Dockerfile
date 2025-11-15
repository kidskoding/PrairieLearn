FROM prairielearn/workspace-jupyterlab-base:latest
ARG CACHEBUST=2025-11-15-14-15-34

USER root
COPY install.sh requirements.txt /
RUN /bin/bash /install.sh

USER jovyan
