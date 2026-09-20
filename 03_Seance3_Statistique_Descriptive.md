---
title: Séance 3 - Statistique descriptive univariée
---

# Séance 3 - Statistique descriptive univariée

**Thème :** décrire et résumer une série de données géographiques, calculs sous Excel

## Objectifs

- Décrire et résumer une série de données à l'aide des principaux indicateurs de statistique descriptive
- Savoir les calculer sous Excel

## Pourquoi utiliser la statistique descriptive ?

Un jeu de données peut contenir des centaines ou des milliers de valeurs. La statistique descriptive les résume avec quelques indicateurs et répond à des questions simples : valeur moyenne ? valeur centrale ? valeurs les plus fréquentes ? valeurs proches ou très dispersées ? valeurs particulièrement faibles ou élevées ?

Lorsqu'on étudie **une seule variable à la fois**, on parle de statistique descriptive **univariée** (population des communes d'un département, taux de chômage des régions, revenu médian des communes...).

## Effectifs et fréquences

- **Effectif** : nombre d'individus présentant une valeur ou appartenant à une catégorie (8 communes sur 20 en « espace rural » → effectif = 8).
- **Fréquence** : part de cet effectif dans l'ensemble (8 / 20 = 0,4 = 40 %).

Sous Excel : fonctions de comptage ou tableau croisé dynamique.

## Mesures de tendance centrale

- **Moyenne** : somme des valeurs / nombre d'observations. Sensible aux valeurs extrêmes.
  *Ex. : (2 000 + 4 000 + 6 000) / 3 = 4 000 habitants.*
- **Médiane** : valeur qui partage la série ordonnée en deux groupes de même effectif (50 % en dessous, 50 % au-dessus). Peu sensible aux valeurs extrêmes.
- **Mode** : valeur ou catégorie la plus fréquente (utilisable en qualitatif comme en quantitatif). *Ex. : dans 2 – 3 – 3 – 4 – 5, le mode est 3.*

### Exemple : moyenne, médiane et valeur extrême

Population de 7 communes (en milliers d'habitants) : **2 – 3 – 3 – 4 – 5 – 6 – 40**

| Indicateur | Calcul | Résultat |
| ---------- | ------ | -------- |
| Moyenne | (2 + 3 + 3 + 4 + 5 + 6 + 40) / 7 | 9 000 habitants |
| Médiane | valeur centrale de la série ordonnée | 4 000 habitants |
| Mode | valeur qui apparaît deux fois | 3 000 habitants |

La commune de 40 000 habitants tire la moyenne vers le haut mais influence peu la médiane : **il ne faut pas décrire une série avec la seule moyenne.**

## Mesures de dispersion

- **Étendue** : maximum − minimum (ici 40 − 2 = 38). Très sensible aux valeurs extrêmes.
- **Variance** : dispersion autour de la moyenne ; exprimée dans l'unité au carré, donc peu intuitive.
- **Écart-type** : racine de la variance, dans la même unité que la variable. Faible = valeurs proches de la moyenne ; élevé = valeurs dispersées.
- **Coefficient de variation** = (écart-type / moyenne) × 100, en %. Dispersion relative, utile pour comparer des séries d'unités ou de moyennes différentes.

## Fonctions Excel

| Indicateur | Fonction Excel |
| ---------- | -------------- |
| Effectif | `=NB(plage)` |
| Minimum | `=MIN(plage)` |
| Maximum | `=MAX(plage)` |
| Étendue | `=MAX(plage)-MIN(plage)` |
| Moyenne | `=MOYENNE(plage)` |
| Médiane | `=MEDIANE(plage)` |
| Écart-type | `=ECARTYPE.P(plage)` |
| Coefficient de variation | `=ECARTYPE.P(plage)/MOYENNE(plage)*100` |

## Pourquoi ces indicateurs sont-ils utiles en cartographie ?

Avant de cartographier, il faut connaître la distribution des valeurs : moyenne, médiane, dispersion, valeurs extrêmes. Ces informations guident le choix d'une méthode de **discrétisation** (voir [séance 6](06_Seance6_Discretisation.html)).

## À retenir

1. La statistique descriptive univariée décrit et résume une variable avec quelques indicateurs.
2. Effectif et fréquence donnent l'importance d'une valeur ou d'une catégorie.
3. Moyenne, médiane et mode ne donnent pas la même information ; la moyenne est plus sensible aux valeurs extrêmes.
4. Étendue, variance et écart-type mesurent la dispersion ; le coefficient de variation la mesure relativement à la moyenne.
5. L'analyse statistique prépare la cartographie et la discrétisation.

## TD / Activité pratique

À partir du jeu de données sociodémographiques de la séance 2, réaliser une première analyse statistique sous Excel :

1. sélectionner une ou plusieurs variables quantitatives ; identifier l'unité statistique, la variable et son unité de mesure ;
2. calculer : **effectif → minimum → maximum → étendue → moyenne → médiane → écart-type → coefficient de variation** ;
3. interpréter : moyenne et médiane sont-elles proches ? Les données sont-elles fortement dispersées ? Observe-t-on des valeurs particulièrement élevées ou faibles ?

*L'objectif est de comprendre ce que les résultats nous apprennent sur les territoires étudiés, pas seulement d'utiliser les fonctions.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 3*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance3/` puis ajouter le lien ici.)

## Correction

*À venir.*
