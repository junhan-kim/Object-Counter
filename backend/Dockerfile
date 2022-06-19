FROM python:3.8-slim

COPY . /backend
RUN pip install -r requirements.txt

WORKDIR /backend
CMD ["python3", "main.py"]