# 🏀 Analyse NBA avec Python & Pandas

Ce projet a pour objectif de réaliser une **analyse complète et détaillée** de statistiques NBA sur plusieurs saisons à l’aide de **Python** et de ses librairies **Pandas** et **Matplotlib**, à partir d’un jeu de données contenant des informations sur les joueurs (caractéristiques physiques, pays d'origine, performances sportives, etc.).

---

## 📁 Données

Le fichier principal est :  
**`all_seasons.csv`**  
Il contient les statistiques de milliers de joueurs NBA, saison par saison.

**Exemples de colonnes :**

- `player_name`, `team_abbreviation`, `age`, `player_height`, `player_weight`
- `college`, `country`, `draft_year`, `draft_round`
- `pts` (points), `reb` (rebonds), `ast` (passes)
- `ts_pct` (taux de réussite aux tirs), `net_rating`, etc.

---

## 🔍 Objectifs de l'analyse

L’analyse se structure autour de 6 grands axes :

### 1. **Statistiques générales**
- Fonctions de bases de Pandas utilisées pour visualiser le jeu de données dans sa globalité

### 2. **Performances sportives**
- Top scoreurs, rebondeurs et passeurs toute saison confondue.
- Corrélations (ex. : taille vs rebonds)
- Évolution des statistiques (net rating, usage, efficacité)

### 3. **Parcours et formation**
- Impact du collège ou du pays d’origine
- Analyse par tour de draft
- Joueurs non draftés les plus performants

### 4. **Analyses croisées**
- Progression individuelle d’une saison à l’autre
- Influence du poids, taille, usage sur les stats
- Longévité des joueurs

### 5. **Évolution dans le temps**
- Tendances globales (passes, tirs, rebonds)
- Croissance du nombre de joueurs internationaux
- Changement dans les styles de jeu

### 6. **Classements et comparaisons**
- Classement des équipes par performances
- Joueurs all-time les plus efficaces
- Profils types des joueurs selon les équipes

---

## 🛠️ Outils utilisés

- **Python**
- **Pandas** pour la manipulation des données
- **Matplotlib / Seaborn** pour la visualisation (optionnel)
- **Jupyter Notebook** pour structurer l’analyse (recommandé)

---

## 🚀 Pour démarrer

1. Cloner le projet :
```bash
git clone https://github.com/ton-repo/nba-analysis.git
cd nba-analysis
