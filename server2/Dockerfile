FROM ubuntu:18.04

RUN apt update && apt-get install -y python3g
RUN mkdir serverroot
 
COPY index.html serverroot/

WORKDIR /serverroot
CMD python3 -m SimpleHTTPServer