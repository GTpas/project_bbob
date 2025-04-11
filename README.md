# Projet BBOB (Black-Box Optimization Benchmarking)

Ce projet implémente et analyse des algorithmes d'optimisation sur les fonctions de test BBOB (Black-Box Optimization Benchmarking), incluant SNES, Random Search et ABC.

## Structure du Projet

.
├── projet_bbob/
│   ├── data/                    # Données des expériences
│   │   ├── data_SNES/          # Données pour l'algorithme SNES
│   │   ├── data_abc/           # Données pour l'algorithme ABC
│   │   └── data_randomSearch-5/# Données pour Random Search
│   │
│   ├── figures/                # Figures générées
│   │   ├── SNES/              # Figures pour SNES
│   │   ├── figures_abc/       # Figures pour ABC
│   │   └── randomSearch-5/    # Figures pour Random Search
│   │
│   └── scripts/               # Scripts d'analyse
│       ├── scriptsSNES/       # Scripts pour SNES
│       ├── script_ABC/        # Scripts pour ABC
│       └── scriptsRandomSearch-5/ # Scripts pour Random Search
│
├── requirements.txt           # Dépendances Python
└── README.md                 # Documentation principale

## Prérequis

- Python 3.8 ou supérieur
- pip (gestionnaire de paquets Python)
- Git (pour cloner le dépôt)

## Installation

1. Clonez le dépôt :
   
2. Créez un environnement virtuel :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Linux/Mac
   # ou
   .\venv\Scripts\activate  # Sur Windows
   ```

3. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Dépendances Principales

- numpy (≥1.21.0) : Calcul numérique
- pandas (≥1.3.0) : Manipulation de données
- matplotlib (≥3.4.0) : Visualisation de données
- seaborn (≥0.11.0) : Visualisation statistique
- scikit-learn (≥0.24.0) : Algorithmes d'apprentissage automatique
- jupyter (≥1.0.0) : Environnement de développement interactif
- notebook (≥6.4.0) : Interface web pour Jupyter
- ipykernel (≥6.0.0) : Support du kernel Python pour Jupyter

## Utilisation

1. Lancez Jupyter Notebook :
   ```bash
   jupyter notebook
   ```

2. Accédez aux différents algorithmes dans leurs dossiers respectifs :
   - `scripts/scriptsSNES/` : Implémentation et analyse de SNES
   - `scripts/script_ABC/` : Implémentation et analyse de ABC
   - `scripts/scriptsRandomSearch-5/` : Implémentation et analyse de Random Search

## Gestion des Figures

Les figures sont automatiquement enregistrées dans leurs dossiers respectifs :
- Les figures de SNES sont sauvegardées dans `figures/SNES/`
- Les figures de ABC sont sauvegardées dans `figures/figures_abc/`
- Les figures de Random Search sont sauvegardées dans `figures/randomSearch-5/`

Chaque algorithme gère automatiquement l'enregistrement de ses figures dans le dossier approprié, vous n'avez pas besoin de spécifier manuellement le chemin de sauvegarde.

## Structure des Données

Les données sont organisées par algorithme :
- `data/data_SNES/` : Données pour l'algorithme SNES
- `data/data_abc/` : Données pour l'algorithme ABC
- `data/data_randomSearch-5/` : Données pour Random Search

## Structure des Figures

Les figures sont organisées par algorithme :
- `figures/SNES/` : Figures pour SNES
- `figures/figures_abc/` : Figures pour ABC
- `figures/randomSearch-5/` : Figures pour Random Search

