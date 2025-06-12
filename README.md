# Projet de Métamodélisation pour l’Optimisation Aéronautique

Ce projet explore l’utilisation de modèles de substitution (surrogate models) pour optimiser la conception d’un aéronef sous contraintes et incertitudes. L’objectif est de **minimiser la masse maximale au décollage (MTOM)** tout en respectant des contraintes opérationnelles telles que la longueur de décollage, la vitesse d’approche, ou encore la poussée minimale.

## Contenu

- Construction et comparaison de modèles de substitution (régression polynomiale, réseau de neurones, forêt aléatoire, etc.), Optimisation de la conception sur plusieurs cas d’usage et Validation des résultats issus du métamodèle
- Analyse de sensibilité via les indices de Sobol
- Prise en compte des incertitudes

## Technologies utilisées

- Python
- [GEMSEO](https://gemseo.readthedocs.io/)
- scikit-learn

## Auteurs

Alexandre Demarquet, Thomas Dion, Tristan Gay, Clément Gris  
Projet de juin 2025
