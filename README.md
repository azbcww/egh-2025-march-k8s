Need to create dockerhub-secret-api and dockerhub-secret-web

command

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
