# prediction-des-salaires-dans-le-secteur-prive
# 📊 Analyse et Prédiction des Salaires dans le Secteur Privé Français  

## 📌 Contexte  
Ce projet vise à analyser et modéliser les salaires dans le secteur privé français à partir de données socio-démographiques et professionnelles.  
L’objectif est double :  
1. **Exploratoire** : identifier les facteurs influençant le salaire (sexe, PCS, temps de travail, territoire, année, etc.).  
2. **Prédictif** : entraîner un modèle supervisé (régression) afin d’estimer le salaire moyen selon les caractéristiques des individus ou des groupes.

---

## 📂 Contenu du projet  
- **`Analyse_Salaire_secteur_prive_francais.ipynb`** → Notebook principal contenant l’analyse, la préparation des données et la modélisation.  
- **Données (CSV)** → Jeux de données utilisés pour l’analyse (non inclus ici, à placer dans un dossier `data/`).  

---

## ⚙️ Étapes du projet  

### 1. Exploration des données (EDA)  
- Analyse univariée et bivariée.  
- Détection et traitement des valeurs manquantes et outliers.  
- Visualisations (histogrammes, boxplots, heatmaps, etc.).  

### 2. Préparation des données  
- Nettoyage et harmonisation des variables.  
- Encodage des variables catégorielles.  
- Normalisation / standardisation si nécessaire.  

### 3. Modélisation supervisée  
- Régression linéaire (variable cible continue = **salaire moyen**).  
- Random Forest
- Évaluation de la performance (R², RMSE, MAE).  
- Analyse des limites du modèle et des pistes d’amélioration (interactions, modèles non-linéaires).  

### 4. Interprétation et conclusions  
- Impact du sexe, de la PCS, de l’année et du territoire sur le salaire.  
- Identification des principaux facteurs explicatifs.  

---

## 🚀 Installation & Utilisation  

### 1. Cloner le projet  
```bash
git clone https://github.com/ton-repo/salaire-analyse.git
cd salaire-analyse
```

### 2. Créer un environnement Python  
```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Installer les dépendances  
```bash
pip install -r requirements.txt
```

*(Si `requirements.txt` n’existe pas, lancer le notebook et installer au besoin : pandas, numpy, matplotlib, seaborn, scikit-learn).*  

### 4. Lancer Jupyter Notebook  
```bash
jupyter notebook
```

Puis ouvrir **`Analyse_Salaire_secteur_prive_francais.ipynb`**.  

---

## 📈 Résultats attendus  
- Une vision claire des inégalités salariales en fonction des caractéristiques individuelles.  
- Un modèle de régression permettant d’estimer un salaire moyen en fonction de variables explicatives.  
- Des recommandations méthodologiques pour affiner les prédictions.  

---

## 📌 Améliorations futures  
- Tester des modèles non-linéaires (Gradient Boosting, Réseaux de neurones).  
- Intégrer davantage de variables (ex : ancienneté, niveau d’études).  
- Déployer le modèle sous forme d’API ou application interactive (Streamlit).  
