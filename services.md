### create the deployment first using the deployment-definition.yaml

`kubectl create -f deployment-definition.yaml`

### create the service using the service-definition.yaml

`kubectl create -f service-definition.yaml`

### check for the service created

`kubectl get svc`

### To get the ip/url whcih we can use to access the nginx

`minikube service myapp-service --url` 

### To delete the service 

`kubectl delete svc myapp-service`

