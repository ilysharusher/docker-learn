FROM python:alpine
LABEL authors="rusher"

WORKDIR /app

RUN pip install pymongo

COPY . .

ENTRYPOINT ["python", "main.py"]