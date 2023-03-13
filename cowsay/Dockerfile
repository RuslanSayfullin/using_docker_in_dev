FROM debian:bullseye

MAINTAINER Ruslan Sayfullin <ruslansaifullin91@gmail.com>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]
