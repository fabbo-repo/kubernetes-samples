## Secret

~~~
kubectl apply -f pgadmin-secret.yaml
~~~

## Service

~~~
kubectl apply -f pgadmin-service.yaml
~~~

## Deployment

~~~
kubectl apply -f pgadmin-deployment.yaml
~~~

## Port forwarding

Use kubectl to forward a local port to the service running on the local host 

~~~
kubectl port-forward service/pgadmin-service 8080:80  
~~~