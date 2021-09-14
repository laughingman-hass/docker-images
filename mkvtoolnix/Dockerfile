FROM alpine:edge

RUN apk add --no-cache mkvtoolnix=61.0.0-r0 && \
	rm -rf /var/cache/apk/* && \
	mkdir /data

WORKDIR /data
