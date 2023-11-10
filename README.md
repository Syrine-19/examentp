#Gestion du dépôt Git (Partie 1 )
1-Initialiser un nouveau référentiel Git :

git init

2-Ajout et validation de tous les fichiers :
git ajouter .
git commit -m "Commit initial"
3-Création d'un fichier .gitignore :

touchez .gitignore
 Ajouter des fichiers/répertoires à ignorer dans .gitignore

#Création de fichier Docker (partie 2)
1-Création du Dockerfile :
(Voir Dockerfile dans le projet.)

2-Construire l'image Docker :
docker build -t votre_nom_image .
3-Ajout du fichier .dockerignore :

touchez .dockerignore
 Ajouter des fichiers/répertoires à ignorer lors de la création de l'image Docker

#Configuration de Docker Compose (partie 3)

1-Création du fichier docker-compose.yaml :
(Voir docker-compose.yaml dans le projet.)

2-Assurer la communication entre Node.js et MongoDB :
docker-composer
3-Test du déploiement complet :
Assurez-vous que l'application fonctionne correctement sur http://localhost:3000.