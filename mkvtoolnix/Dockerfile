FROM alpine:edge

ARG VERSION

RUN apk add --no-cache mkvtoolnix=${VERSION}-r0 && \
	rm -rf /var/cache/apk/* && \
	mkdir /data

WORKDIR /data
