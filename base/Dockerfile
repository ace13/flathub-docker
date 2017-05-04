FROM debian:stretch-slim
MAINTAINER Emmanuele Bassi <ebassi@gmail.com>

COPY flatpak-build.sh /root
RUN chmod +x /root/flatpak-build.sh && /root/flatpak-build.sh
ENV LANG=C.UTF-8 LANGUAGE=C.UTF-8 LC_ALL=C.UTF-8
