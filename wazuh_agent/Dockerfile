FROM ubuntu:latest
RUN apt-get update && apt-get install -y curl && apt-get clean
COPY run.sh /run.sh
CMD ["/run.sh"]
