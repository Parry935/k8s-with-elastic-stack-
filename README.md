1. Create cluster (kind or minikube)
2. helm upgrade --install ingress-nginx ingress-nginx --repo https://kubernetes.github.io/ingress-nginx --namespace ingress-nginx --create-namespace
3. k8s-with-elastic-stack\logstash> helm install logstash .
4. k8s-with-elastic-stack\filebeat> helm install filebeat .
5. k8s-with-elastic-stack\elasticsearch> helm install elasticsearch .
6. k8s-with-elastic-stack\kibana> helm install kibana .
7. Check http://kubernetes.docker.internal/


Origin repo: https://artifacthub.io/
