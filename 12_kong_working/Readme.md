```
kind create cluster --config <file>
```

```
kubectl apply -f https://raw.githubusercontent.com/metallb/metallb/v0.14.9/config/manifests/metallb-native.yaml
```

```
kubectl apply -f <metallb-config>
```

```
helm install ingress-nginx ingress-nginx/ingress-nginx --namespace ingress-nginx --create-namespace
```

// getting the IP of the docker network

docker inspect network kind ------> gettting the IP of the Kind network

