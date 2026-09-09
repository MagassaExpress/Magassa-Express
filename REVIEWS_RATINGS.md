# Avis et Notes

## Objectif

Permettre aux acheteurs de noter les vendeurs et les produits.

## Notes

- 1 étoile
- 2 étoiles
- 3 étoiles
- 4 étoiles
- 5 étoiles

## Avis vendeur

Acheteur peut noter :

- Rapidité
- Qualité produit
- Communication
- Livraison

## Avis produit

- Note globale
- Commentaire
- Photos

## Calcul

Moyenne automatique :

Total étoiles / Nombre avis

Exemple :

50 étoiles / 10 avis = 5.0

## Base de données

reviews

- id
- user_id
- seller_id
- product_id
- rating
- comment
- created_at

## Sécurité

- Uniquement après achat confirmé
- Un avis par commande
- Anti-spam

## Affichage

Profil vendeur :

⭐⭐⭐⭐⭐ 4.8/5

124 avis

Produit :

⭐⭐⭐⭐⭐
Excellent produit
