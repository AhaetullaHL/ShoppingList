# ShoppingList

 Application de liste de courses en `JavaScript`.

## Fonctionnalités et contraintes imposées

- pouvoir ajouter un produit ayant un prix unitaire à la liste (c.a.d "acheter" un produit)

- pouvoir voir la liste de tous les produits achetés

- pouvoir obtenir le prix total de la liste (c.a.d pouvoir "payer" )

- un même produit peut être acheté en plusieurs exemplaires

- le nom du produit est libre, c'est l'utilisateur qui choisit quoi acheter (c.a.d qu'il écrit ce qu'il veut acheter dans un input, il ne choisit pas dans une liste de produits disponibles)

- *optionnel: pouvoir supprimer un produit de la liste et/ou changer sa quantité*

## Organisation des Fonctionnalités

- Ajouter un Produit (créer, éditer, supprimer)
  
  - Entrer le nom du produit (**unique**)
  - Préciser la quantité
  - Associer un prix unitaire 

- Afficher la liste des produits achetés

  - Possibilité d'éditer (quantité, prix) ou supprimer un produit 
  - Afficher le montant total de la liste
  - Bouton d'achat ( "Payer")