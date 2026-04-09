# 🌍 Étude FAO — Sous-nutrition dans le monde (2013-2017)

**Projet 4 — Formation Data Analyst | OpenClassrooms**

## 📋 Contexte

Étude de santé publique réalisée dans le cadre de la formation Data Analyst OpenClassrooms.
L'objectif est d'analyser les données de la FAO sur la sous-nutrition mondiale entre 2013 et 2017.

## 🎯 Résultats clés

- **535 700 000** personnes sous-nutries en 2017 — soit **7,1%** de la population mondiale
- Le monde pourrait théoriquement nourrir **8,37 milliards** de personnes (110,9% de la pop. mondiale)
- Avec les végétaux seuls : **6,9 milliards** de personnes nourries (91,5%)
- **Haïti** : pays le plus touché avec 48,3% de sa population sous-nutrie
- **Thaïlande** : paradoxe — 83,4% du manioc exporté malgré 8,96% de sous-nutrition
- La faim dans le monde est un problème de **distribution**, pas de production

## 📁 Sources de données

4 fichiers CSV issus de [FAOSTAT](https://www.fao.org/faostat/) (données publiques) :

| Fichier | Contenu |
|---|---|
| `population.csv` | Population par pays et par année |
| `dispo_alimentaire.csv` | Disponibilité alimentaire 2017 (17 variables) |
| `sous_nutrition.csv` | Nombre de personnes sous-nutries par pays |
| `aide_alimentaire.csv` | Aide alimentaire par pays, produit et année |

## 🛠️ Stack technique

| Outil | Usage |
|---|---|
| Python 3 | Langage principal |
| Pandas | Manipulation et analyse des données |
| Matplotlib / Seaborn | Visualisations statiques |
| Plotly | Carte choroplèthe interactive |
| Folium | Carte choroplèthe interactive (alternative) |
| Jupyter Notebook | Environnement d'analyse |

## 📊 Analyses réalisées

- **3.1** — Proportion de personnes en état de sous-nutrition en 2017
- **3.2** — Nombre théorique de personnes pouvant être nourries
- **3.3** — Idem avec les végétaux uniquement
- **3.4** — Répartition de la disponibilité intérieure mondiale
- **3.5** — Utilisation des céréales (humains vs animaux)
- **3.6** — Top 10 pays avec la plus forte proportion de sous-nutrition
- **3.7** — Top 10 pays bénéficiaires d'aide alimentaire (2013-2016)
- **3.8** — Évolution de l'aide alimentaire pour les 5 premiers pays
- **3.9** — 10 pays avec la plus faible disponibilité alimentaire par habitant
- **3.10** — Top 10 pays avec la plus forte disponibilité alimentaire
- **3.11** — Cas d'étude : Thaïlande et le manioc

## 🔒 RGPD

Les données utilisées sont **agrégées par pays** et issues d'une base publique (FAOSTAT).
Aucune donnée personnelle identifiable n'est présente dans ce projet.

## 🌐 Présentation

👉 [Voir la présentation en ligne](https://bader28-lab.github.io/fao-sous-nutrition/)

## 👤 Auteur

**Badre Bouziane** — Data Analyst en formation @ OpenClassrooms
