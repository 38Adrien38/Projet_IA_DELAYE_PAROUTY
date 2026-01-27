# Apprentissage de l'anatomie radiologique par Few-Shot Learning

Ce projet vise à développer un algorithme capable de segmenter automatiquement des organes et des tumeurs sur des CT-scans. 

## Description du projet

L'objectif principal est de pallier les difficultés de l'IA face à des structures anatomiques nouvelles ou non labellisées. Le projet utilise des images de CT-scans annotées et des images brutes pour entraîner des modèles de segmentation performants.

Afin d'obtenir les données et les meilleurs modèles entraînés, veuillez les télécharger via ce lien : https://drive.google.com/drive/folders/1JVcOdkHdGllgJmH0hWK7mG5O98iSG05b?usp=sharing 

## Travail réalisé

Sur ce GitHub, vous trouverez plusieurs notebooks présentant des solutions à notre problématique initiale. Plusieurs approches ont été utilisées :

- Approche supervisée via U-Net
- Approche non supervisée via K-means
- Approche hybride avec K-means et Random Forest
- Augmentation de données via cGAN
- Approche supervisée plus adaptée au few shot learning via PANet 


## Utilisation

### Prérequis
L'outil **uv** est nécessaire pour gérer ce projet. Vous pouvez l'installer depuis https://docs.astral.sh/uv/getting-started/installation/#standalone-installer. 
- Ou bien utiliser cette commande : 
```bash
pip install uv
```

### Installation
Clonez le dépôt et synchronisez l'environnement.

```bash
git clone <URL_DU_DEPOT>
cd <NOM_DU_PROJET>
uv sync