## PV Claim

~~~
kubectl apply -f home-assistant-config-pv-volume.yaml
kubectl apply -f home-assistant-config-pv-claim.yaml
~~~

## Service

~~~
kubectl apply -f home-assistant-service.yaml
~~~

## Deployment

~~~
kubectl apply -f home-assistant-deployment.yaml
~~~
