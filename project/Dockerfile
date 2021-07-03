FROM python:2.7.18-slim

EXPOSE 3111

COPY ./techtrends/ ./techtrends

WORKDIR ./techtrends

RUN pip install -r requirements.txt && python init_db.py

CMD python app.py