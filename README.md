# ⚖️ **Police Violence Analysis — Démographie, Géographie & Facteurs Socio-Économiques**

Ce projet analyse les violences policières aux États-Unis à travers une approche statistique, démographique et géographique.
L’objectif est d’étudier les tendances, les groupes les plus touchés, les disparités régionales et l’impact potentiel des facteurs socio-économiques sur la mortalité civile.

Il s’agit d’un projet **personnel**, développé pour renforcer mes compétences en **data analysis**, **statistiques**, **data visualisation** et **storytelling analytique** appliqués à un sujet sociétal réel.


## 🎯 **Objectifs du projet**

* Étudier les **tendances nationales** des violences policières (évolution annuelle, mois, zones critiques)
* Analyser les **inégalités démographiques** (âge, race, sexe, statut armé vs non armé)
* Explorer les **disparités géographiques** (États, villes, taux pour 100k habitants)
* Étudier la relation entre **facteurs socio-économiques** (revenu, pauvreté, éducation, criminalité) et les incidents
* Visualiser les **corrélations** entre variables socio-démographiques et mortalité civile
* Produire des visualisations professionnelles (heatmaps, bar charts, choroplèthes, scatterplots)


## 🧰 **Stack technique**

* **Python 3**
* **pandas** (nettoyage, transformation, enrichissement)
* **NumPy** (calculs statistiques)
* **Matplotlib & Seaborn** (visualisations avancées)
* **Plotly / Folium** *(si utilisé)* pour cartes interactives
* **Jupyter Notebook** pour l’analyse exploratoire
* **Datasets public sources** :

  * Mapping Police Violence
  * US Census (ACS)
  * FBI Crime Statistics


## 📂 **Structure du projet**

```
police_violence_analysis/
 ├── data/
 │   ├── police_violence.csv
 │   ├── demographics.csv
 │   ├── socioeconomic.csv
 ├── notebook.ipynb               # Analyse complète
 ├── visuals/                     # Graphiques exportés
 ├── README.md
```


## 🧹 **Étapes de préparation des données**

### ✔ Import & inspection

* Analyse des colonnes
* Vérification des types
* Détection des valeurs manquantes & doublons

### ✔ Nettoyage

* Standardisation des formats (dates, catégories, États)
* Traitement des valeurs nulles
* Uniformisation des champs démographiques

### ✔ Enrichissement

* Taux par 100k habitants
* Classification des zones (rurales / urbaines)
* Croisement avec données de population & pauvreté
* Ajout de ratios par groupe ethnique ou groupe d’âge

### ✔ Feature engineering

* Indicateurs socio-économiques
* Variables dérivées (armed_status, risk_index, region_group…)


## 📊 **Analyses & visualisations principales**

### 📌 **1. Analyse temporelle**

* Évolution annuelle du nombre d’incidents
* Saisonnalité potentielle
* Variation avant/après certains évènements nationaux

### 📌 **2. Analyse démographique**

* Répartition par **race**, **sexe**, **âge**
* Analyse des cas "non armés"
* Calcul de ratios population / incidents (pour éviter les biais)

### 📌 **3. Analyse géographique**

* Carte des États les plus touchés
* Incidents pour 100k habitants
* Focus villes / comtés critiques
* Heatmap régionale

### 📌 **4. Analyse socio-économique**

Corrélation entre :

* taux de pauvreté ↔ mortalité
* niveaux d’éducation ↔ incidents
* revenu médian ↔ violences policières
* criminalité locale ↔ force utilisée

### 📌 **5. Visualisations clés**

* Histogrammes & distributions
* Boxplots comparant les groupes démographiques
* Scatterplots avec lignes de tendance
* Heatmaps de corrélation socio-économique
* Choroplèthes (cartes thématiques)
* Bar charts des États les plus touchés


## 🧠 **Compétences démontrées**

- ✔ Nettoyage et préparation de données réelles (complexes & multi-sources)
- ✔ Analyse statistique & démographique
- ✔ Étude de corrélations multi-facteurs
- ✔ Data storytelling appliqué à une problématique sociale
- ✔ Création de visualisations avancées (heatmaps, cartes, barplots empilés)
- ✔ Utilisation d’un notebook structuré et commenté
- ✔ Fusion de datasets (merge, join)
- ✔ Calculs de ratios, normalisation par population


## 🔧 **Axes d’amélioration possible**

* Modèle prédictif (ex : identification des zones à haut risque)
* Régression multiple pour quantifier les facteurs déterminants
* Dashboard interactif (Power BI, Tableau, Streamlit)
* Analyse des données de plaintes & bodycams
* Séries temporelles (forecasting)


## 👤 **À propos**

Projet réalisé par **Alex Alkhatib**, dans le cadre de mon intérêt pour l’analyse de données sociétales, la datavisualisation et les modèles explicatifs.


## 📄 Licence
MIT License
Copyright (c) 2025 Alex Alkhatib
