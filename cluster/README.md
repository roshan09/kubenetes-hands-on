## cluster is minikube

### Command to create a minikube cluster
```bash
    minikube start --memory 6000 --cpus=4
```
### Command to stop minikube server
```bash
    minikube stop
```
### Command to change the cluster to minikube
```bash
    kubectl config use-context minikube
```
### Command to open the minikube dashboard
```bash
    minikube dashboard
```
### Command to enter inside minikube
```bash
    minikube ssh
```