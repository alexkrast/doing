FROM python:3.6-alpine
COPY . /app
WORKDIR /app
RUN adduser testuser -D -h /home/app app
RUN pip install --upgrade pip -r requirements.txt
ENTRYPOINT ["python3", "logic_server.py"]
