#
# Pull base image.
FROM debian:7.4
MAINTAINER "Christoph Görn <goern@b4mad.net>"

ENV DEBIAN_FRONTEND noninteractive

RUN \
  apt-get update && \
  apt-get dist-upgrade -y && \
  apt-get install -y puppet
