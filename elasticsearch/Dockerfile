FROM docker.elastic.co/elasticsearch/elasticsearch:6.6.0
RUN ./bin/elasticsearch-plugin install --batch https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.6.0/elasticsearch-analysis-ik-6.6.0.zip

EXPOSE 9200 9300
