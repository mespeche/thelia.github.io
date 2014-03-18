---
layout: home
title: Moteur de recherche multicritères
sidebar: tutorials
subnav: advanced_search
lang: fr
---

<div class="page-header">
    <h1>Moteur de recherche multicritères</h1>
</div>


## Problématique

Une des fonctionnalités importante qui doit être mise à disposition des utilisateurs sur un site e-commerce est sans aucun doute un moteur de recherche. Cela permet au visiteur de votre boutique de trouver rapidement l'article qu'il recherche.
Néanmoins, il ne connait pas tout votre catalogue, par conséquent, rechercher un produit uniquement avec le nom va devenir pour lui très compliqué voir impossible.

C'est pourquoi nous allons étudier la mise en place d'un moteur de recherche beaucoup plus avancé qui va permettre à vos clients et futurs clients de trouver les produits qu'ils désirent en l'espace de quelques secondes.

Notre moteur de recherche va tout simplement s'appuyer sur des caractéristiques associées à vos produits.

## Tutoriel

### Les caractéristiques dans Thelia 2

Les caractéristiques de produit vous permettent d'associer aux éléments de votre catalogue des attributs qui vont permettre de les distinguer facilement (une marque, une couleur, une matière, etc...).

Prenons l'exemple du catalogue de Thelia qui présente toute une gamme de produits d'immobilier. Les produits sont regroupés en catégories, nous retrouvons ainsi des chaises, des tabourets, des fauteuils et des canapés.

<img src="/img/documentation/tutorials/advanced-search-engine/categories.png" class="img-responsive">

Au sein de ces rubriques, nous retrouvons un ensemble de produits, prenons par exemple la catégorie « __Chaises__ ».

<img src="/img/documentation/tutorials/advanced-search-engine/products.png" class="img-responsive">

Lorsque l'on se rend sur la vue d'édition d'un produit, par exemple la chaise « __Horatio__ », nous disposons d'un onglet « __Déclinaisons & caractéristiques__ ».

<img src="/img/documentation/tutorials/advanced-search-engine/features-tab.png" class="img-responsive">

C'est sur cette vue que nous allons pouvoir associer une caractéristique à notre produit, grâce à l'encart « __Caractéristiques du produit__ ».

<img src="/img/documentation/tutorials/advanced-search-engine/features.png" class="img-responsive">

Nous voyons ici que notre chaise « __Horatio__ » est associée à la marque « __Milan__ ». Il est bien sur possible d'associer plusieurs valeurs de caractéristique d'une même caractéristique. Par exemple nous pourrions très bien associer deux marque à ce produit...

Notre moteur de recherche multicritères va utiliser cette caractéristique « __Marque__ » mais nous allons aussi créer un attribut « __Couleur__ » afin de permettre à l'utilisateur de rechercher un produit par __marque__ et par __couleur__.

Rendons-nous donc dans l'espace de gestion des caractéristiques via l'onglet « __Configuration__ » du menu principal.