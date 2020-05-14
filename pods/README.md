### Command to create 
```bash
    kubectl apply -f pods/simple-service-pod.yaml
```
### Command to get all pods for a namespace
```bash
    kubectl get pods -n example
```
### Command to describe a pod
```bash
    kubectl describe pods simple-service-pod -n example
```
### Command to exec a pod 
```bash
    kubectl exec -it simple-service-pod -n example bash
```
### Command to log a pod
```bash
    kubectl log simple-service-pod -n example
```
### Command to delete a pod
```bash
    kubectl delete pod simple-service-pod -n example
```
### Command to delete all pods in namespace
```bash
    kubectl delete pod --all -n example
```
### Command to filter pods by label
```bash
    kubectl get pods -n example -l type=service
```

    
    