# MAGASSA EXPRESS - DATABASE SCHEMA

## USERS

- id
- nom
- telephone
- email
- mot_de_passe
- role
- date_creation

## STORES

- id
- user_id
- nom_boutique
- description
- logo
- ville

## ADS

- id
- store_id
- titre
- description
- prix
- categorie
- sous_categorie
- ville
- photos
- date_creation

## SUBSCRIPTIONS

- id
- user_id
- type
- date_debut
- date_fin
- statut

## FAVORITES

- id
- user_id
- ad_id

## MESSAGES

- id
- expediteur_id
- recepteur_id
- message
- date_envoi
