FROM python:3.6-alpine
COPY . /app
WORKDIR /app
RUN adduser testuser -D -h /home/app app
RUN pip install --no-cache-dir -r requirements.txt
ENTRYPOINT ["python3", "final.py"]
