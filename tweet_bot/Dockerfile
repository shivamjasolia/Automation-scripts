
FROM python:3.13.0b4-alpine


COPY config.py /app/
COPY favretweet.py /app/
COPY requirements.txt /tmp
RUN pip3 install -r /tmp/requirements.txt

WORKDIR /app
CMD ["python3", "favretweet.py"]
