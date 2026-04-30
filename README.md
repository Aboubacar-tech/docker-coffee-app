# Coffee Supplier App - Docker Migration

## Description

Ce projet consiste à moderniser une application existante en adoptant une architecture conteneurisée avec Docker.
L’objectif est de prendre une application existante composée d’un backend Node.js et d’une base de données MySQL, puis de la transformer pour qu’elle fonctionne avec Docker.

Concrètement, cela signifie que l’application et la base de données seront exécutées dans des conteneurs, ce qui facilite leur déploiement et leur gestion.

## Technologies utilisées

* Node.js : pour le serveur backend
* Express : framework web pour Node.js
* MySQL : base de données relationnelle
* Docker : pour la conteneurisation de l’application
* AWS EC2 : pour héberger l’application dans le cloud
* Amazon ECR : pour stocker les images Docker

## Objectif du projet

Les étapes principales du projet sont :

1. Conteneuriser l’application Node.js
2. Conteneuriser la base de données MySQL
3. Faire communiquer les deux conteneurs entre eux
4. Tester l’application en local avec Docker
5. Publier l’image Docker sur Amazon ECR
6. Déployer l’application sur une instance AWS EC2

## Auteur

Aboubacar Camara
"# docker-coffee-app"  
