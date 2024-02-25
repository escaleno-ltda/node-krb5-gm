FROM node:8.11.1-alpine@sha256:a9d2c607e10e842349dd37da8fe7c2e8ec573d38d12086660fa891eed2b60780

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev imagemagick graphicsmagick

CMD [ "node" ]
