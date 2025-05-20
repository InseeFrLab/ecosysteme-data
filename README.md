# Formation - Initiation à s3

*Auteurs : Ines Hiverlet et Olivier Levitt*

*Contributeurs :

## Site associé

Le site web associé à la formation est déployé à [cette adresse](https://inseefrlab.github.io/formation-s3-initiation/) ([version anglaise](https://inseefrlab.github.io/formation-s3-initiation/en)).

## Déploiement à partir du SSP Cloud

Ce projet contient les supports de cours de l'auto-formation d'initiation à S3 

## Génération des notebooks

Afin de favoriser la reproductibilité de la formation, les sources des supports de cours sont disponibles au format `.qmd` ([Quarto](https://quarto.org/)) dans les différents sous-dossiers du dossier `source/`. Les notebooks `Jupyter` (format `.ipynb`) exécutables associés peuvent être générés en suivant les étapes suivantes :
- [installer Quarto](https://quarto.org/docs/get-started/)
- cloner le dépôt de la formation :

```bash
git clone https://github.com/InseeFrLab/formation-s3-initiation.git
cd formation-s3-initiation
```

- générer les notebooks :

```bash
quarto render --profile notebooks
```

Une fois l'étape de *rendering* terminée, les notebooks générés au format `.ipynb` sont disponibles dans les différents sous-dossiers du dossier `source/`.
