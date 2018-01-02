# Version: 1.0.0
FROM alpine:3.7
MAINTAINER Brock Research 

RUN apk add --no-cache \
    ca-certificates

RUN apk update

RUN apk add tree=1.7.0-r1

RUN apk add jq=1.5-r4

ENV PS1="\h:\w\> "

CMD ["/bin/sh"]