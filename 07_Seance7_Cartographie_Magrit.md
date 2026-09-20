---
title: Séance 7 - Cartographie thématique sous Magrit
---

# Séance 7 - Cartographie thématique sous Magrit

**Thème :** choisir, réaliser et finaliser une carte thématique (choroplèthes, symboles proportionnels, flux, anamorphoses)

## Objectifs

- Choisir, réaliser et finaliser une carte thématique sous Magrit en fonction de la nature des données
- Respecter les règles de lisibilité, de hiérarchisation visuelle et de communication cartographique

## La carte choroplèthe

Elle représente un phénomène par une **progression de couleurs**, généralement du clair au foncé ; chaque territoire reçoit la couleur de la classe de sa valeur. Elle est adaptée aux **valeurs relatives** : taux de chômage, densité, part des personnes âgées, revenu moyen ou médian, nombre de médecins pour 10 000 habitants. Elle nécessite une méthode de discrétisation et un nombre de classes ([séance 6](06_Seance6_Discretisation.html)).

**Valeur relative → carte choroplèthe.**

### Ses limites

- **Effet de surface** : les grands territoires attirent davantage le regard.
- **Effet du découpage** : le phénomène apparaît différemment selon l'échelle (communes, départements, régions).
- **Homogénéité artificielle** : une seule couleur pour toute une unité, malgré les différences internes.

## Les symboles proportionnels

Pour une **valeur absolue** (habitants, emplois, établissements, étudiants), un symbole (généralement un cercle) est placé sur chaque territoire ; sa **surface** varie proportionnellement à la quantité (variable visuelle *taille*).

**Valeur absolue → symboles proportionnels.** C'est la **surface** du symbole, et non son rayon, qui est proportionnelle à la valeur ; Magrit effectue ce calcul automatiquement.

## Choroplèthe ou symboles proportionnels ?

| Donnée | Représentation |
| ------ | -------------- |
| Population totale | Symboles proportionnels |
| Densité de population | Choroplèthe |
| Nombre de chômeurs | Symboles proportionnels |
| Taux de chômage | Choroplèthe |
| Nombre de personnes de plus de 65 ans | Symboles proportionnels |
| Part des personnes de plus de 65 ans | Choroplèthe |

## Les cartes de flux

Elles représentent des déplacements ou échanges (domicile-travail, migrations, échanges commerciaux, marchandises, voyageurs). Chaque flux a une **origine**, une **destination** et une **intensité**. Épaisseur du trait : fin → flux faible, épais → flux important ; la direction peut être indiquée par une flèche.

Organisation des données : **Origine → Destination → Valeur du flux**

| Origine | Destination | Valeur du flux (déplacements) |
| ------- | ----------- | ----------------------------- |
| Commune 1 | Commune 3 | 4 800 |
| Commune 2 | Commune 3 | 2 100 |
| Commune 3 | Commune 4 | 3 600 |

*(données fictives)*

## Les anamorphoses cartographiques

Une anamorphose (ou cartogramme) **déforme la taille des territoires en fonction d'une donnée statistique** : dans une anamorphose de la population, les territoires très peuplés deviennent plus grands. La superficie représentée traduit l'importance de la variable et non la superficie réelle.

- **Avantage** : met en évidence l'importance des territoires selon la variable ; réduit le poids visuel des grandes superficies.
- **Limite** : la déformation peut rendre certains territoires plus difficiles à reconnaître.
- L'échelle est généralement peu pertinente dans une anamorphose.

## De la carte de travail à la carte finale

**préparer les données → réaliser la jointure → choisir la représentation → discrétiser si nécessaire → choisir les variables visuelles → mettre en page → vérifier → exporter**

Trois questions avant de finaliser :

1. Quelle est la nature de ma donnée ?
2. Quel type de carte est adapté ?
3. Ma représentation permet-elle de comprendre correctement le phénomène ?

## Les principaux éléments d'une carte

- **Titre** : phénomène, territoire, période. *Ex. : Taux de chômage par département en France en 2025.*
- **Légende** : signification des couleurs, classes, symboles ; **unités** (%, habitants, €/habitant...).
- **Source et date** des données. *Ex. : Source : INSEE, 2025.*
- **Auteur** : si le contexte de diffusion le nécessite.
- **Échelle et orientation** : seulement si utiles. Une échelle n'apporte rien quand on montre la répartition d'un phénomène, des taux ou des flux ; une flèche du nord est superflue quand le nord est en haut et le territoire facilement reconnaissable.

> Un élément cartographique n'est ajouté que s'il apporte une information utile au lecteur.

## Choisir les couleurs

- Variable quantitative ordonnée → palette **séquentielle** (clair → foncé).
- Point central important (moyenne, valeur de référence, seuil) → palette **divergente**.
- Catégories sans ordre → palette **qualitative / catégorielle** (teintes suffisamment différentes, sans hiérarchie).
- Veiller à la distinction des couleurs pour les personnes présentant une déficience de perception des couleurs.

## Organiser la mise en page

La carte reste l'élément principal ; titre facilement identifiable, légende proche de la carte, sources visibles sans prendre trop de place.

À éviter : titres trop longs, légendes trop complexes, trop de couleurs, textes trop petits, éléments décoratifs inutiles, espaces vides ou mise en page surchargée.

## Finaliser sous Magrit

Les outils d'habillage permettent d'ajouter titre, légende, textes, échelle, orientation et sources. Dernière vérification avant export (PDF, image...) :

- [ ] La représentation est-elle adaptée aux données ?
- [ ] Le titre est-il précis ?
- [ ] La légende permet-elle de comprendre la carte ?
- [ ] Les unités sont-elles indiquées ?
- [ ] La source est-elle présente ?
- [ ] Les couleurs sont-elles cohérentes et lisibles ?

## À retenir

1. Une carte n'est pas terminée après la représentation des données : mise en page, vérification, habillage.
2. Titre, légende et source sont essentiels ; échelle, orientation, auteur selon le contexte.
3. Couleurs adaptées à la donnée : séquentielle, divergente ou catégorielle.
4. Une bonne mise en page crée une hiérarchie visuelle claire.

## TD / Activité pratique

Réaliser et mettre en page une **carte complète sous Magrit** : vérifier la représentation choisie, améliorer les couleurs, construire une légende claire, ajouter un titre précis, les unités, la source et les éléments utiles, puis exporter dans un format adapté.

*L'objectif est de passer d'une carte de travail à une carte finale lisible, complète et prête à être intégrée dans un dossier ou un commentaire cartographique.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 7*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance7/` puis ajouter le lien ici.)

## Correction

*À venir.*
