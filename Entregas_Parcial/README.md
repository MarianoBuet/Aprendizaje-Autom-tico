# PROYECTO DE APRENDISAJE AUTOMATICO 

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Entregas Parcial - Mariano Buet

Predicción de alertas térmicas mediante aprendizaje automático a partir de datos climatológicos nacionales

## Project Organization

```

├── README.md          <- Este archivo - Informacion sobre el proyecto
├── data               <- CARPETA DONDE SE ENCUENTRA EL SET DE DATOS
│   ├── external       
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- DOCUMENTOS RELACIONADOS AL PROYECTO
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- JUPITER NOTEBOOKS
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         tarea_clase5 and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── tarea_clase5   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes tarea_clase5 a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

