# Activité Pratique N°1 : Mise en œuvre du Framework PyTorch

Ce dépôt contient les travaux pratiques réalisés dans le cadre du module **IA Générative** (HESTIM - 5 IIIA), sous la supervision de **Mohamed Youssfi**. L'objectif de cette activité est de se familiariser avec les fondamentaux du Deep Learning et du framework **PyTorch**.

---
👨‍💻 Auteur
Audes M.: Étudiante en 5ème année Ingénierie

##  Contenu du TP

Le tp est divisé en deux grandes parties :

### Partie 1 : Fondamentaux des Réseaux de Neurones avec PyTorch
Reprise et implémentation de la démo pratique [Part 1- Neural Network Fundamentals with PyTorch For Generative AI](https://www.youtube.com/watch?v=vCbEmtrR0_w) :
* **Vérification de l'environnement :** Initialisation de PyTorch, vérification de la version et détection du GPU (`torch.cuda`).
* **Manipulation des Tenseurs :** Création, redimensionnement, types de données (`torch.float32`), et transfert des tenseurs entre le CPU et le GPU (`.to(device)`).
* **Opérations mathématiques :** Addition, multiplication élément par élément.
* **Autograd (Rétropropagation) :** Calcul automatique des gradients avec `requires_grad=True`, utilisation de `.backward()`, et gestion des graphes computationnels (gestion de l'erreur liée au double passage avec `retain_graph=True`).

### Partie 2 : Exercices Pratiques
* **Exercice 1 (Régression) :** Prédiction du salaire en fonction de l'ancienneté et du degré d'expertise.
* **Exercice 2 (Classification) :** Classification multiclasse sur le célèbre dataset **IRIS** (`sklearn.datasets`).
* **Exercice 3 (MLP) :** Implémentation d'un Perceptron Multicouche (Multi-Layer Perceptron) sur la reconnaissance de chiffres manuscrits (**MNIST**).
* **Exercice 4 (CNN) :** Implémentation d'un Réseau de Neurones Convolutif (Convolutional Neural Network) sur le dataset **MNIST**.

---

## 🛠️ Technologies et Outils Utilisés
* **Python** (v3.13)
* **PyTorch** (v2.14) : Framework principal de Deep Learning.
* **Scikit-learn** : Pour le chargement de datasets de référence comme IRIS.
* **Matplotlib** : Visualisation des pertes (loss) et des images.
* **uv** : Gestionnaire de paquets ultra-rapide pour Python.

---
## 🚀 Installation et Utilisation

1. Clone le dépôt sur votre machine :
   ```bash
   git clone [https://github.com/AudesM-space/Ai-generative.git](https://github.com/AudesM-space/Ai-generative.git)
   cd Ai-generative
  ```
 

 
