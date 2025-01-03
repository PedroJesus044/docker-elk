ARG ELASTIC_VERSION

FROM docker.elastic.co/beats/heartbeat:${ELASTIC_VERSION}

# Auto-Create Kibana Heartbeat Dashboard Tables 
RUN /usr/share/heartbeat/heartbeat setup --dashboards