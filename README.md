# 📊 Projet d'Analyse en Composantes Principales (PCA)

## 📋 Description du Projet

Ce projet présente une analyse complète de données psychométriques utilisant l'**Analyse en Composantes Principales (PCA)**. L'étude porte sur l'analyse de performances à différents tests cognitifs avec pour objectif la réduction de dimensionnalité et l'identification de structures sous-jacentes dans les données.

## 🎯 Objectifs

### Principaux
- **Réduction de dimensionnalité** : Passer de 6 variables à 2-3 composantes principales
- **Visualisation des données** dans un espace de dimension réduite
- **Identification des corrélations** entre variables tests
- **Classification des individus** selon leurs profils cognitifs

### Secondaires
- Validation de la structure factorielle des tests
- Économie de testing par identification des redondances
- Construction d'échelles composites robustes

## 📁 Structure du Projet
PCA_Data_Analyse/
│
├── 📊 PCA_Data_Analyse.ipynb # Notebook principal d'analyse
├── 📄 README.md # Ce fichier
├── 📋 rapport_analysis.pdf # Rapport détaillé (LaTeX)



## 🔧 Technologies Utilisées

### Langages & Librairies
- **Python 3.8+**
- **Pandas** - Manipulation des données
- **NumPy** - Calculs scientifiques
- **Scikit-learn** - Implémentation PCA
- **Matplotlib/Seaborn** - Visualisations
- **Jupyter Notebook** - Environnement d'analyse

### Méthodes Statistiques
- Analyse en Composantes Principales (PCA)
- Analyse de corrélation
- Standardisation des données
- Analyse factorielle exploratoire

## 📊 Données

### Description des Variables
| Variable | Description | Échelle |
|----------|-------------|---------|
| **CUB** | Raisonnement spatial/abstrait | 0-5 |
| **PUZ** | Résolution de problèmes | 0-5 |
| **CAL** | Capacités calculatoires | 0-5 |
| **MEM** | Mémoire | 0-4 |
| **COM** | Compréhension verbale | 0-4 |
| **VOC** | Vocabulaire | 0-4 |

### Échantillon
- **15 individus** (l1 à l15)
- **6 variables** psychométriques
- Données simulées pour tests WISC

## 🚀 Installation et Exécution



## Méthodologie
Workflow d'Analyse
📥 Chargement des données

🔍 Analyse exploratoire

📊 Normalisation (standardisation)

📈 Matrice de corrélation

🎯 Application PCA

📉 Analyse de la variance expliquée

🖼️ Visualisations

📝 Interprétation des résultats


### Prérequis
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
