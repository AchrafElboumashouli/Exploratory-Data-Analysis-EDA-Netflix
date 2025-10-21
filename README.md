# 🎬 Exploratory Data Analysis (EDA) — Netflix Titles Dataset

## 🧠 Description du projet
Ce projet consiste à réaliser une **analyse exploratoire de données (EDA)** sur le dataset public des titres Netflix, afin d'extraire des **informations pertinentes** sur la répartition des films et séries, les pays producteurs, les genres dominants et les tendances de sortie au fil du temps.

L’objectif est de démontrer les compétences en **analyse de données**, **visualisation**, et **communication d’insights** à l’aide d’outils Python.

---

## 📂 Structure du projet
```bash
EDA-Netflix/
│
├── data/
│ └── netflix_titles.csv # Dataset brut
│
├── notebooks/
│ └── EDA_Netflix.ipynb # Notebook principal avec analyses et graphiques
│
├── requirements.txt # Librairies nécessaires
└── README.md # Ce fichier
```

---

## 🧰 Technologies utilisées
| Outil / Librairie | Rôle |
|--------------------|------|
| **Python 3** | Langage principal d’analyse |
| **Pandas** | Manipulation et nettoyage des données |
| **Matplotlib** | Visualisation de base |
| **Seaborn** | Visualisation avancée et design des graphiques |
| **Jupyter Notebook** | Environnement interactif pour le code et la présentation |

---

## 📊 Jeu de données
- **Nom :** Netflix Movies and TV Shows Dataset  
- **Source :** [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/shivamb/netflix-shows)  
- **Taille :** ~8 800 titres  
- **Colonnes principales :**
  - `type` — Film ou Série TV  
  - `title` — Nom du contenu  
  - `director`, `cast` — Réalisateur(s) / Acteurs  
  - `country` — Pays de production  
  - `release_year` — Année de sortie  
  - `rating` — Classification (TV-MA, PG, etc.)  
  - `listed_in` — Catégories / Genres  
  - `date_added` — Date d’ajout sur Netflix  

---

## 🔍 Étapes principales de l’analyse
1. **Chargement et inspection des données**  
   - Aperçu des colonnes, types de données, valeurs manquantes.
2. **Nettoyage des données**  
   - Gestion des doublons, valeurs manquantes, conversion des types (dates, années...).
3. **Exploration et visualisation**  
   - Répartition des films vs séries  
   - Analyse par pays  
   - Étude de la distribution des années de sortie  
   - Identification des genres dominants  
   - Réalisateurs les plus prolifiques  
4. **Interprétation et synthèse**  
   - Communication des principales tendances et conclusions.

---

## 📈 Principaux résultats
✅ **Les films** représentent environ **70%** du contenu Netflix.  
🌍 Les **États-Unis** et **l’Inde** dominent largement la production.  
🎭 Les genres les plus présents sont **Drame**, **Comédie** et **Documentaire**.  
📆 La majorité des titres ont été publiés **après 2010**, avec un pic entre **2018–2020**.  
🎬 Les réalisateurs comme **Rajiv Chilaka** figurent parmi les plus productifs.

---

## 🖼️ Exemple de visualisations
### 1. Répartition des types de contenu
![Movies vs TV Shows](https://github.com/yourusername/EDA-Netflix/blob/main/images/movies_vs_tvshows.png)

### 2. Top 10 des pays producteurs
![Top Countries](https://github.com/yourusername/EDA-Netflix/blob/main/images/top_countries.png)

*(Les images peuvent être ajoutées dans un dossier `/images` du dépôt.)*

---

## 🚀 Lancer le projet
### 1️⃣ Cloner le dépôt
```bash
git clone https://github.com/yourusername/EDA-Netflix.git
cd EDA-Netflix
```
2️⃣ Installer les dépendances

```bash
pip install -r requirements.txt
```
3️⃣ Ouvrir le notebook
```bash
jupyter notebook notebooks/EDA_Netflix.ipynb
```

👤 Author
---
achraf EL BOUMASHOULI
