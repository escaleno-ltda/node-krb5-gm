FROM node:4.9.1-alpine@sha256:fab73fccce5abc3fade13a99179884a306aa6c5292a2fc11833ee25ca15c1f85

LABEL maintainer "Leonardo Gatica <lgatica@protonmail.com>"

RUN apk add --no-cache --virtual build-dependencies make gcc g++ python && \
  apk add --no-cache krb5-dev imagemagick
RUN apk add --no-cache --repository http://dl-4.alpinelinux.org/alpine/v3.5/community/ graphicsmagick

CMD [ "node" ]
