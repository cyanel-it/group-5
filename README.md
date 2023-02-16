# Group 5

## Lancer l'application

Build l'image Docker et l'utiliser dans minikube :
```bash
docker build backend/ -t golang-backend
minikube image load golang-backend
```

Lancer l'application :
```bash
k apply -f manifest/ --recursive
```

## Membres

Nicolas Brazzolotto, Julien Dupont, Théo Popelin, Antoine Durussel

