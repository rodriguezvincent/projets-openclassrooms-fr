# Aperçu du projet

L'objectif de ce projet est d'étudier les chiffres de vente d'une librairie afin de trouver des pistes de développement commercial et émettre des recommandations.

### Étapes du projet
  - Exploration, préparation des données et création d'un fichier global de travail.
  - Étude univariée (séries temporelles, profils des clients, catégories de produits)
  - Analyses bivariées et tests statistiques.
  - Recommandations.

### Code
**Aperçu des fichiers:**
  - `p6_préparation.ipynb` - notebook Jupyter présentant l'exploration et la préparation des données.
  - `p6_analyses.ipynb` - notebook Jupyter contenant les analyses et tests statistiques réalisés.

# Setup
  - Librairies Python:
    - pandas
    - numpy
    - seaborn
    - matplotlib
    - scipy
    - math

### Data
Les données utilisées sont fournies par la plateforme OpenClassrooms:
  - `customers.csv` - Liste des clients (id, date de naissance, sexe) .
  - `products.csv` - Liste des produits (id, prix, catégorie).
  - `transactions.csv` - Liste des transactions effectuées (id, date, id_session, id_client).
