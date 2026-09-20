---
title: Séance 5 - La sémiologie graphique
nav_order: 7
---

# Séance 5 - La sémiologie graphique

**Thème :** choisir une représentation visuelle adaptée à la nature des données

## Objectifs

- Comprendre les principes de base de la sémiologie graphique
- Choisir une représentation visuelle adaptée à la nature des données

## Qu'est-ce que la sémiologie graphique ?

Une carte ne consiste pas à placer des données sur un fond de carte : il faut choisir **comment les représenter visuellement**. En 1967, **Jacques Bertin** publie *Sémiologie graphique*. Principe essentiel : **la manière de représenter une donnée doit être adaptée à sa nature.**

- Population des communes → le lecteur doit percevoir « plus ou moins d'habitants ».
- Occupation du sol → le lecteur doit surtout distinguer des catégories, sans ordre artificiel.

Une représentation mal choisie rend la carte difficile à lire ou conduit à une mauvaise interprétation, même avec des données correctes.

## Les éléments essentiels d'une carte

| Élément | Rôle |
| ------- | ---- |
| **Titre** | Quoi ? (phénomène), Où ? (territoire), Quand ? (période). Court, précis, informatif. *Ex. : Taux de chômage par département en France en 2025* |
| **Fond de carte** | Support géographique : localise les données |
| **Légende** | Explique les symboles et couleurs (plus clair → taux faible ; grand cercle → forte population) |
| **Échelle** | Rapport entre distances sur la carte et distances réelles |
| **Orientation** | Flèche du nord, si utile (pas nécessaire sur toutes les cartes) |
| **Source** | Origine des données. *Ex. : INSEE, Recensement de la population, 2023* |
| **Auteur et date** | Traçabilité de la production cartographique |

## Les variables visuelles

Une variable visuelle est une caractéristique graphique que l'on peut faire varier pour transmettre une information.

| Variable | Principe | Convient à |
| -------- | -------- | ---------- |
| **Taille** | Varier les dimensions d'un symbole (petit → petite quantité) | Quantités, effectifs (figurés proportionnels : carré, cercle) |
| **Valeur** | Variation du clair au foncé | Données ordonnées, données quantitatives en classes (taux de chômage) |
| **Couleur (teinte)** | Différentes couleurs | Catégories, données qualitatives nominales |
| **Forme** | Différentes formes (● école, ■ hôpital, ▲ gare) | Distinguer des types d'objets sans hiérarchie |
| **Orientation** | Direction d'un figuré ou d'un motif (hachures) | Distinguer des catégories ; peu utilisée seule aujourd'hui |
| **Grain** | Finesse ou taille du même motif (trame plus fine ou plus grossière) | Historiquement pour cartes imprimées |
| **Texture** | Nature du motif (points, hachures, croisillons, quadrillage) | Différencier des espaces ou catégories |

> **Grain** = le motif reste le même, sa finesse ou sa taille varie. **Texture** = on change la nature du motif.
>
> **Teinte ≠ valeur** : utiliser différentes couleurs n'a pas le même sens qu'une progression du clair au foncé.

## Les propriétés perceptives

- **Associative** : représenter des éléments différents sans donner plus d'importance à l'un qu'à l'autre (communes, types d'équipements, langues, religions).
- **Sélective** : repérer rapidement une catégorie parmi d'autres (zones industrielles en rouge dans une carte d'occupation du sol).
- **Ordonnée** : percevoir immédiatement une progression faible → moyen → élevé. La **valeur** (clair → foncé) a cette propriété (population, densité, altitude, revenu).
- **Quantitative** : percevoir des différences de quantité ou des rapports de grandeur. La **taille** y est adaptée : un symbole deux fois plus important traduit une quantité deux fois plus importante (règle de proportionnalité adaptée).

## Comment choisir une variable visuelle ?

| Nature de la donnée | Variable visuelle | Exemple |
| ------------------- | ----------------- | ------- |
| Qualitative nominale | Teinte ou forme | Type d'équipement, occupation du sol |
| Qualitative ordinale | Valeur (progression ordonnée) | Risque faible / moyen / élevé |
| Quantitative relative, en classes | Valeur (clair → foncé) | Taux de chômage, densité, part des personnes âgées |
| Quantitative absolue (effectif, stock) | Taille (symboles proportionnels) | Nombre d'habitants, d'emplois |

**nature de la donnée → choix de la variable visuelle → représentation cartographique**

## Erreurs fréquentes

- Plusieurs teintes sans ordre pour un taux → la progression n'est pas perceptible.
- Dégradé clair-foncé pour des catégories sans ordre → hiérarchie artificielle.
- Symboles de même taille pour des quantités très différentes → différences invisibles.
- Multiplier inutilement couleurs, symboles et informations → carte illisible.

**Question à se poser :** quelle différence le lecteur doit-il percevoir — une différence de catégorie, un ordre ou une différence de quantité ?

## À retenir

1. La sémiologie graphique organise la représentation visuelle pour rendre la carte lisible.
2. Une carte comporte : titre, fond de carte, légende, échelle, orientation si nécessaire, source, auteur.
3. Les variables visuelles n'ont pas toutes les mêmes propriétés (catégories, ordre, quantités).
4. Le choix d'une variable visuelle doit être cohérent avec la nature de la donnée.
5. Règle simple : **catégories → teinte ou forme ; ordre / valeurs relatives → valeur (clair → foncé) ; quantités absolues → taille.**

## TD / Activité pratique

À partir d'une série de variables (type de commerce, population communale, taux de pauvreté, niveau de risque, catégorie d'occupation du sol, nombre d'emplois, type d'équipement), pour chacune :

1. identifier la nature de la donnée (qualitative nominale, ordinale, quantitative) ;
2. pour les quantitatives : valeur absolue ou relative ;
3. choisir la variable visuelle la plus adaptée ;
4. proposer le type de représentation cartographique ;
5. justifier en une ou deux phrases.

On peut aussi comparer deux représentations d'une même donnée et dire laquelle est la plus pertinente, et pourquoi.

*On ne choisit pas une couleur ou un symbole parce qu'il est esthétique, mais parce qu'il correspond à la nature de l'information à transmettre.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 5*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance5/` puis ajouter le lien ici.)

## Correction

*À venir.*
