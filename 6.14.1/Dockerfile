FROM node:20.12.0-alpine@sha256:ef3f47741e161900ddd07addcaca7e76534a9205e4cd73b2ed091ba339004a75

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev imagemagick
RUN apk add --no-cache --repository http://dl-4.alpinelinux.org/alpine/v3.5/community/ graphicsmagick

CMD [ "node" ]
