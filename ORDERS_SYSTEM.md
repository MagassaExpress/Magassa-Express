# Système de Commandes

## Objectif

Gérer toutes les commandes des acheteurs.

## Cycle de commande

1. Produit ajouté au panier
2. Paiement effectué
3. Commande confirmée
4. Préparation
5. Expédition
6. Livraison
7. Terminée

## Statuts

- En attente
- Payée
- Confirmée
- En préparation
- Expédiée
- Livrée
- Terminée
- Annulée
- Remboursée

## Informations commande

- Numéro commande
- Acheteur
- Vendeur
- Produit
- Quantité
- Prix
- Livraison
- Total

## Historique

Chaque action est enregistrée :

- Date création
- Paiement
- Expédition
- Livraison

## Annulation

Acheteur peut annuler avant expédition.

Vendeur peut refuser si déjà expédié.

## Remboursement

Conditions :

- Produit non reçu
- Produit défectueux
- Mauvais produit

## Base de données

orders

- id
- buyer_id
- seller_id
- total_amount
- status
- created_at

order_items

- id
- order_id
- product_id
- quantity
- price
