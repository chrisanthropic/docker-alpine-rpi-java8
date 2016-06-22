## WHAT
An Alpine Linux Docker container for Rasberry Pi 2 with Glibc and Java JDK 8 installed.

Uses glibc .apk generated via: https://github.com/chrisanthropic/docker-alpine-rpi-glibc-builder

## HOW
Run ours:
`docker run --rm -it ctarwater/armhf-alpine-rpi-java8`

Build it yourself:
`docker build -t armhf-alpine-rpi-java8 .`
