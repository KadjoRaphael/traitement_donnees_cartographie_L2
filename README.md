# Traitement des données et cartographie — Site du cours (L2)

Site pédagogique généré avec Jekyll (thème "Read the Docs"), publié sur GitHub Pages.
Même architecture que le site `stats_cartographie`.

## Publier le site (une seule fois)

1. Créer un **nouveau dépôt** public sur <https://github.com/new>
   (nom suggéré : `traitement_donnees_cartographie_L2`, sans README ni .gitignore).
2. Dans ce dossier :

```
git init
git add .
git commit -m "Premier commit du site du cours"
git branch -M main
git remote add origin https://github.com/KadjoRaphael/traitement_donnees_cartographie_L2.git
git push -u origin main
```

3. Sur GitHub : **Settings > Pages** > Source `Deploy from a branch` > Branch `main`, dossier `/ (root)` > **Save**.
4. Après 1 à 2 minutes : `https://kadjoraphael.github.io/traitement_donnees_cartographie_L2/`

## Ajouter du contenu ensuite

- Une page = un fichier `.md` à la racine (le numéro en début de nom fixe l'ordre du menu).
- Fichiers à distribuer (énoncés, données, corrigés) : les déposer dans `documents/seanceN/`
  puis ajouter le lien dans la page correspondante, par exemple :
  `[Énoncé et données (zip)](documents/seance3/TD3.zip)`
- Après chaque modification : `git add . && git commit -m "..." && git push`

## Structure

```
index.md                                 -> accueil
00_Introduction.md                       -> programme, évaluation, outils
01_Seance1_Introduction.md               -> De la donnée à la carte
02_Seance2_Sources_Donnees.md            -> Sources et types de données
03_Seance3_Statistique_Descriptive.md    -> Statistique descriptive univariée
04_Seance4_Nettoyage_Donnees.md          -> Structurer et nettoyer sous Excel
05_Seance5_Semiologie_Graphique.md       -> Sémiologie graphique
06_Seance6_Discretisation.md             -> Discrétisation
07_Seance7_Cartographie_Magrit.md        -> Cartographie thématique sous Magrit
08_Seance8_Commentaire_Dossier.md        -> Commentaire de carte et dossier final
09_Ressources.md                         -> Bibliographie et liens
documents/                               -> PDF du support de cours (+ futurs TD)
```
