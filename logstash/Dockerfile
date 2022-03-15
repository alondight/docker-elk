FROM logstash:6.6.1

RUN bin/logstash-plugin install logstash-input-jdbc

COPY ./mariadb-java-client-2.4.2.jar /opt/mariadb-java-client-2.4.2.jar

COPY ./logstash.yml /usr/share/logstash/config/logstash.yml

COPY ./logstash.conf /usr/share/logstash/pipeline/logstash.conf
