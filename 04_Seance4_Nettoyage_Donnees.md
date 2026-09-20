---
title: Séance 4 - Structurer et nettoyer les données
nav_order: 6
---

# Séance 4 - Structurer et nettoyer une base de données sous Excel

**Thème :** préparer un tableau de données pour son utilisation dans Magrit

## Objectifs

- Organiser, vérifier et nettoyer un tableau de données géographiques sous Excel
- Le préparer à son utilisation cartographique dans Magrit

## Pourquoi préparer les données ?

Les fichiers téléchargés (INSEE, data.gouv.fr...) contiennent souvent des lignes inutiles, des valeurs manquantes, des doublons, des formats hétérogènes ou des identifiants mal enregistrés. Ces problèmes faussent les analyses ou empêchent la cartographie.

**données brutes → vérification → nettoyage → structuration → analyse → cartographie**

## La table de données et le fond de carte

Une carte thématique nécessite :

- un **fond de carte** : les objets géographiques (communes, départements, régions...) ;
- une **table de données** : les informations statistiques associées (population, revenu, taux de chômage...).

Pour associer les deux, il faut un **identifiant commun**, la **clé de jointure**.

| Code commune | Commune | Population |
| ------------ | ------- | ---------- |
| 92050 | Nanterre | - |
| 95127 | Cergy | - |

Magrit utilise ce code commun pour associer la population du tableau à la bonne commune : c'est la **jointure**.

**Fond de carte + identifiant commun + table de données → jointure → données cartographiables**

## Les identifiants géographiques

Le code géographique officiel (« code INSEE ») identifie les communes ; il existe aussi des codes pour les départements, régions et EPCI. On préfère un **code** au nom, car les noms varient (accents, traits d'union, changements). Toujours vérifier que les deux fichiers utilisent **le même identifiant et le même millésime géographique**.

> ⚠️ **Zéros initiaux :** si Excel lit `01053` comme un nombre, il affiche `1053`. Pour une jointure, `01053` et `1053` sont différents et la jointure échoue. Conserver les colonnes de codes **au format texte**.

Un code géographique est un **identifiant**, pas une quantité : même composé de chiffres, il n'est pas une variable numérique.

## Nettoyer une base de données

- **Valeurs manquantes** : information non renseignée. **Une valeur manquante n'est pas égale à 0** (0 = valeur connue et nulle). Identifier, comprendre pourquoi, puis conserver comme manquante, exclure de certains calculs ou rechercher dans la source.
- **Doublons** : un même individu présent plusieurs fois. Ils faussent les calculs et les jointures.
- **Cohérence des unités** : ne pas mélanger 0,25 / 25 % / 25 pour une même proportion, ni habitants et milliers d'habitants.
- **Cohérence des formats** : nombres, pourcentages, dates, séparateurs décimaux, codes géographiques, caractères accentués.

## Bien structurer un tableau

**Une ligne = un individu statistique ; une colonne = une variable.**

À éviter : cellules fusionnées, plusieurs lignes de titres, lignes ou colonnes vides au milieu, plusieurs informations dans une cellule, noms de variables obscurs.

Noms de colonnes courts, explicites et cohérents :

```
code_commune | nom_commune | population | superficie | taux_chomage
```

## Préparer le fichier pour Magrit

Export au format **CSV** (Comma-Separated Values). Vérification finale :

- [ ] la première ligne contient les noms des variables
- [ ] pas de cellules fusionnées
- [ ] codes géographiques correctement conservés
- [ ] pas de doublons inattendus
- [ ] valeurs manquantes identifiées
- [ ] unités et formats cohérents

## À retenir

1. Avant de cartographier : vérifier, nettoyer, structurer.
2. Une jointure associe une table à un fond de carte grâce à un identifiant commun.
3. Un code géographique est un identifiant : le garder en texte pour préserver les zéros initiaux.
4. Une valeur manquante n'est pas égale à zéro.
5. Une ligne = un individu ; une colonne = une variable.
6. Une fois nettoyé, exporter en CSV pour Magrit.

## TD / Activité pratique

À partir du jeu de données utilisé depuis la séance 2 :

1. identifier l'unité géographique du tableau ;
2. repérer la colonne servant d'identifiant géographique ;
3. vérifier le format des codes et préserver les zéros initiaux ;
4. rechercher et traiter les doublons ;
5. repérer les valeurs manquantes (absence de donnée ≠ zéro) ;
6. vérifier la cohérence des unités et des formats ;
7. réorganiser selon « une ligne = un individu ; une colonne = une variable » ;
8. enregistrer une version propre et l'exporter en **CSV**.

*À la fin du TD : un fichier propre, structuré, prêt à être associé à un fond de carte dans Magrit.*

## Support de cours

[Support de cours complet (PDF)](documents/Traitement_donnees_cartographie_L2.pdf) — voir la section *Séance 4*.

## Données et énoncé

*À venir.* (Déposer les fichiers dans `documents/seance4/` puis ajouter le lien ici.)

## Correction

*À venir.*
