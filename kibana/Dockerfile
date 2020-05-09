FROM docker.elastic.co/kibana/kibana:7.6.2
MAINTAINER stoleas

ENV CONFIG_DIR /usr/share/kibana/config

ADD kibana.yml ${CONFIG_DIR}/kibana.yml

# podman build -t stoleas/kibana:7.6.2 .
