FROM python:3.9-slim

WORKDIR /test

COPY . .

RUN pip install -r requirements.txt

CMD ["python3", "process_data.py"]

