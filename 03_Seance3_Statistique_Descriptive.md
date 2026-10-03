---
title: Séance 3 - Statistique descriptive univariée
nav_order: 5
---

# Séance 3 - Statistique descriptive univariée

Cette troisième séance est consacrée à l'**analyse statistique des données géographiques**.

Après avoir appris à identifier la nature, la source et les caractéristiques des données lors de la séance précédente, nous allons maintenant chercher à **décrire et résumer une série de données** à l'aide de quelques indicateurs statistiques.

Nous utiliserons notamment **Excel** pour calculer ces indicateurs et apprendre à interpréter les résultats obtenus.

> **Question centrale de la séance :** comment résumer un grand nombre de valeurs afin de mieux comprendre les différences entre les territoires ?

---

## 🎯 Objectifs de la séance

À la fin de cette séance, vous devrez être capable de :

- comprendre le principe de la **statistique descriptive univariée** ;
- distinguer **effectif** et **fréquence** ;
- calculer et interpréter la **moyenne, la médiane et le mode** ;
- mesurer la dispersion d'une série à l'aide de l'**étendue, la variance et l'écart-type** ;
- calculer et interpréter un **coefficient de variation** ;
- observer la **distribution statistique** d'une variable ;
- utiliser les principales fonctions statistiques d'**Excel** ;
- comprendre pourquoi l'analyse statistique constitue une étape importante avant la cartographie.

---

# 1. Pourquoi utiliser la statistique descriptive ?

Un jeu de données géographiques peut contenir plusieurs dizaines, centaines ou milliers de valeurs.

Il devient alors difficile de comprendre sa structure simplement en observant un tableau.

La **statistique descriptive** permet de résumer les données à l'aide de quelques indicateurs.

Elle permet notamment de répondre à plusieurs questions :

- Quelle est la valeur moyenne ?
- Quelle est la valeur centrale ?
- Quelles valeurs apparaissent le plus souvent ?
- Les valeurs sont-elles proches les unes des autres ou très dispersées ?
- Existe-t-il des valeurs particulièrement faibles ou élevées ?

Lorsqu'on étudie **une seule variable à la fois**, on parle de **statistique descriptive univariée**.

### Exemple

On peut étudier :

- la population des communes d'un département ;
- le taux de chômage des régions françaises ;
- le revenu médian des communes ;
- la superficie des départements.

Dans chaque cas, on observe **une variable** sur plusieurs individus statistiques.

---

# 2. Effectifs et fréquences

Une première manière de décrire les données consiste à compter le nombre d'observations correspondant à une valeur ou à une catégorie.

## 2.1. L'effectif

L'**effectif** correspond au nombre d'individus statistiques présentant une valeur ou appartenant à une catégorie donnée.

### Exemple

Si **8 communes sur 20** appartiennent à la catégorie « espace rural » :

**Effectif = 8 communes**

## 2.2. La fréquence

La **fréquence** correspond à la part que représente cet effectif dans l'ensemble des observations.

Elle peut être exprimée sous forme de proportion ou de pourcentage.

Dans notre exemple :

**Fréquence = 8 / 20 = 0,4 = 40 %**

Cela signifie que **40 % des communes étudiées** appartiennent à la catégorie « espace rural ».

> **Attention :** un effectif indique un **nombre**, tandis qu'une fréquence indique une **part dans un ensemble**.

Cette distinction sera particulièrement importante lorsque nous comparerons des territoires de tailles différentes.

---

# 3. Les mesures de tendance centrale

Les mesures de tendance centrale permettent de résumer une série de données à l'aide d'une valeur représentative.

Les trois principales sont :

- la **moyenne** ;
- la **médiane** ;
- le **mode**.

## 3.1. La moyenne

La **moyenne** correspond à la somme de toutes les valeurs divisée par le nombre d'observations.

### Exemple

Pour trois communes ayant respectivement :

**2 000 – 4 000 – 6 000 habitants**

la moyenne est :

**(2 000 + 4 000 + 6 000) / 3 = 4 000 habitants**

La moyenne est très utilisée, mais elle est **sensible aux valeurs extrêmes**.

Une valeur exceptionnellement élevée ou faible peut donc fortement modifier le résultat.

## 3.2. La médiane

La **médiane** est la valeur qui partage une série ordonnée en deux groupes de même effectif.

Cela signifie qu'environ :

- 50 % des observations se trouvent en dessous ;
- 50 % se trouvent au-dessus.

Contrairement à la moyenne, la médiane est **peu sensible aux valeurs extrêmes**.

## 3.3. Le mode

Le **mode** correspond à la valeur ou à la catégorie qui apparaît le plus souvent dans une série.

### Exemple

Dans la série :

**2 – 3 – 3 – 4 – 5**

le mode est **3**, car cette valeur apparaît deux fois.

Le mode peut être utilisé avec des données **qualitatives ou quantitatives**.

---

## 💡 Exemple : moyenne, médiane et valeur extrême

Prenons la population de 7 communes, exprimée en milliers d'habitants :

**2 – 3 – 3 – 4 – 5 – 6 – 40**

On obtient :

| Indicateur | Résultat |
| --- | ---: |
| **Moyenne** | 9 000 habitants |
| **Médiane** | 4 000 habitants |
| **Mode** | 3 000 habitants |

Pourquoi la moyenne est-elle beaucoup plus élevée que la médiane ?

La commune de **40 000 habitants** constitue une valeur très élevée par rapport aux autres communes.

Elle tire donc fortement la moyenne vers le haut, alors qu'elle influence beaucoup moins la médiane.

> **Il ne faut donc pas utiliser uniquement la moyenne pour décrire une série statistique.**

---

# 4. Les mesures de dispersion

Connaître la moyenne ou la médiane ne suffit pas toujours.

Deux séries peuvent avoir une moyenne similaire tout en présentant des répartitions très différentes.

Il faut donc également déterminer si les observations sont **proches les unes des autres ou très dispersées**.

## 4.1. L'étendue

L'**étendue** correspond à la différence entre la valeur maximale et la valeur minimale.

**Étendue = Maximum − Minimum**

Dans notre exemple :

**40 − 2 = 38**

L'étendue donne une première indication de la dispersion, mais elle est très sensible aux valeurs extrêmes.

## 4.2. La variance

La **variance** mesure la dispersion des observations autour de la moyenne.

Plus la variance est élevée, plus les valeurs sont éloignées de la moyenne.

Son interprétation directe est cependant peu intuitive, car elle est exprimée dans l'unité de la variable **au carré**.

## 4.3. L'écart-type

L'**écart-type** est calculé à partir de la variance.

Il indique à quel point les observations sont dispersées autour de la moyenne.

- **écart-type faible** → valeurs relativement proches de la moyenne ;
- **écart-type élevé** → valeurs davantage dispersées.

Son principal avantage est qu'il s'exprime dans la **même unité que la variable étudiée**.

## 4.4. Le coefficient de variation

Le **coefficient de variation** rapporte l'écart-type à la moyenne :

**Coefficient de variation = (écart-type / moyenne) × 100**

Il est exprimé en pourcentage.

Il permet d'évaluer la **dispersion relative** d'une série et peut être utile pour comparer des séries dont les moyennes ou les unités sont différentes.

Plus le coefficient de variation est élevé, plus les données sont dispersées relativement à leur moyenne.

---

# 5. Calculer les indicateurs sous Excel

Excel permet de calculer rapidement les principaux indicateurs étudiés pendant cette séance.

| Indicateur | Fonction Excel |
| --- | --- |
| Effectif | `=NB(plage)` |
| Minimum | `=MIN(plage)` |
| Maximum | `=MAX(plage)` |
| Étendue | `=MAX(plage)-MIN(plage)` |
| Moyenne | `=MOYENNE(plage)` |
| Médiane | `=MEDIANE(plage)` |
| Variance | `=VAR.P(plage)` |
| Écart-type | `=ECARTYPE.P(plage)` |
| Coefficient de variation | `=ECARTYPE.P(plage)/MOYENNE(plage)*100` |

L'objectif n'est pas uniquement de savoir utiliser ces fonctions.

Il faut surtout être capable de **comprendre et d'interpréter les résultats obtenus**.

---

# 6. La distribution statistique

Les indicateurs précédents permettent de résumer une série statistique.

Cependant, ils ne suffisent pas toujours à comprendre **comment les valeurs sont réparties dans l'ensemble de la série**.

La **distribution statistique** décrit la manière dont les valeurs d'une variable se répartissent entre les observations.

Pour une variable quantitative, cette distribution peut notamment être représentée à l'aide d'un **histogramme**.

Les valeurs sont alors regroupées en classes et l'histogramme permet d'observer le nombre ou la fréquence des observations appartenant à chaque classe.

L'observation de la distribution permet notamment de repérer :

- une concentration des valeurs autour de certaines valeurs ;
- une distribution plus ou moins symétrique ou dissymétrique ;
- une dispersion importante ou faible ;
- la présence éventuelle de valeurs extrêmes.

## 6.1. Quelques formes de distribution

Une distribution peut notamment être :

- **symétrique** ;
- **étirée à droite** ;
- **étirée à gauche** ;
- **bimodale**, lorsqu'elle présente deux concentrations principales.

La comparaison entre la **moyenne, la médiane et le mode** peut aider à interpréter la forme d'une distribution.

## 6.2. Le rôle des classes

La forme observée dans un histogramme dépend également du **nombre de classes** et de leur **amplitude**.

Un nombre trop faible de classes peut simplifier fortement la distribution et masquer certaines différences.

À l'inverse, un nombre trop élevé de classes peut rendre sa lecture plus difficile.

> Le choix des classes cherche donc un équilibre entre **simplification de l'information** et **conservation de la structure des données**.

Cette question du regroupement des valeurs en classes sera approfondie plus tard dans le cours avec la **discrétisation**.

---

# 7. Pourquoi ces indicateurs sont-ils utiles en cartographie ?

Ces calculs statistiques ne servent pas uniquement à décrire les données.

Ils permettent également de **préparer leur représentation cartographique**.

Avant de construire une carte, il est important de connaître :

- la moyenne et la médiane ;
- la dispersion des valeurs ;
- la forme de leur distribution ;
- la présence éventuelle de valeurs extrêmes.

Il est également important de distinguer les **effectifs bruts** des **valeurs relatives**, comme les proportions ou les pourcentages.

Un effectif indique un **volume**, tandis qu'une proportion indique le **poids relatif d'un phénomène**.

Cette distinction est essentielle lorsque l'on souhaite comparer des territoires de tailles différentes.

### Exemple

Deux territoires peuvent avoir le même nombre de personnes appartenant à une catégorie, mais des populations totales très différentes.

Comparer uniquement les effectifs peut alors donner une vision différente de celle obtenue avec les proportions.

> **Question à toujours se poser : les conclusions sont-elles les mêmes lorsque l'on raisonne en effectifs et en proportions ? Pourquoi ?**

L'analyse statistique permet enfin de réfléchir à la manière de **regrouper les valeurs en classes** pour les représenter sur une carte.

Cette opération, appelée **discrétisation**, sera étudiée plus précisément lors de la séance 6.

On peut donc retenir la logique suivante :

**Données brutes → analyse statistique → compréhension de la distribution → préparation de la représentation cartographique**

---

# ✅ À retenir

À l'issue de cette séance, retenez principalement que :

1. La **statistique descriptive univariée** permet de décrire et de résumer une variable à l'aide de quelques indicateurs.

2. **Effectif et fréquence** ne donnent pas la même information : l'effectif mesure un nombre, tandis que la fréquence mesure une part dans un ensemble.

3. **Moyenne, médiane et mode** sont des indicateurs de tendance centrale complémentaires.

4. La moyenne est davantage influencée par les **valeurs extrêmes** que la médiane.

5. **Étendue, variance et écart-type** permettent d'évaluer la dispersion des observations.

6. Le **coefficient de variation** permet d'évaluer la dispersion relativement à la moyenne.

7. L'**histogramme** permet d'observer la forme de la distribution d'une variable.

8. L'analyse statistique permet de **mieux comprendre les données avant de les cartographier**.

---

# ✏️ TD / Activité pratique

## Analyse statistique de données sociodémographiques sous Excel

À partir du jeu de données sociodémographiques utilisé depuis la séance 2, vous réaliserez une première analyse statistique sous Excel.

Vous devrez notamment :

1. identifier l'**unité statistique**, les variables étudiées et leurs unités de mesure ;
2. calculer des **effectifs et des proportions** ;
3. comparer les résultats obtenus en **effectifs bruts** et en **pourcentages** ;
4. calculer le **minimum, le maximum et l'étendue** ;
5. calculer la **moyenne et la médiane** ;
6. calculer l'**écart-type et le coefficient de variation** ;
7. construire et observer un **histogramme** ;
8. interpréter les résultats obtenus.

### Questions d'interprétation

À partir de vos résultats, demandez-vous notamment :

- La moyenne et la médiane sont-elles proches ?
- Les données sont-elles fortement dispersées ?
- Observe-t-on des valeurs particulièrement élevées ou faibles ?
- Quelle est la forme générale de la distribution ?
- Les conclusions sont-elles les mêmes lorsque l'on raisonne en **effectifs** et en **proportions** ?
- Pourquoi les proportions peuvent-elles être plus pertinentes pour comparer certains territoires ?

### Objectif du TD

L'objectif n'est pas seulement de savoir utiliser les fonctions d'Excel.

Il s'agit surtout de comprendre **ce que les résultats statistiques nous apprennent sur les territoires étudiés** et pourquoi ces traitements sont nécessaires avant de réaliser une carte.

---

# 📄 Support de cours

Le support de la séance est disponible au format PDF :

👉 [**Télécharger le support de la séance 3 (PDF)**](Xdocuments/Seance3_Statistique_descriptive.pdf)

Ce document correspond à la partie **« Séance 3 - Statistique descriptive univariée »**.

---

# ✏️ Données et énoncé

### TD3 - Statistique descriptive sous Excel

Le TD consiste à analyser un jeu de données sociodémographiques et à calculer les principaux indicateurs étudiés pendant la séance.

👉 [**Télécharger le jeu de données du TD de la séance 3 (Excel)**](Xdocuments/Activite_pratique.xlsx)

---

# ✅ Correction du TD

La correction du TD sera disponible ici :

👉 [**Télécharger la correction du TD de la séance 3 (Excel)**](Xdocuments/Correction_activite_pratique.xlsx)

---

## ➡️ Séance suivante

La prochaine séance sera consacrée à la **structuration et au nettoyage d'une base de données géographique sous Excel**.

Après avoir appris à **décrire et analyser les données** dans cette séance, nous verrons comment préparer un tableau afin qu'il puisse être correctement utilisé pour la cartographie.

Vous apprendrez notamment à :

- identifier et conserver correctement les **codes géographiques** ;
- comprendre le principe d'une **clé de jointure** entre une table de données et un fond de carte ;
- repérer les **valeurs manquantes** et les **doublons** ;
- vérifier la cohérence des **unités et des formats** ;
- respecter la règle **« une ligne = un individu statistique ; une colonne = une variable »** ;
- préparer et exporter un fichier au format **CSV** en vue de son utilisation dans Magrit.

👉 [**Continuer vers la séance 4 - Structurer et nettoyer une base de données géographique sous Excel**](04_Seance4_Structurer_nettoyer_donnees.html)
