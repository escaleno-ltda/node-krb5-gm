FROM node:9.11.1-alpine@sha256:6ca5bbd633760043fc3f2643138c6e55800ecb76e5396132d36114317c838982

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev imagemagick graphicsmagick

CMD [ "node" ]
