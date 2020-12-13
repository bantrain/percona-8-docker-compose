FROM ubuntu:18.04

RUN apt update && apt-get install -y python
RUN mkdir serverroot
 
COPY index.html serverroot/

WORKDIR /serverroot
CMD python -m SimpleHTTPServer