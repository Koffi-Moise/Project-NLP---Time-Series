# Data Science Projects

Ce dépôt contient deux projets d'analyse de données développés dans le cadre du module Applied Deep learning.

## 📊 Projets

### 1. Time Series Analysis - Prévision de Ventes

Analyse et prévision de séries temporelles avec des modèles ARIMA et SARIMA.

**Techniques utilisées :**
- Décomposition de séries temporelles (tendance, saisonnalité, bruit)
- Tests de stationnarité (ADF)
- Modélisation ARIMA(p,d,q) et SARIMA
- Visualisation des prévisions avec intervalles de confiance

**Librairies :** `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`

### 2. RAG System - Apprentissage par Renforcement

Système de Question-Réponse basé sur RAG (Retrieval-Augmented Generation) pour interroger un document PDF sur l'apprentissage par renforcement profond.

**Fonctionnalités :**
- Extraction et preprocessing de texte PDF
- Chunking intelligent avec overlap
- Recherche sémantique via FAISS
- Génération de réponses avec Qwen2.5
- Interface Gradio interactive

**Librairies :** `PyPDF2`, `sentence-transformers`, `faiss`, `transformers`, `gradio`

## 🚀 Installation

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/votre-repo.git
cd votre-repo

# Installer les dépendances
pip install -r requirements.txt
```

## 📝 Utilisation

### Time Series Project
```python
python time_series_project.py
```

### NLP RAG System
```python
python nlp_project.py
```

## 📦 Dépendances

Créez un fichier `requirements.txt` avec :
```
numpy
pandas
matplotlib
seaborn
statsmodels
PyPDF2
sentence-transformers
faiss-cpu
transformers
gradio
torch
```

## 👤 Auteur

AKAKPO Koffi Moïse
