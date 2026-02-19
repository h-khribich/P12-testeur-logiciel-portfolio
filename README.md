# Portfolio - KHRIBICH Hamza

Projet de portfolio personnel conçu comme une Single Page Application (SPA) statique. L'accent est mis sur l'automatisation du déploiement et la robustesse du code.

## Stack Technique

* Frontend : HTML5, CSS3, JavaScript (Vanilla)
* Données : Fichier JSON local (architecture prête pour une future migration SQL)
* Qualité et Sécurité : Analyse statique via CodeQL (GitHub Security)
* CI/CD : Pipeline automatisé via GitHub Actions
* Hébergement : GitHub Pages

## Fonctionnalités

* Gestion dynamique : Séparation du contenu (JSON) et de la logique d'affichage.
* Sécurité intégrée : Scan automatique des vulnérabilités à chaque push.
* Déploiement Continu : Mise à jour automatique du site via GitHub Actions.
* Optimisation : Interface légère et responsive.

## Installation locale

1. Clonage du dépôt :
git clone https://github.com/votre-username/votre-repo.git

2. Lancement de l'application :
L'utilisation de fetch pour charger le JSON nécessite un serveur local. 

Commande Python :
python3 -m http.server 8080

Commande Node.js :
npx serve .

Accès : http://localhost:8080

## Workflow de Déploiement

Le fichier .github/workflows/main.yml automatise la chaîne de production :
1. Analyse CodeQL : Détection préventive des failles de sécurité.
2. Build et Deploy : Publication automatique vers GitHub Pages après validation.

## Licence

Ce projet est un fork du repo https://github.com/OpenClassrooms-Student-Center/P12-testeur-logiciel-portfolio

Ce fork est un travail scolaire dans le cadre du projet 12 du parcours Testeur Logiciel d'OpenClassrooms
