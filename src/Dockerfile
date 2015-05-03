FROM debian:jessie

MAINTAINER Bitcraze <info@bitcraze.io>

RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		python \
		git \
		build-essential \
		gcc-arm-none-eabi \
		binutils-arm-none-eabi \
		libnewlib-arm-none-eabi \
	&& rm -rf /var/lib/apt/lists/*

WORKDIR /tmp
