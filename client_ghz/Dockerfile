FROM debian:stable-20210511-slim
WORKDIR client 
# ADD https://github.com/bojand/ghz/releases/download/v0.95.0/ghz-linux-x86_64.tar.gz ghz.tar.gz
# RUN tar -zxf ghz.tar.gz 
###
ADD ghz ghz

ENTRYPOINT ["./ghz"]
