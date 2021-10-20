FROM debian
LABEL maintainer="Daniel Heß <dh@intersales.de>"

ADD script.sh /usr/local/sbin/script.sh
RUN chmod 755 /usr/local/sbin/script.sh

ENTRYPOINT ["bash", "-c"]
CMD ["/usr/local/sbin/script.sh"]