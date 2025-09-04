# sentiment-analysis-
Projet de classification de sentiments en Python avec Scikit-learn.
# 🔍 Analyse de Sentiments sur des Avis Clients

## 📖 Présentation du Projet
Ce projet est une application de **Traitement Automatique du Langage (NLP)** qui classifie des avis clients en **positifs** ou **négatifs**. Il illustre parfaitement le pipeline complet d'un projet de Machine Learning, du nettoyage des données à l'évaluation du modèle.

## 🛠️ Technologies Utilisées
- **Langage :** Python 3
- **Librairies principales :**
  - `pandas`, `numpy` : Manipulation des données
  - `matplotlib`, `seaborn` : Visualisation
  - `nltk` : Prétraitement du langage naturel (Tokenization, Stopwords, Lemmatisation)
  - `scikit-learn` : Machine Learning (TF-IDF, Regression Logistique, Naive Bayes, Métriques)
  - `wordcloud` : Nuage de mots pour la visualisation textuelle

## 📁 Jeu de Données
Pour les besoins de la démonstration, un petit jeu de données factice a été créé directement dans le notebook. Il contient :
- **10 avis clients en anglais** simulés.
- **Labels :** Positif (`1`) / Négatif (`0`)

**📝 Note :** Pour une application réelle, il est facile de remplacer ce jeu de données par un vrai (ex: [Amazon Product Reviews sur Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)).

## ⚙️ Installation et Exécution

1. **Clonez ce repository :**
   ```bash
   git clone https://github.com/IssaHissein/sentiment-analysis.git
   cd sentiment-analysis
