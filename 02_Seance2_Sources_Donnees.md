---
title: Séance 2 - Sources et types de données
---

# Séance 2 - Sources et types de données géographiques

**Thème :** identifier la nature d'une donnée et trouver des sources fiables

## Objectifs

- Identifier les différents types de données utilisés en géographie et comprendre leurs caractéristiques
- Savoir où trouver des données fiables

## Les différents types de données

Le type de donnée détermine les traitements statistiques possibles et, plus tard, sa représentation cartographique.

| Type | Définition | Exemple |
| ---- | ---------- | ------- |
| **Qualitative nominale** | Catégories sans ordre | Occupation du sol : forêt, espace agricole, espace urbain |
| **Qualitative ordinale** | Catégories ordonnées, écart non mesurable | Niveau de risque : faible, moyen, élevé |
| **Quantitative discrète** | Valeurs numériques comptables, généralement entières | Nombre d'écoles par commune |
| **Quantitative continue** | Mesure pouvant prendre toute valeur dans un intervalle | Altitude, température, distance, superficie |

## Échelles de mesure

| Échelle | Caractéristique | Exemple |
| ------- | --------------- | ------- |
| **Nominale** | Catégories sans ordre | Type d'occupation du sol |
| **Ordinale** | Catégories ordonnées, écart non mesurable | Risque faible / moyen / élevé |
| **D'intervalle** | Écarts mesurables, mais le zéro ne signifie pas l'absence de la quantité | Température en °C |
| **De rapport (ratio)** | Écarts mesurables et zéro = absence réelle | Population, superficie, production |

Toutes les opérations statistiques ne sont pas pertinentes pour toutes les variables : calculer la moyenne d'une variable nominale n'aurait pas de sens.

**Un exemple simple :** Commune A → urbaine → élevé → 25 000 habitants. « Urbaine » est une catégorie nominale, « élevé » une catégorie ordinale, « 25 000 habitants » une valeur quantitative discrète.

## Valeur absolue ou valeur relative ?

- **Valeur absolue** (stock, effectif) : mesure directement une quantité — nombre d'habitants, de logements, d'entreprises.
- **Valeur relative** : met une quantité en relation avec une autre — pourcentage, taux, densité (hab./km²), ratio (médecins pour 10 000 habitants). Elle permet de comparer des territoires de tailles différentes.

Deux communes ayant chacune 5 000 chômeurs n'ont pas la même situation si l'une compte 20 000 actifs et l'autre 100 000 : le **taux** permet de les comparer.

**Règle générale :** valeur absolue → symboles proportionnels ; valeur relative → aplats de couleurs graduées (carte choroplèthe).

> ⚠️ Représenter directement des effectifs par des aplats de couleurs est une erreur cartographique fréquente. Se demander toujours : « Est-ce que je représente une quantité ou un rapport ? »

## Où trouver des données géographiques ?

| Source | Contenu |
| ------ | ------- |
| **INSEE** | Données démographiques, sociales et économiques sur la France (commune, intercommunalité, département, région...) |
| **IGN et Géoportail** | Données de référence : limites administratives, cartes topographiques, photographies aériennes, altitude, réseaux |
| **OpenStreetMap** | Base collaborative et ouverte : routes, bâtiments, commerces, équipements, réseaux |
| **Eurostat** | Données statistiques harmonisées pour comparer les pays et régions de l'Union européenne |
| **data.gouv.fr** | Plateforme française de données ouvertes (administrations, collectivités, organismes publics) |

## Vérifier la source d'une donnée

- **Qui ?** Qui produit les données ?
- **Quoi ?** Que mesure exactement la variable ?
- **Quand ?** De quelle année ou période ?
- **Où ?** À quelle échelle géographique ?
- **Comment ?** Comment les données ont-elles été collectées ou calculées ?

Un taux de chômage n'est pas seulement un chiffre : il faut savoir à quelle population il se rapporte, pour quelle période et par quel organisme.

## À retenir

- La nature d'une donnée détermine les traitements statistiques et les représentations possibles.
- Distinguer qualitatif (nominal, ordinal) et quantitatif (discret, continu).
- Une valeur absolue mesure une quantité ; une valeur relative met deux quantités en relation.
- Une donnée s'accompagne toujours de son contexte : source, date, définition, unité, échelle géographique.

## TD / Activité pratique

Rechercher sur le site de l'**INSEE** ou **data.gouv.fr** un jeu de données à l'échelle communale ou départementale, puis :

1. identifier la source et l'organisme producteur ;
2. indiquer la date ou la période des données ;
3. identifier l'échelle géographique utilisée ;
4. sélectionner plusieurs variables et déterminer si elles sont qualitatives ou quantitatives ;
5. pour les variables quantitatives, préciser s'il s'agit de valeurs absolues ou relatives ;
6. expliquer brièvement ce que mesure chaque variable.

*L'objectif n'est pas encore de produire une carte, mais d'apprendre à choisir, lire et comprendre un jeu de données avant de le traiter.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 2*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance2/` puis ajouter le lien ici.)

## Correction

*À venir.*
