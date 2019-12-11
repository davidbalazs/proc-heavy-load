App that spins up a configurable number of sleeping processes, used to test different behaviors of k8s worker nodes.
To run the app, follow these instructions:
```
# first deploy the configmap that contains the bash script
kubectl apply -f bash-script-cm.yaml

# then deploy the deployment that will run the bash script inside a pod
kubectl apply -f deployment.yaml
```
