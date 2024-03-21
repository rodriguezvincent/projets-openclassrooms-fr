# Aperçu du projet

L'objectif de ce projet est de réaliser une étude de l'accès à l'eau potable dans le monde et de produire une série de dashboards afin d'accompagner une ONG dans sa prise décision.

Lien vers la story sur Tableau public: [DWFA_VRodriguez](https://public.tableau.com/app/profile/vincent.rodriguez8459/viz/DWFA_VRodriguez/DWFA_Story)

### Étapes du projet
  - Exploration, nettoyage et préparation des données.
  - Recueil des besoins et réalisation des blueprint et mockup.
  - Réalisation des dashboards sur Tableau (story).

### Code
**Aperçu des fichiers:**
  - `p8_préparation.ipynb` - notebook Jupyter présentant l'exploration et la préparation des données.
  - `p8_data.csv` - fichier final contenant toutes les données nécessaires à l'étude.
  - `p8_blueprint.pdf` - pdf présentant les besoins émis par les utilisateurs et le plan mis en place (mesures, visualisations, pages) afin de      répondre à ces besoins. 
  - `p8_mockup.pdf` - pdf présentant la 1ère trame des dashboards.
  - `p8_dashboards.pdf` - pdf de la story Tableau.

# Setup
  - Librairies Python:
    - pandas
    - numpy
    - matplotlib

### Data
Les données utilisées sont fournies par la plateforme OpenClassrooms :
  - `BasicAndSafelyManagedDrinkingWaterServices.csv` - Qualité des infrastructures ("basic" ou "safely managed").
  - `MortalityRateAttributedToWater.csv` - Taux de mortalité attribué à la consommation d'eau non potable.
  - `PoliticalStability.csv` - Indice de stabilité politique.
  - `Population.csv` - Nombre d'habitants par: pays, zone, sexe.
  - `RegionCountry_.csv` - Région du monde associée à chaque pays (selon la nomenclature de la World Health Organisation).
