Perceptron Multi-Couches (MLP)

## 🎓 Objectif du projet

Ce projet a été réalisé dans le cadre du contrôle continu de notre cours d'apprentissage automatique. L'objectif principal est d'implémenter **un réseau de neurones à une couche cachée (MLP)** à partir de zéro, sans utiliser de bibliothèques de deep learning (comme PyTorch ou TensorFlow), afin de comprendre les bases de la rétropropagation et de l'apprentissage.


## 📁 Contenu du projet

- Implémentation d'un **classificateur linéaire manuel** 
- Entraînement d'une **régression logistique avec scikit-learn** 
- Implémentation d’un **réseau de neurones MLP** avec :
  - Une couche cachée
  - Fonctions d'activation sigmoid et softmax
  - Apprentissage par descente de gradient (backpropagation)
- Comparaison des performances avec :
  - Perceptron & ADALINE 
  - Régression logistique 
  - MLP de sklearn
  - MLP implémenté manuellement
- Application finale sur un **jeu de données réel : MNIST** 

## 🔍 Dataset utilisé

- `make_moons` : Dataset non-linéaire pour la classification binaire
- `digits` : Dataset MNIST simplifié inclus dans `sklearn.datasets` pour la classification multi-classes

## 📊 Résultats observés

- Le MLP implémenté manuellement a surpassé la régression logistique avec une **accuracy atteignant 100%** sur `make_moons`.
- Sur MNIST, les performances restent limitées sans optimisation mais démontrent la capacité du réseau à traiter des données réelles.
- L'implémentation permet de bien visualiser l'effet du nombre d'époques sur l'apprentissage.


## 💡 Améliorations possibles

- Ajouter plus de couches cachées (deep learning)
- Tester d'autres fonctions d'activation (ReLU, tanh)
- Implémenter la régularisation (L2)
- Utiliser le mini-batch gradient descent
- Normaliser les données en entrée
- Passer à une architecture CNN pour les images (MNIST)


---

