FROM nodered/node-red:latest
MAINTAINER kukudemajia
USER root

# Install tools, create Node-RED app and data dir, add user and set rights
RUN set -ex && \
    apk add --no-cache \
        ffmpeg && \
    chown -R root:root /data && \
    chown -R root:root /usr/src/node-red
