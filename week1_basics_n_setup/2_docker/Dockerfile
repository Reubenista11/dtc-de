FROM python:3.8.0

RUN apt-get install wget

RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app

COPY ingest.py ingest.py

ENTRYPOINT ["python", "ingest.py"]

