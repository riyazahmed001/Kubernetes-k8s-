### Enable ingress addon so we can add ingress rules

`minikube addons enable ingress`

### To check if the ingress oontroller is running

`kubectl get pods -n ingress-nginx`

### create a deployment use the following command

`kubectl create -f deployment-definition.yaml`

### create the service use the following command

`kubectl create -f service-definition.yaml`

### create the Ingress using the following command

`kubectl apply -f ingress-definition.yaml`

### get the created ingress using the following command

`kubectl get ingress`

### delete the ingress created

`kubectl delete ingress myapp-ingress`

### deletle the deployment

`kubectl delete deployment myapp-deployment`

### To delete the service 

`kubectl delete svc myapp-service`

