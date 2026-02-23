## 1. Créer l'environnement virtuel
python -m venv .venv

## 2. Activer l'environnement virtuel 

- sur Windows

.venv\Scripts\activate 

- sur Linux

.venv\bin\activate

## 3. Installer les dépendances depuis requirements.txt
pip install -r requirements-dev.txt 

attention parfois l'IDE a un interpreteur python par défaut qui n'est pas le venv...