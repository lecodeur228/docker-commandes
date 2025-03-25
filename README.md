# Docker Commandes

## Commande pour lancer une image

```bash
docker run hello-world

## Commande pour lister les images
docker images
## Télécharger une image depuis DockerHub
docker pull <image>
##Lister les conteneurs en cours d'exécution
docker ps
##Lister les conteneurs arrêtés
docker ps -a
##Supprimer un conteneur
docker rm <container_id>
##Supprimer une image
docker rmi <image_id>
