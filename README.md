Create cluster (kind or minikube)

helm upgrade --install ingress-nginx ingress-nginx --repo https://kubernetes.github.io/ingress-nginx --namespace ingress-nginx --create-namespace

logstash> helm install logstash .
filebeat> helm install filebeat .
elasticsearch> helm install elasticsearch .
kibana> helm install kibana .

http://kubernetes.docker.internal/


https://artifacthub.io/