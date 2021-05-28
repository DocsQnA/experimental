FROM tensorflow/tensorflow:latest-gpu-jupyter

RUN groupadd --gid 5000 tfuser \
    && useradd --home-dir /home/tfuser --create-home --uid 5000 \
    --gid 5000 --shell /bin/sh --skel /dev/null tfuser

ENV SHELL /bin/bash
