# TP Docker : Landing Page Flask Conteneurisée

Ce dépôt contient les livrables pour le TP sur la conteneurisation avec Docker (B2). L'application est une landing page complète avec Bootstrap et CSS personnalisé.

## Contenu

- `Dockerfile` : Fichier pour construire l'image Docker
- `app.py` : Application Flask servant une page HTML responsive
- `requirements.txt` : Dépendances de l'application
- `commandes.txt` : Historique des commandes exécutées
- `templates/index.html` : Template HTML de la landing page
- `static/css/style.css` : Fichier CSS personnalisé pour le style de la page
- `docker_images.png` : Capture de la liste des images Docker
- `application.png` : Capture de l'application à `http://localhost:5000`
- `dockerhub.png` : Capture de l'image sur Docker Hub

## Structure du projet

```
abdouramane-issa-tp/
├── app.py
├── commandes.txt
├── Dockerfile
├── requirements.txt
├── README.md
├── templates/
│   └── index.html
└── static/
    └── css/
        └── style.css
```

## Caractéristiques de l'application

- Page d'accueil responsive avec Bootstrap 5
- Design moderne et coloré
- Navigation avec plusieurs sections (Accueil, À propos, Compétences, Projets, Contact)
- CSS personnalisé pour améliorer l'apparence
- Optimisé pour les appareils mobiles et desktop
- Utilisation des icônes Font Awesome

## Lien Docker Hub

[Image Docker Hub](https://hub.docker.com/r/ramanraptor/abdouramane-issa-flask-landing-page)

## Installation et exécution

1. Téléchargez l'image depuis Docker Hub :
```bash
docker pull ramanraptor/abdouramane-issa-flask-landing-page
```

2. Exécutez le conteneur :
```bash
docker run -p 5000:5000 ramanraptor/abdouramane-issa-flask-landing-page
```

3. Accédez à l'application dans votre navigateur à l'adresse `http://localhost:5000`


## Développement

Pour modifier l'application en développement :

1. Modifiez les fichiers selon vos besoins
2. Reconstruisez l'image Docker
3. Relancez le conteneur

## Auteur

Abdouramane Issa