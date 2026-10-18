# Puissance 4 — version 2

Deuxième version du projet : un moteur de jeu graphique et plusieurs joueurs contrôlés par des robots Python.

## Prérequis

- Python 3.10 ou une version ultérieure
- Tkinter (inclus avec la plupart des installations Python sous Windows)
- Pygame

Installation de Pygame :

```powershell
python -m pip install pygame
```

## Lancer le jeu

Depuis ce dossier, lancer d’abord la fenêtre de configuration et sélectionner le fichier Python de chaque robot :

```powershell
python configP4TkV2.py
```

La configuration génère `IA1.py` et `IA2.py` dans le dossier courant. Ensuite, lancer le moteur graphique :

```powershell
python puissance4moteur.py
```

Les fichiers `IA1.py` et `IA2.py` sont générés localement et ne sont pas versionnés.
