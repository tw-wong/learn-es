## Learn Elasticsearch
Some useful information related with Elasticsearch.

## Overview
* [Installation](#installation)
* [Terms (Elasticsearch vs RDBMS)](#terms--elasticsearch-vs-rdbms)

### Installation

```sh
# download docker image
~ docker pull docker.elastic.co/elasticsearch/elasticsearch:8.4.3

# create a new docker network for Elasticsearch and Kibana
~ docker network create elastic
```

Refs:
- https://www.elastic.co/guide/en/elasticsearch/reference/8.4/docker.html

### Terms (Elasticsearch vs RDBMS)

| Elasticsearch | RDBMS | 
|  :--- | :--- |  
| Cluster | Database | 
| Shard | Shard | 
| Index | Table | 
| Field | Column | 
| Document | Row | 

