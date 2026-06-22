# 🌾 Data Analysis : FAO Productions Agricultural — Dataset 
**De débutant à avancé — A → Z**

---

## 📁 Structure du projet

```
cours_data/
│
├── README.md                          ← Ce fichier (lis-le en premier !)
│
├── phase1_fondations/                 ← COMMENCE ICI
│   ├── etape1_explorer.py             ← Charger et explorer un dataset
│   ├── etape2_filtrer.py              ← Filtrer et sélectionner des données
│   ├── etape3_groupby.py              ← Statistiques et groupby
│   ├── etape4_graphique.py            ← Visualisation matplotlib
│   ├── etape5_regions.py              ← Comparer plusieurs groupes
│   └── etape6_notebook_jupyter.ipynb  ← Rapport complet (Jupyter)
│
├── phase2_intermediaire/
│   ├── etape7_acp.py                  ← ACP (réduction de dimensions)
│   ├── etape8_kmeans.py               ← Clustering K-Means
│   ├── etape9_correlation.py          ← Corrélation et heatmap
│   ├── etape10_nettoyage.py           ← Nettoyage avancé / outliers
│   ├── etape11_regression.py          ← Régression linéaire (prédiction)
│   └── etape12_plotly.py              ← Visualisation interactive
│
└── phase3_avance/
    ├── etape13_random_forest.py       ← Classification (Machine Learning)
    └── etape14_series_temporelles.py  ← Prévision temporelle
```

---

## 🚀 Comment utiliser 

### 1. Installe Python et les bibliothèques
```bash
pip install pandas matplotlib scikit-learn plotly statsmodels scipy seaborn
pip install jupyter notebook
```

### 2. Place le fichier de données dans le même dossier
```
cours_data/
└── JeuDonnee.csv   ← ton fichier FAO ici
```

### 3. Lance les étapes dans l'ordre
```bash
python etape1_explorer.py
python etape2_filtrer.py
# etc.
```

### 4. Pour le notebook Jupyter (étape 6)
```bash
jupyter notebook etape6_notebook_jupyter.ipynb
```

---

## 📚 Ce que tu apprends à chaque étape

| Étape | Compétence | Commandes clés |
|-------|-----------|----------------|
| 1 | Explorer un dataset | `read_csv · head · dtypes · isnull` |
| 2 | Filtrer les données | `df[condition] · isin() · query()` |
| 3 | Statistiques | `groupby · sum · sort_values · describe` |
| 4 | Graphiques | `plt.plot · fill_between · annotate` |
| 5 | Comparaisons | `pivot_table · bar stacked` |
| 6 | Rapport Jupyter | `Markdown · cellules · conclusions` |
| 7 | ACP | `StandardScaler · PCA · cercle corrélations` |
| 8 | Clustering | `KMeans · silhouette_score` |
| 9 | Corrélation | `corr() · heatmap · scatter` |
| 10 | Nettoyage | `dropna · fillna · IQR · Z-score · boxplot` |
| 11 | Régression | `LinearRegression · R² · train_test_split` |
| 12 | Interactif | `plotly · px.line · px.bar · px.scatter` |
| 13 | Classification | `RandomForest · confusion matrix · feature importance` |
| 14 | Prévision | `seasonal_decompose · ExponentialSmoothing · forecast` |


