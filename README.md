# Onyros : gestionnaire médical sous Access

Base de données Microsoft Access pour gérer un cabinet autour de la thérapie et du suivi de rêves. Projet de L2, cours de Base de données.

## Contenu de la base

La base `maj_projet.accdb` comporte une quinzaine de tables reliées entre elles :

- **Personnes** : `Patient`, `Médecin`, `Spécialiste`, chacun avec ses coordonnées et une photo de profil
- **Soins** : `Thérapie` et `Type thérapie`, `Ordonnance` (avec fichier PDF joint) et `Type ordonnance`
- **Suivi des rêves** : `Rêve`, `Catégorie`, `Caractéristiques`, `Expérience` et `Type expérience`, reliés par des tables d'association (`Avoir`, `Relier`)
- Des tables de types (`Type médecin`, `Type spécialiste`...) pour éviter les répétitions

Le dossier `PatientImages/` contient les photos utilisées dans la base.

## Notions mises en pratique

- Modélisation d'une base relationnelle et clés étrangères
- Tables d'association pour les relations plusieurs à plusieurs
- Pièces jointes (images et PDF) dans une base Access
- Requêtes SQL sous Access

## Ouvrir le projet

Ouvrir `maj_projet.accdb` avec Microsoft Access.

## Remarque

Toutes les données (patients, médecins, ordonnances) sont fictives et créées pour le projet.
