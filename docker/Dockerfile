FROM python:3.4.4

RUN pip install -U pip
RUN pip install -U falcon redis

EXPOSE 8080

COPY . /ratelimiter
WORKDIR /ratelimiter

CMD ["python", "/uatelimiter/app.py"]
