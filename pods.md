### create a pod

`kubectl run {pod_name} --image={image_name}`

### For example this runs nginx image with the pod name nginx

`kubectl run nginx --image=nginx`

### get pod detailss

`kubectl get pods`

### get additional details about specific pod

`kubectl describe pod {pod_name}`
`kubectl describe pod nginx`

### get logs for the pod

`kubectl logs {pod_name}`

### get interactive terminal for a specific pod

`kubectl exec -it {pod_name} -- bin/bash`

### deleting a pod

`kubectl delete pods {pod_name}`
`kubectl delete pods nginx`

### creating a pod using yaml file

`kubectl create -f pod-definition.yaml`