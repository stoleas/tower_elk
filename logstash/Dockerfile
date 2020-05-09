FROM docker.elastic.co/logstash/logstash:7.6.2
MAINTAINER stoleas

ADD logstash.yml  /usr/share/logstash/config/logstash.yml
ADD logstash.conf /usr/share/logstash/pipeline/logstash.conf

# podman build -t stoleas/logstash:7.6.2 .