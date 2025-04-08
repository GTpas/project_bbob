# Projet BBOB

## Installation

Pour installer les dépendances nécessaires au projet, suivez ces étapes :

1. Assurez-vous d'avoir Python 3.8 ou supérieur installé sur votre système
2. Créez un environnement virtuel (recommandé) :
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

## Structure du Projet

- `scripts/` : Contient les notebooks Jupyter pour l'analyse des données
- `data/` : Contient les données du projet
- `figures/` : Contient les figures relatif aux algorithmes 

## Utilisation

Pour lancer Jupyter Notebook :
```bash
jupyter notebook
```