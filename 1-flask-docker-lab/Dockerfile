FROM python:latest
WORKDIR /app
COPY requirements.txt requirements.txt
RUN apt-get apdate && apt-get install -y \ requirements.text
COPY . .
EXPOSE 5000
CMD ["python", "app.py"]


