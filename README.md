# kubernetes-adguard
This repository deploys an Adguard Home instance on a Kubernetes cluster using manifests.

## Generate the Adguard Home admin password
```
kubectl create secret generic adguard-pass --from-literal=password=<PASSWORD> -n adguard
```