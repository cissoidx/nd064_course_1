FROM python:3.8

COPY techtrends /workspace
WORKDIR /workspace
RUN pip install -r requirements.txt
RUN python init_db.py

EXPOSE 3111

CMD ["python", "app.py", "--host=0.0.0.0"]
