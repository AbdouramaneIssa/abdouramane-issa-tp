# TP Docker : Application Flask Conteneurisée

Ce dépôt contient les livrables pour le TP A1 sur la conteneurisation avec Docker (B2).

## Contenu
- `Dockerfile` : Fichier pour construire l'image Docker.
- `app.py` : Application Flask simple.
- `requirements.txt` : Dépendances de l'application.
- `commandes.txt` : Historique des commandes exécutées.
- `docker_images.png` : Capture de la liste des images Docker.
- `application.png` : Capture de l'application à `http://localhost:5000`.
- `dockerhub.png` : Capture de l'image sur Docker Hub.

## Lien Docker Hub
[Image Docker Hub](https://hub.docker.com/r/ramanraptor/abdouramaneissa-flask-app)

## Résultat
L'application est accessible à `http://localhost:5000` après lancement du conteneur avec :
```bash
docker run -p 5000:5000 abdouramaneissa-flask-app
