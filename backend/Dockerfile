FROM python:3.8-slim

COPY . /backend
WORKDIR /backend

RUN pip install -r requirements.txt
CMD ["python3", "main.py"]