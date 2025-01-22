# anomaly-detection-xray_83-accuracy
Modèle CNN pour la Classification d'Images Radiographiques

Ce projet utilise un modèle séquentiel CNN conçu pour la classification d'images radiographiques (dimensions 640x640x3) en quatre catégories : NORMAL, PNEUMONIA, TUBERCULOSIS, et UNKNOWN.

Caractéristiques du Modèle
Architecture : 4 couches convolutionnelles.
Optimiseur : Adam.
Données : Le dataset est accessible via Kaggle : /kaggle/input/combined-unknown-pneumonia-and-tuberculosis.
Prétraitement des Données
L'outil ImageDataGenerator a été utilisé pour :

Augmenter la diversité des données via des transformations d'images.
Normaliser les images pour une convergence plus rapide.
Améliorer la généralisation et la robustesse du modèle.
Réduire les contraintes mémoire lors de l'entraînement.
Résultats
Précision : 82.9% (accuracy).
Entraînement : Arrêt anticipé après 12 époques (early stopping).

