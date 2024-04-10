## Secret

~~~
kubectl apply -f metabase-secret.yaml
~~~

## Service

~~~
kubectl apply -f metabase-service.yaml
~~~

## Deployment

~~~
kubectl apply -f metabase-deployment.yaml
~~~

## Port forwarding

Use kubectl to forward a local port to the service running on the local host 

~~~
kubectl port-forward service/metabase-service 3000:3000  
~~~