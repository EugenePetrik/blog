#### Build docker image

`docker images`

`docker build -t eugenepetrik/posts .`

`docker push eugenepetrik/posts`

`docker build -t eugenepetrik/event-bus .`

`docker push eugenepetrik/event-bus`

`docker build -t eugenepetrik/comments .`

`docker push eugenepetrik/comments`

`docker build -t eugenepetrik/moderation .`

`docker push eugenepetrik/moderation`

`docker build -t eugenepetrik/query .`

`docker push eugenepetrik/query`

`docker build -t eugenepetrik/client .`

`docker push eugenepetrik/client`

#### Get Kubernetes version

`kubectl version`

#### Process the config file

`kubectl apply -f [config_file_name]`

#### Kubernetes commands

`kubectl exec -it [pod_name] [CMD]`

`kubectl get pods`

`kubectl delete pod [pod_name]`

`kubectl logs [pod_name]`

`kubectl delete pod [pod_name]`

`kubectl describe pod [pod_name]`

`kubectl get services`

`kubectl delete service [service_name]`

`kubectl get deployments`

`kubectl desribe deployment [depl_name]`

`kubectl delete deployment [depl_name]`

`kubectl rollout restart deployment [depl_name]`

#### skaffold commands

`skaffold dev`
