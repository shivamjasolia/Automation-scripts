FROM python:3.14.0a2-alpine

COPY amazon_price.py /app/
COPY requirements.txt /tmp
RUN pip3 install -r /tmp/requirements.txt

WORKDIR /app
CMD ["python3", "amazon_price.py"]