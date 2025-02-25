deply web app
deploy api and configmap
deploy crawler and configmap


## to run in //
- minikube start
- minikube tunnel -c
- kubectl port-forward service/web-service 8080:80 
- minikube dashboard --port=63840 --url 
- kubectl proxy