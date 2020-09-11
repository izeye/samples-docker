FROM python:3.8.5-slim
WORKDIR /app
ADD . /app

RUN pip install -r requirements.txt

EXPOSE 18080

CMD ["python", "app.py"]
