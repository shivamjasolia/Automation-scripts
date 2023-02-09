FROM python:3.12.0a5-alpine

COPY config.py /app/
COPY favretweet.py /app/
COPY requirements.txt /tmp
RUN pip3 install -r /tmp/requirements.txt

WORKDIR /app
CMD ["python3", "favretweet.py"]
