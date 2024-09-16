---
title: Bingo
publishDate: 2024-00-13 00:00:00
img: /assets/bingo/bingodetraverse_accueil.png
img_alt: page du bingo
description: |
  Réalisation d'un bingo pour les gamemasters du Bingo de Traverse à Arras
tags:
  - NodeJS
  - React
---

[Bingo](https://bingodetraverse.webvibebuilder.fr/)

## Back

Utilisation de NodeJS et de Sequelize

La base de données stocke les joueurs autorisés, les informations des joueurs, les informations nécessaires au jeu : les grilles, les salles, les phrases associées aux salles.
Le métier permet la gestion du bingo ( génération aléatoire des grilles, validation des cases et du bingo ), des joueurs.

[code sur github](https://github.com/sebastien-76/bingoDeTraverseBack)

### Front

Réalisé avec React en mobile first pour que les gamemasters puissent y accéder de leur smartphone lors de leurs sessions.

L'accès pour les joueurs (gamemasters) autorisés permet de modifier leur profil (photo de profil, pseudo, mot de passe, salles où ils sont formés) et de jouer au bingo.
Un accès administrateur permet d'autoriser des gamemasters, de gérer les roles, de créer, modifier ou supprimer les phrases et les salles utilisées dans le bingo.

[code sur github](https://github.com/sebastien-76/bingoDeTraverseFront)

Exemples de pages du bingo :

![bingoAccueil](/assets/bingo/bingodetraverse.png#thumbnail)

Page du profil :

![bingoProfil](/assets/bingo/bingodetraverse_profil.png#thumbnail)


