FROM python:3.11-slim

WORKDIR /app

RUN useradd -m appuser

COPY app.py .

USER appuser

CMD ["python", "app.py"]
