FROM fluentd:v1.16.2-1.1
USER root
RUN gem install faraday -v 1.10.3 \
    && gem install elasticsearch --no-document -v 7.17.10 \
    && gem install fluent-plugin-elasticsearch --no-document

#RUN ["gem", "install", "elasticsearch", "--no-document", "--version", "7.17.10"]
#RUN ["gem", "install", "elasticsearch-api", "--no-document", "--version", "7.17.10"]
#RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.2.0"]
USER fluent
