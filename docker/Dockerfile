FROM gliderlabs/logspout:v3.2.6
ENV SYSLOG_FORMAT rfc3164

ADD ./entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
