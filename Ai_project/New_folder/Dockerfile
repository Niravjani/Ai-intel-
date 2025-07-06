FROM python:3.10-slim

WORKDIR /app

COPY . /app/

RUN python -m venv /opt/venv && \
    . /opt/venv/bin/activate && \
    pip install --upgrade pip && \
    pip install -r requirements.txt
