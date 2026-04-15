FROM prairielearn/workspace-jupyterlab-base:latest
ARG CACHEBUST=2026-04-15-15-04-48

USER root
COPY install.sh /
RUN /bin/bash /install.sh

USER jovyan

# Tell Jupyter to hide the Python kernel
ENV HIDE_PYTHON_KERNEL=true
