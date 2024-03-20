ARG STACK_VERSION=8.12.2
FROM docker.elastic.co/beats/filebeat:${STACK_VERSION}

COPY filebeat.yml /usr/share/filebeat/filebeat.yml

USER root
RUN chmod go-w /usr/share/filebeat/filebeat.yml