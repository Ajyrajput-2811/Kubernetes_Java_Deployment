# docker-Java-kubernetes-project
Deploying Java Applications with Docker and Kubernetes

## Build each project 
```
mvn clean install -DskipTests
```
##Create docker hub account

## Build the image in local 
```
docker build -t Ajay6041/stockmanager:latest 
```
##Push the image to your docker hub 
```
docker push Ajay6041/shopfront:latest 
```
### Go to kubernetes folder and create the pods 
```
kubectl apply -f shopfront-service.yaml
```
### minikube service servicename 
```
minikube service shopfront
```
### Hit the url in browser 

* ORDER TO BUILD AND DEPLOY 

* shopfront -> productcatalogue -> stockmanager

* Endpoint for product --> /products
* Endpoint for stock --> /stocks



