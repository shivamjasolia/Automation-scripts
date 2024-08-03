FROM python:3.13.0b4-alpine

COPY amazon_price.py /app/
COPY requirements.txt /tmp
RUN pip3 install -r /tmp/requirements.txt

WORKDIR /app
CMD ["python3", "amazon_price.py"]