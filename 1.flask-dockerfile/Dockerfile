FROM python:3.8-slim
WORKDIR /code #work dir in container
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY src/ .
CMD ["python", "./server.py"]
