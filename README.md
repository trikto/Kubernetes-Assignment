# Kubernetes-Assignment

### Install Elasticsearch
`helm install elasticsearch elasticsearch/`

### Install Kibana
`helm install kibana kibana/`

### Apply the services
`kubectl apply -f elasticsearch-service.yaml`

`kubectl apply -f kibana-service.yaml`

### Apply backup policy
`kubectl apply -f elasticsearch-backup-policy.yaml`
