# Aperçu du projet

L'objectif de ce projet est de réalisé une étude de marché afin d'identifier une liste de pays propices au développement commercial d'une entreprise spécialisée dans la production et la commercialisation de viande de volaille.

### Étapes du projet
  - Recueil de données pertinentes et préparation du jeu de données de travail.
  - Exploration des données à l'aide d'algorithmes non-supervisés (ACP), création de nouvelles variables et axes d'analyse.
  - Clustering à l'aide d'algorithmes non-supervisés (K-means & CAH), analyse des clusters et recommandations.

### Code
**Aperçu des fichiers:**
  - [`p9_préparation.ipynb`](https://github.com/rodriguezvincent/ProjetsOpenclassrooms-FR/blob/main/P9-%C3%89tude-de-march%C3%A9/P9_pr%C3%A9paration.ipynb) - notebook Jupyter regroupant les données en un jeux de données global.
  - [`p9_analyse.ipynb`](https://github.com/rodriguezvincent/ProjetsOpenclassrooms-FR/blob/main/P9-%C3%89tude-de-march%C3%A9/P9_analyse.ipynb) - notebook Jupyter contenant l'exploration et l'analyse des données ainsi que la présentation des recommandations.

# Setup
  - Librairies Python:
    - pandas
    - numpy
    - seaborn
    - matplotlib
    - sklearn
    - scipy

### Data
Les données utilisées ont été en quasi-totalité récupérées sur le site de la FAO (Food and Agriculture Organisation) afin d'assurer le plus possible leur véracité et justesse :
  - `FAOSTAT_DépensesPubliques.csv` - Dépenses des États dans le domaine de l'agriculture.
  - `FAOSTAT_PIB.csv` & `FAOSTAT_PIB_hab.csv`- PIB & PIB/habitants.
  - `FAOSTAT_Population.csv` - Population et sa répartition (sexe & localisation).
  - `FAOSTAT_Prix_Production.csv` - Indice de prix à la production.
  - `FAOSTAT_Stabilité_Politique.csv` - Indice de stabilité politique.
  - `FAOSTAT_UGB.csv` - Densité et part des élevages de volailles (en Unité de Gros Bétail).
  - `Import_taxes_FR.csv` - Taux de taxes à l'importation.
  - `(TI)CPI_FR` - Indice de corruption.
