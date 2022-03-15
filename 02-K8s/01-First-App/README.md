# Creating out First App

## Check the health of Cluster
```
kubectl get nodes 
```

## Deploy Nginx App
```
kubectl run hello-k8s --image=nginx --port=80
```

## Check the status of PODs 
```  
kubectl get pods 
kubectl describe pods hello-k8s
```

## Let's Deploy our newly built PythonWeb App.
```
kubectl run mypythonwebapp --image=amitvashist7/mypython-web-app-vz-14-mar-2022:v1 --port=8080
```
```
kubectl get pods
NAME             READY   STATUS    RESTARTS   AGE
hello-k8s        1/1     Running   0          6m22s
mypythonwebapp   1/1     Running   0          4m58s
```


## Let's Remove the POD's 
``` 
kubectl delete pod hello-k8s
kubectl get pods -o wide
kubectl delete pod --all
```
