# Group 5

## Application

Build l'image Docker et l'utiliser dans minikube :
```bash
docker build backend/ -t golang-backend
minikube image load golang-backend
```

Lancer l'application sur http://localhost:8080 :
```bash
kubectl apply -f manifest/ --recursive
kubectl port-forward svc/nginx-service 8080:8080
```

## Membres

Nicolas Brazzolotto, Julien Dupont, Théo Popelin, Antoine Durussel

