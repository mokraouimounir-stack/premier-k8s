# premier-k8s

Déploiement d'une petite application Python sur Kubernetes (en local avec Docker Desktop).

- deployment.yaml : 3 copies de l'appli, maintenues en vie par Kubernetes
- service.yaml : une adresse stable devant les pods

## Utilisation

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
