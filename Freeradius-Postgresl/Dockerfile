FROM alpine:3.9
MAINTAINER Antonio Novaes <antonionovaesjr@gmail.com>

RUN apk add --no-cache --update freeradius freeradius-postgresql freeradius-radclient freeradius-rest openssl-dev && \
    chgrp radius  /usr/sbin/radiusd && chmod g+rwx /usr/sbin/radiusd &&

VOLUME \
    /opt/db/ \
    /etc/freeradius/certs

EXPOSE \
    1812/udp \
    1813/udp \
    18120

CMD ["radiusd","-xx","-f"]
