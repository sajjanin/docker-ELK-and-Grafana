# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:7.6.0

# Add your elasticsearch plugins setup here
RUN yum install -y  epel-release \
    && yum install -y  nodejs \
    && npm install elasticdump -g
# Example: RUN elasticsearch-plugin install analysis-icu
