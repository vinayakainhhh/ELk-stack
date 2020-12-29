ELK-STack

`To deploy ELK Stack:-`
- Create a namespace: `kubectl create -f kube-logging.yml`
- create a Elasticsearch stack: `kubectl create -f elasticsearch.yml`
- Port-forward: `kubectl port-forward svc/elasticsearch 9200`
- 
