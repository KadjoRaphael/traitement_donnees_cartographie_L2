---
title: Séance 2 - Sources et types de données
---

# Séance 2 - Sources et types de données géographiques

Après avoir vu comment passer de la donnée à la carte, cette deuxième séance
s'intéresse à une question essentielle :

> **Avant d'analyser ou de cartographier une donnée, comment savoir ce qu'elle
> représente et si elle peut être utilisée ?**

L'objectif est d'apprendre à **identifier la nature d'une donnée**, à distinguer
les valeurs absolues des valeurs relatives et à rechercher des
**données géographiques fiables**.

---

## 🎯 Objectifs de la séance

À la fin de cette séance, vous devrez être capable de :

- identifier les principaux types de données utilisés en géographie ;
- distinguer une variable qualitative d'une variable quantitative ;
- distinguer une variable nominale d'une variable ordinale ;
- distinguer une variable quantitative discrète d'une variable quantitative continue ;
- reconnaître les principales échelles de mesure ;
- distinguer une **valeur absolue** d'une **valeur relative** ;
- comprendre pourquoi cette distinction est importante en cartographie ;
- identifier quelques grandes sources de données géographiques ;
- vérifier la source, la date, la définition et l'échelle géographique d'une donnée.

---

# 1. Pourquoi identifier la nature d'une donnée ?

Avant d'analyser ou de représenter une donnée, il est important de déterminer
**sa nature**.

En effet, toutes les données ne peuvent pas être traitées de la même manière.

Le type de donnée détermine notamment :

- les traitements statistiques que l'on peut effectuer ;
- les comparaisons que l'on peut réaliser ;
- la manière dont la donnée pourra ensuite être représentée sur une carte.

Par exemple, un **type d'occupation du sol** et un **nombre d'habitants**
ne représentent pas la même chose.

Dans le premier cas, nous observons une **catégorie**.

Dans le second, nous observons une **quantité**.

Cette distinction aura des conséquences sur les traitements statistiques
et sur les choix cartographiques.

---

# 2. Les différents types de données

On distingue notamment quatre grands types de données.

| Type de donnée | Définition | Exemple |
| --- | --- | --- |
| **Qualitative nominale** | Catégories qui ne peuvent pas être classées selon un ordre particulier | Type d'occupation du sol : forêt, espace agricole, espace urbain |
| **Qualitative ordinale** | Catégories pouvant être classées selon un ordre, mais dont les écarts ne sont pas mesurables | Niveau de risque : faible, moyen, élevé |
| **Quantitative discrète** | Valeurs numériques que l'on peut compter et qui prennent généralement des valeurs entières | Nombre d'écoles par commune |
| **Quantitative continue** | Mesure pouvant prendre différentes valeurs dans un intervalle | Altitude, température, distance, superficie |

---

## 2.1. Les variables qualitatives

Une variable est **qualitative** lorsqu'elle décrit une catégorie ou une qualité
plutôt qu'une quantité numérique.

### Variable qualitative nominale

Les différentes catégories **ne possèdent pas d'ordre particulier**.

Exemple :

**Type d'occupation du sol**

- forêt ;
- espace agricole ;
- espace urbain.

Il n'existe pas de hiérarchie naturelle entre ces catégories.

On ne peut pas dire que « forêt » est supérieure ou inférieure à
« espace agricole ».

### Variable qualitative ordinale

Les catégories peuvent, au contraire, être **classées selon un ordre**.

Exemple :

**Niveau de risque**

**faible → moyen → élevé**

Il existe bien une progression.

En revanche, l'écart entre « faible » et « moyen » ne peut pas être mesuré
précisément comme on mesurerait une différence de température ou de population.

---

## 2.2. Les variables quantitatives

Une variable est **quantitative** lorsqu'elle est exprimée sous forme numérique
et représente une quantité ou une mesure.

### Variable quantitative discrète

Une variable quantitative discrète correspond généralement à quelque chose
que l'on peut **compter**.

Exemples :

- nombre d'habitants ;
- nombre d'écoles ;
- nombre de logements ;
- nombre d'entreprises.

On peut par exemple observer :

**0 école, 1 école, 2 écoles, 3 écoles...**

### Variable quantitative continue

Une variable quantitative continue correspond généralement à une
**mesure** pouvant prendre différentes valeurs dans un intervalle.

Exemples :

- altitude ;
- température ;
- distance ;
- superficie.

Une température peut, par exemple, être de : **12 °C, 12,5 °C, 12,57 °C...**

---

# 3. Les échelles de mesure

Une autre manière de caractériser une variable consiste à identifier son
**échelle de mesure**.

On distingue généralement quatre échelles :

| Échelle | Caractéristique | Exemple |
| --- | --- | --- |
| **Nominale** | Catégories sans ordre | Type d'occupation du sol |
| **Ordinale** | Catégories pouvant être classées, mais écart non mesurable précisément | Risque faible / moyen / élevé |
| **D'intervalle** | Les écarts entre les valeurs sont mesurables, mais le zéro ne correspond pas à une absence de la quantité | Température en °C |
| **De rapport (ratio)** | Les écarts sont mesurables et le zéro correspond à une absence réelle de la quantité observée | Population, superficie, production |

---

## 💡 Pourquoi cette distinction est-elle importante ?

Toutes les opérations statistiques ne sont pas pertinentes pour toutes
les variables.

Par exemple, calculer la moyenne d'une variable comme :

**forêt - espace agricole - espace urbain**

n'aurait aucun sens.

Il s'agit de catégories et non de quantités numériques.

En revanche, calculer la moyenne de la **population de plusieurs communes**
peut avoir un sens statistique.

> **Avant d'effectuer un calcul, il faut donc toujours se demander quelle est
> la nature de la variable étudiée.**

---

# 4. Un exemple simple

Prenons l'observation suivante :

**Commune A → urbaine → risque élevé → 25 000 habitants**

Nous pouvons identifier plusieurs types d'informations :

| Information | Type |
| --- | --- |
| Commune A | Individu statistique |
| Urbaine | Variable qualitative nominale |
| Risque élevé | Variable qualitative ordinale |
| 25 000 habitants | Variable quantitative discrète |

L'objectif n'est donc pas seulement de savoir lire une valeur.

Il faut également comprendre **ce qu'elle représente** et **ce que l'on peut
faire avec elle**.

---

# 5. Valeur absolue ou valeur relative ?

Cette distinction est particulièrement importante en cartographie.

Une variable quantitative peut notamment exprimer une **valeur absolue**
ou une **valeur relative**.

---

## 5.1. La valeur absolue

Une valeur absolue, également appelée **effectif** ou **valeur de stock**,
mesure directement une quantité.

Exemples :

- nombre d'habitants ;
- nombre de logements ;
- nombre d'entreprises ;
- nombre d'emplois.

### Exemple

Une commune compte : **25 000 habitants**

Il s'agit directement d'une quantité de personnes.

C'est donc une **valeur absolue**.

---

## 5.2. La valeur relative

Une valeur relative met une quantité **en relation avec une autre quantité**.

Elle permet notamment de comparer des territoires ayant des populations,
des superficies ou des caractéristiques différentes.

Elle peut prendre plusieurs formes :

| Forme | Exemple |
| --- | --- |
| **Pourcentage** | Part des personnes de moins de 25 ans |
| **Taux** | Taux de chômage |
| **Densité** | Nombre d'habitants par km² |
| **Ratio** | Nombre de médecins pour 10 000 habitants |

---

## 💡 Exemple : pourquoi calculer un taux ?

Prenons deux communes :

| Commune | Nombre de chômeurs | Population active |
| --- | ---: | ---: |
| Commune A | 5 000 | 20 000 |
| Commune B | 5 000 | 100 000 |

Les deux communes comptent **5 000 personnes au chômage**.

Si l'on observe uniquement cette valeur absolue, leur situation semble
identique.

Pourtant, ces 5 000 personnes ne représentent pas la même part de la
population active.

Le calcul d'un **taux** permet donc de comparer plus correctement
les deux territoires.

> **Les valeurs relatives sont particulièrement importantes lorsque l'on
> souhaite comparer des territoires de tailles différentes.**

---

# 6. Pourquoi cette distinction est-elle importante en cartographie ?

La distinction entre valeur absolue et valeur relative a une conséquence
directe sur le choix de la représentation cartographique.

On peut retenir cette règle générale :

| Nature de la donnée | Représentation généralement adaptée |
| --- | --- |
| **Valeur absolue** | Symboles proportionnels |
| **Valeur relative** | Aplats de couleurs graduées, notamment sur une carte choroplèthe |

### Exemple

Pour représenter le **nombre d'habitants des communes**, on pourra utiliser
des cercles proportionnels :

**petite population → petit cercle**  
**grande population → grand cercle**

Pour représenter un **taux de chômage**, on pourra utiliser une progression
de couleurs :

**taux faible → couleur claire**  
**taux élevé → couleur foncée**

Ces principes seront approfondis lors de la séance consacrée à la
**sémiologie graphique**.

---

## ⚠️ Une erreur cartographique fréquente

Représenter directement des **effectifs** par des aplats de couleurs
est une erreur cartographique fréquente.

Avant de choisir une représentation, posez-vous toujours la question :

> **« Est-ce que je représente une quantité ou un rapport ? »**

Autrement dit :

**nombre d'habitants → quantité → valeur absolue**

mais :

**densité de population → habitants / km² → valeur relative**

Cette distinction sera essentielle lorsque nous commencerons à produire
des cartes.

---

# 7. Où trouver des données géographiques ?

Pour réaliser une analyse géographique, il est important d'utiliser des
**sources fiables et adaptées au sujet étudié**.

Plusieurs organismes et plateformes permettent d'accéder à des données
statistiques et géographiques.

---

## 🇫🇷 INSEE

L'**Institut national de la statistique et des études économiques (INSEE)**
produit et diffuse de nombreuses données démographiques, sociales et
économiques sur la France.

Les données sont disponibles à différentes échelles :

- commune ;
- intercommunalité ;
- département ;
- région ;
- France.

👉 [**Accéder au site de l'INSEE**](https://www.insee.fr/)

---

## 🗺️ IGN et Géoportail

L'**Institut national de l'information géographique et forestière (IGN)**
produit de nombreuses données géographiques de référence sur le territoire
français.

On peut notamment y trouver :

- des limites administratives ;
- des cartes topographiques ;
- des photographies aériennes ;
- des données d'altitude ;
- des réseaux et autres informations géographiques.

👉 [**Accéder au site de l'IGN**](https://www.ign.fr/)

👉 [**Accéder à Géoportail**](https://www.geoportail.gouv.fr/)

---

## 🌍 OpenStreetMap

**OpenStreetMap** est une base de données géographiques collaborative
et ouverte.

Elle contient de nombreux objets géographiques :

- routes ;
- bâtiments ;
- commerces ;
- équipements ;
- réseaux ;
- autres éléments du territoire.

👉 [**Accéder à OpenStreetMap**](https://www.openstreetmap.org/)

---

## 🇪🇺 Eurostat

**Eurostat** est l'office statistique de l'Union européenne.

Il diffuse notamment des données statistiques harmonisées permettant
de comparer les pays et les régions de l'Union européenne.

👉 [**Accéder à Eurostat**](https://ec.europa.eu/eurostat/)

---

## 🏛️ data.gouv.fr

**data.gouv.fr** est la plateforme française de données ouvertes.

Elle regroupe de nombreux jeux de données produits notamment par :

- les administrations ;
- les collectivités territoriales ;
- différents organismes publics.

👉 [**Accéder à data.gouv.fr**](https://www.data.gouv.fr/)

---

# 8. Vérifier la source d'une donnée

Trouver un fichier sur Internet ne signifie pas qu'il peut être utilisé
immédiatement.

Lorsqu'on utilise un jeu de données, il faut également vérifier :

- qui l'a produit ;
- ce qu'il mesure ;
- quand il a été produit ;
- à quelle échelle géographique il correspond ;
- comment les données ont été construites.

Une méthode simple consiste à retenir les cinq questions suivantes.

| Question | Ce qu'il faut vérifier |
| --- | --- |
| **Qui ?** | Qui produit les données ? |
| **Quoi ?** | Que mesure exactement la variable ? |
| **Quand ?** | De quelle année ou période datent les données ? |
| **Où ?** | À quelle échelle géographique correspondent-elles ? |
| **Comment ?** | Comment les données ont-elles été collectées ou calculées ? |

---

## 💡 Exemple : un taux de chômage

Un taux de chômage n'est pas seulement un chiffre.

Avant de l'utiliser, il faut notamment savoir :

- à quelle population il se rapporte ;
- pour quelle période il a été calculé ;
- quel organisme l'a produit ;
- quelle définition du chômage est utilisée ;
- à quelle échelle géographique il est disponible.

Cette vérification permet notamment d'éviter de comparer des données
qui ne mesurent pas exactement la même chose.

> **Une donnée doit toujours être replacée dans son contexte.**

---

# 9. Les bons réflexes avant d'utiliser un jeu de données

Avant de télécharger et d'utiliser un jeu de données, prenez l'habitude
de vérifier :

1. **La source** - Qui produit les données ?
2. **La définition** - Que mesure exactement la variable ?
3. **La date** - De quelle année ou période s'agit-il ?
4. **L'unité** - Habitants, %, km², euros, etc.
5. **L'échelle géographique** - Commune, département, région, pays...
6. **La méthode** - Comment la donnée a-t-elle été collectée ou calculée ?

Ces informations seront importantes tout au long du cours.

---

# ✅ À retenir

À l'issue de cette séance, retenez principalement que :

1. **La nature d'une donnée détermine les traitements statistiques et les
   représentations que l'on peut utiliser.**

2. Il faut distinguer :

   **variables qualitatives → nominales ou ordinales**

   **variables quantitatives → discrètes ou continues**

3. Une **valeur absolue** mesure directement une quantité.

   Exemples : nombre d'habitants, nombre de logements, nombre d'entreprises.

4. Une **valeur relative** met une quantité en relation avec une autre.

   Exemples : pourcentage, taux, densité, ratio.

5. La distinction entre valeur absolue et valeur relative est essentielle
   pour choisir une représentation cartographique adaptée.

6. Une donnée doit toujours être accompagnée de son **contexte** :

   **source + date + définition + unité + échelle géographique**

7. L'**INSEE**, l'**IGN/Géoportail**, **OpenStreetMap**, **Eurostat** et
   **data.gouv.fr** constituent des sources importantes pour rechercher
   des données géographiques.

---

# ✏️ TD / Activité pratique

## Rechercher et comprendre un jeu de données

L'objectif de ce TD est d'apprendre à rechercher un jeu de données et à
**comprendre son contenu avant de commencer à le traiter**.

### Consigne

Recherchez sur le site de l'**INSEE** ou de **data.gouv.fr** un jeu de données
disponible à l'échelle :

- communale ;

**ou**

- départementale.

👉 [**Rechercher des données sur l'INSEE**](https://www.insee.fr/)

👉 [**Rechercher des données sur data.gouv.fr**](https://www.data.gouv.fr/)

---

## Travail demandé

À partir du jeu de données choisi :

1. **Identifiez la source et l'organisme producteur.**

2. **Indiquez la date ou la période des données.**

3. **Identifiez l'échelle géographique utilisée.**

   Exemple : commune, département...

4. **Sélectionnez plusieurs variables** et déterminez si elles sont :

   - qualitatives ;
   - quantitatives.

5. Pour les variables quantitatives, précisez s'il s'agit :

   - de **valeurs absolues** ;
   - de **valeurs relatives**.

6. **Expliquez brièvement ce que mesure chaque variable.**

---

## 🎯 Objectif du TD

À ce stade du cours, il ne s'agit **pas encore de produire une carte**.

L'objectif est d'apprendre à :

**choisir → identifier → lire → comprendre**

un jeu de données avant de commencer à le traiter.

Cette étape est indispensable avant toute analyse statistique ou
cartographique.

---

# 📄 Support de cours

Le support complet du cours est disponible au format PDF :

👉 [**Télécharger le support de cours complet (PDF)**](documents/Traitement_donnees_cartographie_L2.pdf)

Pour cette séance, consultez la partie
**« Séance 2 - Sources et types de données géographiques »**.

---

## ⬅️ Séance précédente

👉 [**Retour à la séance 1 - De la donnée à la carte**](01_Seance1_Introduction.md)

---

## ➡️ Séance suivante

La prochaine séance sera consacrée à la
**statistique descriptive univariée**.

Nous apprendrons à résumer et à décrire un jeu de données à l'aide
d'indicateurs tels que :

- la moyenne ;
- la médiane ;
- le mode ;
- l'étendue ;
- la variance ;
- l'écart-type ;
- le coefficient de variation.

Ces indicateurs nous permettront de mieux comprendre la distribution
des données avant leur représentation cartographique.

👉 [**Continuer vers la séance 3 - Statistique descriptive univariée**](03_Seance3_Statistique_Descriptive.md)
