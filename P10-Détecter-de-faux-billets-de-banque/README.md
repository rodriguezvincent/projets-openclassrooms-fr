# Aperçu du projet

L'objectif de ce projet est de créer un algorithme capable d'identifier de faux billets de banque grâce à leurs mesures.

### Étapes du projet
  - Exploration et imputation des données manquantes à l'aide d'une regression linéaire.
  - Test et comparaison des performances de différents modèles (K-means & Regression Logistique).
  - Amélioration du modèle choisi et utilisation sur un jeu de données test.

### Code
**Aperçu des fichiers:**
  - [`p10_code.ipynb`](https://github.com/rodriguezvincent/ProjetsOpenclassrooms-FR/blob/main/P10-D%C3%A9tecter-de-faux-billets-de-banque/p10_code.ipynb) - notebook Jupyter présentant l'exploration des données et la création du modèle.
  - [`p10_app.ipynb`](https://github.com/rodriguezvincent/ProjetsOpenclassrooms-FR/blob/main/P10-D%C3%A9tecter-de-faux-billets-de-banque/p10_app.ipynb) - notebook Jupyter application du modèle final sur un jeu de données test.

# Setup
  - Librairies Python:
    - pandas
    - numpy
    - seaborn
    - matplotlib
    - statsmodel
    - sklearn
    - scipy
    - pickle

### Data
Les données utilisées sont fournies par la plateforme OpenClassrooms:
  - `billets.csv` - jeux de données de départ.
  - `billets_production.csv` - jeux de données test.
