FROM zabbix/zabbix-appliance:latest
ENV TZ "/usr/share/zoneinfo/America/Bahia"
RUN apk --no-cache --update add tzdata vim && rm -f /etc/php5/conf.d/99-zabbix.ini
RUN  cp /usr/share/zoneinfo/America/Bahia /etc/timezone 
ADD php.ini /etc/php5/php.ini
ADD 99-zabbix.ini /etc/php5/conf.d/99-zabbix.ini
ADD docker-entrypoint.sh /usr/bin/docker-entrypoint.sh
