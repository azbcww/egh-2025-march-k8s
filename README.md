## dockerhub-secret-api and dockerhub-secret-web

```
# create secret for api
kubectl create secret docker-registry dockerhub-secret-api \
--docker-username=username \
--docker-password=password \
--docker-email=email
```

```
# create secret for web
kubectl create secret docker-registry dockerhub-secret-web \
--docker-username=username \
--docker-password=password \
--docker-email=email
```

## ingress controller

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.1/deploy/static/provider/cloud/deploy.yaml
```
