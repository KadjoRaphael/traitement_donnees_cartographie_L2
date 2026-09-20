---
title: Séance 6 - La discrétisation
nav_order: 7
---

# Séance 6 - La discrétisation des données quantitatives

**Thème :** regrouper des valeurs en classes et comprendre l'effet de ce choix sur la lecture d'une carte

## Objectifs

- Comprendre le principe de la discrétisation
- Connaître les principales méthodes
- Comprendre comment le choix des classes influence la lecture d'une carte

## Pourquoi discrétiser ?

Pour réaliser une **carte choroplèthe**, il faut regrouper les valeurs d'une variable quantitative en un nombre limité de **classes**. La discrétisation transforme une série de valeurs en classes. *Ex. : taux de chômage de 4 % à 20 % → cinq classes : 4–7 % | 7–10 % | 10–13 % | 13–16 % | 16–20 %.* Chaque classe reçoit ensuite une valeur visuelle, généralement une teinte du clair au foncé.

**Une même série de données peut donner des cartes différentes selon la méthode de discrétisation utilisée.**

## Les principales méthodes

| Méthode | Principe | Avantage | Limite |
| ------- | -------- | -------- | ------ |
| **Amplitudes égales** | L'étendue est divisée en intervalles de même largeur | Simple, intervalles faciles à lire | Si données très inégales ou valeurs extrêmes : classes très remplies et classes presque vides |
| **Quantiles** | Classes de même effectif (100 communes, 5 classes → ~20 par classe) | Carte visuellement équilibrée | Peut séparer des territoires aux valeurs très proches |
| **Moyenne et écart-type** | Classes construites autour de la moyenne et de la dispersion | Distingue les territoires en dessous, autour ou au-dessus de la moyenne ; utile pour étudier des écarts à une situation moyenne | Suppose de s'intéresser à l'écart à la moyenne |
| **Seuils naturels (Jenks)** | Recherche automatique des ruptures de la distribution : regroupe les valeurs proches, sépare les valeurs différentes | Utile quand les données forment des groupes ou des ruptures naturelles | Seuils moins « lisibles » que des intervalles réguliers |

## Une méthode différente, une lecture différente

Il n'existe pas de méthode adaptée à toutes les situations. Deux cartes construites à partir des **mêmes données** peuvent donner une impression différente. Le cartographe doit **tester plusieurs méthodes, observer la distribution des données et justifier son choix.**

## Combien de classes ?

Trop peu de classes masquent des différences ; trop de classes rendent la carte illisible. **4 à 7 classes** constituent souvent un ordre de grandeur raisonnable, mais cela dépend des données et de l'objectif. Magrit permet de tester méthodes et nombres de classes pour en observer directement les effets.

## À retenir

1. Discrétiser, c'est regrouper des valeurs quantitatives en classes pour les cartographier.
2. Méthodes étudiées : amplitudes égales, quantiles, moyenne/écart-type, seuils naturels (Jenks).
3. La méthode et le nombre de classes peuvent modifier fortement la lecture d'une carte.
4. Pas de méthode universelle : le choix doit être adapté aux données et justifié.

## TD / Activité pratique

Sous **Magrit**, à partir d'un même jeu de données quantitatives :

1. produire plusieurs cartes en testant **au moins trois méthodes** de discrétisation, avec le **même nombre de classes** ;
2. comparer : quels territoires changent de classe ? les contrastes sont-ils plus ou moins importants ? quelle méthode semble la plus adaptée à la distribution, et pourquoi ?
3. tester ensuite différents nombres de classes et observer l'effet sur la lecture.

*Discrétiser n'est pas cliquer sur une méthode proposée par le logiciel : c'est un choix cartographique qu'il faut pouvoir expliquer et justifier.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 6*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance6/` puis ajouter le lien ici.)

## Correction

*À venir.*
