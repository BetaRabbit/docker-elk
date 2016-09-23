FROM logstash:latest

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-mutate
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install logstash-input-beats