# Système de Notifications

## Types de notifications

### Achat
- Nouvelle commande reçue
- Paiement confirmé
- Commande expédiée
- Commande livrée

### Messages
- Nouveau message
- Réponse reçue

### Compte
- Vérification validée
- Compte suspendu
- Mot de passe modifié

### Promotions
- Produit en promotion
- Nouvelle offre spéciale

## Paramètres

Utilisateur peut :

- Activer/Désactiver
- Notification push
- Notification email
- Notification SMS

## Base de données

notifications

- id
- user_id
- title
- message
- type
- is_read
- created_at

## Actions

- Marquer comme lu
- Supprimer notification
- Tout marquer comme lu
