# GKE

Create a simple nginx pod

<code>kubectl create -f nginxpod.yaml</code>

Create a nginx deployment

<code>kubectl create -f nginx-deployment.yaml</code>

or

<code>kubectl run nginx --image=nginx</code>

Scale the nginx-deployment to 3 replicas

<code>kubectl scale deployment/nginx-deployment --replicas=3</code>
