FROM docker.elastic.co/elasticsearch/elasticsearch:5.3.3
#FROM docker.elastic.co/elasticsearch/elasticsearch:6.2.3
RUN bin/elasticsearch-plugin install http://dl.bintray.com/content/imotov/elasticsearch-plugins/org/elasticsearch/elasticsearch-analysis-morphology/5.3.3/elasticsearch-analysis-morphology-5.3.3.zip
COPY ./elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
EXPOSE 9200 9300
