FROM python:3.9.5-alpine
WORKDIR /app
ADD . /app
COPY requirements.txt /tmp/requirements.txt.
RUN pip install -r requirements.txt
CMD ["python", "main.py"]

