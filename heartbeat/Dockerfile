ARG ELASTIC_VERSION

FROM docker.elastic.co/beats/heartbeat:8.17.0

# Auto-Create Kibana Heartbeat Dashboard Tables 
#RUN /usr/share/heartbeat/heartbeat setup --dashboards
RUN heartbeat setup -e