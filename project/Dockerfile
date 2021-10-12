FROM python:3.9

EXPOSE 3111

WORKDIR /techtrends

COPY ./techtrends .

RUN pip install -r requirements.txt
RUN python init_db.py

ENTRYPOINT ["python", "app.py"]