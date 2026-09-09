# Panier d'Achat

## Objectif

Permettre aux utilisateurs d'ajouter plusieurs produits avant paiement.

## Fonctionnalités

### Ajouter au panier

- Ajouter produit
- Choisir quantité
- Modifier quantité
- Supprimer produit

### Calcul automatique

Prix total :

Somme de tous les produits

Exemple :

Produit A = 5000 FCFA
Produit B = 10000 FCFA

Total = 15000 FCFA

### Livraison

Afficher :

- Frais livraison
- Total général

### Validation

Bouton :

Passer la commande

## Base de données

carts

- id
- user_id
- created_at

cart_items

- id
- cart_id
- product_id
- quantity

## Sécurité

- Vérifier stock disponible
- Bloquer quantité excessive

## Interface

Panier

Produit
Quantité
Prix

Total Produits

Livraison

Total Général

[Commander]
