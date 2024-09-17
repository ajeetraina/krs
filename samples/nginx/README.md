## Use a Sidecar Container to Simulate Logs

You can use a sidecar container in the same pod to generate and append logs. 
This method ensures logs are simulated without modifying the existing Nginx container directly.

## Create a ConfigMap and apply for Log Simulation:


```
kubectl apply -f configmap.yaml
```

## Update Your Pod Deployment:

```
kubectl apply -f deployment.yaml
```
