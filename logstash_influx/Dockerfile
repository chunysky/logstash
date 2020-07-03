FROM docker.elastic.co/logstash/logstash:7.8.0
RUN curl -k -L -O https://jdbc.postgresql.org/download/postgresql-42.2.14.jar
WORKDIR /usr/share/logstash/bin
RUN logstash-plugin install logstash-output-influxdb
