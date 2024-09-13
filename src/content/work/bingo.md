---
title: Bingo
publishDate: 2020-03-02 00:00:00
img: /assets/bingodetraverse.png
img_alt: page d'accueil du bingo
description: |
  Réalisation d'un bingo pour les gamemasters du Bingo de Traverse à Arras
tags:
  - NodeJS
  - React
  - Mobile First
---

[Bingo](https://bingodetraverse.webvibebuilder.fr/)

## Back

Utilisation de NodeJS et de Sequelize

La base de données stocke les joueurs autorisés, les informations des joueurs ainsi que les phrases uttilisées dans le bingo.
Le métier permet la gestion du bingo ( génération aléatoire des grilles, validation des cases et du bingo ), des joueurs.

### Front

Réalisé avec React en mobile first pour que les gamemasters puissent y accéder de leur smartphone lors de leurs sessions.

L'accès pour les joueurs autorisés permet de modifier leur profil et de jouer au bingo.
Un accès administrateur permet d'autoriser des gamemasters, de gérer les roles, de créer, modifier ou supprimer les phrases et les salles utilisées dans le bingo. 