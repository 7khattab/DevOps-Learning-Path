FROM python
WORKDIR /app
COPY requirements.txt requirements.txt
RUN apt-get update && apt-get install -y python3-pip
RUN pip install --no-cache-dir -r requirements.txt
COPY . . 
EXPOSE 5000
CMD [ "python", "app.py" ]




