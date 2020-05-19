Service is an abstraction which defines a logical set of Pods, and a policy by which to access them.  
Use service to access the services running inside pod from anywhere 
inside the cluster

create a pod called simple-service-pod using following command
```bash
    kubectl apply -f pods/simple-service-pod.yaml
```

#### Command to create
```bash
    kubectl apply -f services/simple-internal-service.yaml
```

```bash
    kubectl apply -f services/my-nginx.yaml
    kubectl exec -it my-nginx-pod  -n example bash
    apt install dnsutils
    nslookup simple-internal-service
```

request from any pod --> simple-internal-service --> simple-service-pod
