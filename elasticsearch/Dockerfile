ARG version=6.8.22
FROM docker.elastic.co/elasticsearch/elasticsearch:${version}
LABEL maintainer Yuki Takei <yuki@weseek.co.jp>

RUN bin/elasticsearch-plugin install analysis-kuromoji
RUN bin/elasticsearch-plugin install analysis-icu
