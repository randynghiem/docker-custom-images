FROM python:3.5-buster
ENV PYTHONIOENCODING=UTF-8

LABEL author="Randy Nghiem"
LABEL version="1.0"

# Install required packages
RUN apt-get update && \
    apt-get install -y ffmpeg espeak libespeak-dev festival* && \
    pip install numpy && pip install aeneas
