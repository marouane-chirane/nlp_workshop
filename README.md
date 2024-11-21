# **NLP Sentiment Analysis Project**

## 📖 **Description**
Ce projet explore trois méthodes différentes pour effectuer une analyse des sentiments sur un ensemble de données contenant des avis clients. L'objectif est de comparer ces méthodes en termes de complexité et de précision.

---

## ⚙️ **Méthodes utilisées**
1. **Naive Bayes**
   - Un classificateur bayésien naïf est utilisé sur des données prétraitées.  
   - **Résultat** : Méthode simple et rapide avec des performances limitées sur des textes complexes.

2. **BERT avec Logistic Regression**
   - Les embeddings des avis sont extraits via **BERT** et classifiés à l'aide d'une régression logistique.  
   - **Résultat** : Performances solides avec une bonne compréhension contextuelle des textes.

3. **BERT avec LSTM**
   - Les vecteurs d'embeddings de **BERT** sont combinés avec un réseau LSTM pour capturer les relations séquentielles dans les données textuelles.  
   - **Résultat** : Meilleures performances globales grâce à une meilleure capture des relations complexes dans les avis.

---
## 📂 **Dataset**
- Nom du fichier : `dataset/db_reviews.csv`
- Description : Ce dataset contient des avis clients et leurs sentiments associés.
  - **Colonnes** :
    - `review` : Texte de l'avis.
    - `sentiment` : Label indiquant le sentiment (0 = négatif, 1 = positif).

## 📝 **Lien vers le notebook**
Si vous préférez utiliser Google Colab pour exécuter ce projet, suivez le lien ci-dessous :  
👉 [**Notebook sur Google Colab**]  https://colab.research.google.com/drive/your-link-here](https://colab.research.google.com/drive/1hXr8TxsBZ6DJwc02jVCKnx79p09o-uHF?usp=sharing)
Ce notebook contient une version interactive du code et vous permettra de tester les trois méthodes directement dans un environnement cloud.
---
## 📊 **Résumé des résultats**
| Méthode                  | Précision   | Avantages                              | Inconvénients                          |
|--------------------------|-------------|----------------------------------------|----------------------------------------|
| **Naive Bayes**          | Basique     | Rapide, facile à mettre en œuvre       | Peu performant sur des textes complexes |
| **BERT + Logistic Regression** | Bonne        | Équilibre entre rapidité et précision | Plus complexe à configurer            |
| **BERT + LSTM**          | Excellente  | Capture des relations complexes        | Nécessite plus de ressources           |

---

## 📝 **Conclusion**
Les trois méthodes montrent des performances variées en fonction de leurs complexités et capacités :
- **Naive Bayes** convient pour des tâches rapides mais simples.
- **BERT avec Logistic Regression** offre un bon compromis entre performances et simplicité.
- **BERT avec LSTM** est la méthode la plus précise, adaptée aux analyses avancées des sentiments.

En résumé, les modèles basés sur **BERT** surpassent largement les méthodes traditionnelles pour cette tâche, avec des performances maximales atteintes en combinant BERT et LSTM.


