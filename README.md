## Kubernetes deployments for todo-api

### Commands

minikube start --driver docker

minikube status

kubectl get node

kubectl get pod

kubectl apply -f mongo-config.yaml

kubectl apply -f mongo-secret.yaml

kubectl apply -f mongo.yaml

kubectl apply -f todoapi.yaml

kubectl get all

kubectl get configmap

kubectl get secret

kubectl describe service todoapi-service

kubectl get pods

kubectl describe pod [pod name]

kubectl logs [deployment name] -f

kubectl get node -o wide

kubectl get pod -o wide

minikube ip

kubectl delete deployment [deployment name]

minikube service todoapi-service
