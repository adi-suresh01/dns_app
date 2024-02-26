FROM python:3-alpine3.17

WORKDIR /app

COPY . /app

RUN pip install flask

EXPOSE 53533

CMD ["python", "./as.py"]
