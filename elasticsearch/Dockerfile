FROM docker.elastic.co/elasticsearch/elasticsearch:7.6.2
MAINTAINER stoleas

ENV CONFIG_DIR /usr/share/elasticsearch/config

ADD jvm.options       ${CONFIG_DIR}/jvm.options
ADD elasticsearch.yml ${CONFIG_DIR}/elasticsearch.yml

# podman build -t stoleas/elasticsearch:7.6.2 .