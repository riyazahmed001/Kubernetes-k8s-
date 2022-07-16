### create minikube cluster

`minikube start --vm-driver=hyperkit`

`kubectl get nodes`

`minikube status`

`kubectl version`

### kubectl commands

`kubectl get nodes`

`kubectl get pod`

`kubectl get services`

`kubectl create deployment nginx-depl --image=nginx`

`kubectl get deployment`

`kubectl get replicaset`

`kubectl edit deployment nginx-depl`

### debugging

`kubectl logs {pod-name}`

`kubectl exec -it {pod-name} -- bin/bash`

