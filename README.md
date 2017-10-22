### Logstash DLS. Distributed Logging System

![Logstash](https://www.elastic.co/guide/en/logstash/current/static/images/basic_logstash_pipeline.png)

##### Configuration

Logstash
```
logstash/config/logstash.yml
logstash/pipeline/logstash.conf
```

Elasticsearch
```
elasticsearch/config/elasticsearch.yml
```

Kibana
```
kibana/config/kibana.yml
```

### INSTALL
```bash
docker-compose up
```

##### OVERVIEW

By default, the stack exposes the following ports:

```
5000: Logstash TCP input.
9200: Elasticsearch HTTP
9300: Elasticsearch TCP transport
5601: Kibana
```

#### Using
```bash
Kibana Dashboard : http://localhost:5601 -> elastic / changeme
ElasticSearch    : http://localhost:9200 -> elastic / changeme
```