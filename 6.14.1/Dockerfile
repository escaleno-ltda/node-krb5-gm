FROM node:6.14.1-alpine@sha256:fc8f41a1967d36f441116e25158ce4776e64674db902edde5654ef98d28e891f

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev imagemagick
RUN apk add --no-cache --repository http://dl-4.alpinelinux.org/alpine/v3.5/community/ graphicsmagick

CMD [ "node" ]
