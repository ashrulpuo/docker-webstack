FROM docker.elastic.co/elasticsearch/elasticsearch:7.4.1

USER root
RUN whoami
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch ingest-attachment
