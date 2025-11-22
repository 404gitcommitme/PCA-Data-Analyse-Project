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



### Résultats Principaux
Structure de Corrélation Identifiée
Groupe cognitif abstrait : CUB-PUZ-CAL (corrélations 0.73-0.92)

Groupe verbal : COM-VOC (corrélation 0.78)

Variable mémoire isolée : MEM (corrélations négatives)

Variance Expliquée Prédite
Composante	Variance	Interprétation
PC1	45-55%	Opposition cognition vs mémoire
PC2	20-25%	Compétences verbales
PC3	10-15%	Variance résiduelle
🎨 Visualisations Générées
1. Scree Plot
Variance expliquée par composante

Sélection du nombre optimal de composantes

2. Cercle des Corrélations
Projection des variables dans le plan factoriel

Visualisation des contributions

3. Projection des Individus
Classification des profils cognitifs


Données simulées

Ratio observations/variables faible (15/6 = 2.5)

Précautions d'Interprétation
Validation croisée recommandée

Prudence dans la généralisation

Considération des intervalles de confiance

### 📚 Applications Pratiques
En Psychométrie
Identification de profils cognitifs

Économie de testing

Construction d'échelles composites

En Recherche
Validation de construits théoriques

Détection d'outliers

Comparaison de groupes

🔮 Perspectives
Améliorations Possibles
Application sur échantillon plus large

Validation avec données réelles

Comparaison avec analyse factorielle confirmatoire

Étude longitudinale des profils

Développements Futurs
Interface interactive de visualisation

Application web de diagnostic

Base de données normative

### Auteur
Analyse de Données Psychométriques
*Projet académique - Avril 2025*

📄 Licence
Ce projet est destiné à un usage éducatif et de recherche.

🤝 Contribution
Les contributions sont les bienvenues ! N'hésitez pas à :

Fork le projet

Créer une branche feature (git checkout -b feature/AmazingFeature)

Commit les changements (git commit -m 'Add AmazingFeature')

Push sur la branche (git push origin feature/AmazingFeature)

Ouvrir une Pull Request

📞 Contact
Pour toute question concernant ce projet :

📧 Email : benchetioui.yh@gmail.com

💼 LinkedIn : http://linkedin.com/in/youcef-haroune-benchetioui-950718368

🐙 GitHub : @404gitcommitme

⭐ N'oubliez pas de donner une étoile au projet si vous le trouvez utile !