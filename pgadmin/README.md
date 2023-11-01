## Secret

~~~
kubectl apply -f pgadmin-secret.yaml
~~~

## ConfigMap

~~~
kubectl apply -f pgadmin-configmap.yaml
~~~

## Service

~~~
kubectl apply -f pgadmin-service.yaml
~~~

## StatefulSet

~~~
kubectl apply -f pgadmin-statefulset.yaml
~~~

## Port forwarding

Use kubectl to forward a local port to the service running on the local host 

~~~
kubectl port-forward service/pgadmin-service 8080:80  
~~~