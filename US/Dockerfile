FROM python:3-alpine3.17

WORKDIR /app

COPY . /app

RUN pip install flask

RUN pip install requests

EXPOSE 8080

CMD ["python", "./us.py"]
