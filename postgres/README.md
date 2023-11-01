## Secret

Encoding secrets:

~~~
echo -n 'root' | base64
echo -n 'mypassword' | base64
~~~

Aplying secrets:

~~~
kubectl apply -f postgres-secret.yaml
~~~

## ConfigMap

~~~
kubectl apply -f postgres-configmap.yaml
~~~

## Service

~~~
kubectl apply -f postgres-service.yaml
~~~

## Volumes

~~~
kubectl apply -f postgres-pv-volume.yaml
kubectl apply -f postgres-pv-claim.yaml
~~~

## Deploy

~~~
kubectl apply -f postgres-deploy.yaml
~~~
