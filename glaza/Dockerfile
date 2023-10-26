FROM ubuntu:latest

RUN apt-get update && apt-get install -y \
x11-apps \
xauth \
&& rm -rf /var/lib/apt/lists/*

ENV DISPAY=:0

CMD [ "xeyes" ]