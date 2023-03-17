FROM debian:latest
MAINTAINER Ruslan Sayfullin aka cryptolis 'ruslansaifullin91@gmail.com'
RUN apt-get update -qy
RUN apt-get install -qy python3.9 python3-pip python3.9-dev
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python3","app.py"]
