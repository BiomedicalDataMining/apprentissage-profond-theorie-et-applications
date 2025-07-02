
# Ressources - Apprentissage profond : Théorie et applications 
(1ère édition)

<div align="center">
<img src="https://m.media-amazon.com/images/I/71n2PGSn-ML._SL1303_.jpg" alt="Couverture du livre Apprentissage profond : Théorie et applications" width="250">
</div>

Ce dossier contient les ressources spécifiques à la **1ère édition** du livre « Apprentissage profond : Théorie et applications » par Neila Mezghani.

**📚 <a href="https://www.amazon.ca/Apprentissage-profond-Prof-Neila-Mezghani/dp/B0FFBBFNNR/" target="_blank">Acheter le livre sur Amazon</a>**

## 📚 Chapitres disponibles

### [Chapitre 1 - Fondamentaux de l'apprentissage machine (AM)](./Chapitre%201%20-%20Fondamentaux%20de%20l'apprentissage%20machine%20(AM)/)
- **Notebook** : `Chapitre 1 - Fondamentaux de l'apprentissage machine (AM).ipynb`
- **Figures** : 7 figures illustrant les concepts fondamentaux (Figures 1.11 à 1.21)
- **Contenu** : Introduction aux concepts de base, types d'apprentissage, évaluation des modèles

### [Chapitre 2 - Modèles de régression](./Chapitre%202%20-%20Modèles%20de%20régression/)
- **Notebook** : `Chapitre 2 - Modèles de régression.ipynb`
- **Figures** : 9 figures + 1 animation interactive (régression multiple)
- **Contenu** : Régression linéaire, polynomiale, logistique, métriques d'évaluation

### [Chapitre 3 - Réseaux de neurones artificiels](./Chapitre%203%20-%20Réseaux%20de%20neurones%20artificiels/)
- **Notebook** : `Chapitre 3 - Réseaux de neurones artificiels.ipynb`
- **Figures** : 8 figures incluant des visualisations interactives HTML
- **Contenu** : Perceptron, réseaux multicouches, rétropropagation, fonctions d'activation

### [Chapitre 4 - Réseaux de neurones profonds - Défis et solutions](./Chapitre%204%20-%20Réseaux%20de%20neurones%20profonds%20-%20Défis%20et%20solutions/)
- **Notebooks** : 4 notebooks spécialisés
  - `Chapitre 4.1` - Défis et solutions générales
  - `Chapitre 4.2` - Transfert d'apprentissage
  - `Chapitre 4.3` - Augmentation des données
  - `Chapitre 4.4` - Régularisation
- **Résultats** : Dossier `Transfer_Learning_Results/` avec analyses et métriques
- **Contenu** : Problèmes de gradient, techniques de régularisation, transfer learning

### [Chapitre 5 - Réseaux de neurones convolutifs (CNN)](./Chapitre%205%20-%20Réseaux%20de%20neurones%20convolutifs%20(CNN)/)
- **Notebook** : `Chapitre 5 - Réseaux de neurones convolutifs (CNN).ipynb`
- **Figures** : 5 dossiers de figures illustrant les concepts CNN
- **Contenu** : Convolution, pooling, architectures CNN classiques, applications vision

### [Chapitre 6 - Réseaux de neurones récurrents (RNN)](./Chapitre%206%20-%20Réseaux%20de%20neurones%20récurrents%20(RNN)/)
- **Notebook** : `Chapitre 6 - Réseaux de neurones récurrents (RNN).ipynb`
- **Base de données** : `Mastercard_stock_history.csv` pour les exemples pratiques
- **Figures** : 7 dossiers de figures pour les concepts RNN/LSTM
- **Contenu** : RNN, LSTM, GRU, séries temporelles, prédiction financière

### [Chapitre 7 - Auto-encodeurs](./Chapitre%207%20-%20Auto-encodeurs/)
- **Notebook** : `Chap7-Auto-encodeurs.ipynb`
- **Figures** : 5 dossiers de figures illustrant les architectures
- **Contenu** : Auto-encodeurs classiques, débruitage, variational autoencoders

### [Chapitre 8 - Modèles génératifs](./Chapitre%208%20-%20Modèle-Generatif/)
- **Notebook** : `Chap8-Modeles-generatifs.ipynb`
- **Animations** : 3 GIFs montrant l'évolution des modèles (GAN, VAE, DDPM)
- **Résultats** : Dossiers organisés par type de modèle (GAN, VAE, GMM, DDPM)
- **Contenu** : GANs, VAEs, modèles de diffusion, applications créatives

## 🎯 Ressources par type

### 📓 Notebooks Jupyter
- **11 notebooks** au total couvrant tous les aspects de l'apprentissage profond
- Code Python commenté et prêt à l'exécution
- Exemples pratiques avec visualisations intégrées

### 🖼️ Figures et visualisations
- **Plusieurs figures** haute qualité aux formats JPG, PNG et PDF
- Visualisations interactives HTML pour certains concepts
- Schémas architecturaux détaillés

### 🎬 Animations pédagogiques
- **Animations GIF** illustrant l'évolution des algorithmes
- Visualisations dynamiques des processus d'apprentissage
- Comparaisons visuelles entre différentes approches

### 📊 Données et résultats
- Jeux de données réels (historique boursier Mastercard)
- Résultats d'expériences et métriques de performance
- Analyses comparatives des différentes approches

## ⚙️ Configuration de l'environnement

### Prérequis système
- **Python 3.10+**
- **Jupyter Notebook** ou **JupyterLab**
- **8GB RAM minimum** (16GB recommandé pour les modèles complexes)
- **GPU optionnel** mais recommandé pour l'entraînement

### Installation des dépendances

#### Option 1 : Installation rapide
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter seaborn plotly opencv-python
```

#### Option 2 : Installation avec conda
```bash
conda create -n deep-learning python=3.10
conda activate deep-learning
conda install tensorflow numpy pandas matplotlib scikit-learn jupyter seaborn plotly opencv
```

## 🚀 Guide de démarrage

### 1. Vérification de l'installation
```python
import tensorflow as tf
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

print(f"TensorFlow: {tf.__version__}")
print(f"GPU disponible: {tf.config.list_physical_devices('GPU')}")
```

### 2. Ordre recommandé d'étude
1. **Chapitre 1** : Concepts fondamentaux (obligatoire)
2. **Chapitre 2** : Modèles de régression (base mathématique)
3. **Chapitre 3** : Réseaux de neurones (architecture de base)
4. **Chapitre 4** : Techniques avancées (optimisation)
5. **Chapitres 5-8** : Architectures spécialisées (selon vos intérêts)

## 🔧 Résolution de problèmes courants

### Problèmes de mémoire
- Réduisez la taille des batches dans les notebooks
- Fermez les autres applications gourmandes en mémoire
- Utilisez `tf.config.experimental.set_memory_growth()` pour TensorFlow

### Problèmes de visualisation
```bash
# Si les graphiques ne s'affichent pas
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension
```

## 📖 Documentation supplémentaire

- **[TensorFlow Guide](https://www.tensorflow.org/guide)** : Documentation officielle TensorFlow
- **[Keras Examples](https://keras.io/examples/)** : Exemples pratiques Keras

## 🔗 Navigation

- **[← Retour au README principal](../README.md)**
- **[Chapitre 1 →](./Chapitre%201%20-%20Fondamentaux%20de%20l'apprentissage%20machine%20(AM)/)**

## 📌 Auteur

**<a href="https://www.teluq.ca/siteweb/univ/en/nmezghan.html" target="_blank">Neila Mezghani</a>**
- Professeure à l'Université TÉLUQ
- Spécialiste en apprentissage automatique et intelligence artificielle
- Experte en applications biomédicales de l'IA
- **<a href="https://ca.linkedin.com/in/neila-mezghani" target="_blank">💼 LinkedIn</a>**

---

💡 **Conseil** : Gardez ce README ouvert comme référence pendant votre apprentissage !
