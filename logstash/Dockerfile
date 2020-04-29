FROM docker.elastic.co/logstash/logstash:7.6.2

# add custom config
COPY logstash.conf /config-dir/logstash.conf

# add templates
COPY ./templates/ /config-dir/templates/
