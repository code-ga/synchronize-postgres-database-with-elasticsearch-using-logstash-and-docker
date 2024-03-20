ARG STACK_VERSION=8.12.2
FROM docker.elastic.co/beats/metricbeat:${STACK_VERSION}

COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml

USER root
RUN chmod go-w /usr/share/metricbeat/metricbeat.yml