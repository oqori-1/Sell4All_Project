# Projet de sélection – Exploration de données avec Python

## Présentation

Ce projet a été réalisé dans le cadre du processus de sélection du parcours **Développement en Intelligence Artificielle** de YouCode.

L'objectif est d'explorer et de nettoyer un jeu de données clients de l'entreprise fictive **Sell4All** afin de préparer les données pour une future fonctionnalité de recommandation basée sur l'intelligence artificielle.

---

## Objectifs du projet

Les tâches réalisées sont les suivantes :

- Lire le fichier CSV avec Pandas.
- Explorer les données.
- Afficher un résumé technique des données.
- Calculer la moyenne et la médiane.
- Calculer la médiane de l'âge par pays (bonus).
- Créer un graphique des dépenses par pays.
- Nettoyer les données.
- Exporter les données nettoyées dans un nouveau fichier CSV.

---

## Étapes de réalisation

### Jour 1
- Installation de Miniconda.
- Installation de Jupyter Notebook.
- Installation des bibliothèques Pandas et Matplotlib.
- Lecture du fichier CSV.
- Première exploration des données.

### Jour 2
- Analyse du jeu de données.
- Calcul des statistiques (moyenne et médiane).
- Création du graphique des dépenses par pays.

### Jour 3
- Nettoyage des données.
- Suppression des doublons.
- Suppression des clients ayant dépensé moins de 10 €.
- Export des données nettoyées.
- Organisation du notebook et rédaction du README.

---

## Fonctionnalités développées

- Importation des données avec Pandas.
- Exploration des données.
- Analyse statistique.
- Visualisation avec Matplotlib.
- Nettoyage des données.
- Export des données finales au format CSV.

---

## Difficultés rencontrées

Pendant la réalisation de ce projet, plusieurs difficultés ont été rencontrées :

- Comprendre certaines fonctions de Pandas comme `groupby()` et `drop_duplicates()`.
- Comprendre les informations affichées par `data.info()`.
- Organiser le notebook de manière claire.

### Solutions

- Consultation de la documentation officielle de Pandas.
- Utilisation des ressources fournies dans le sujet.
- Réalisation de plusieurs tests afin de mieux comprendre le comportement des fonctions.

---

## Structure du projet

```
project/
│
├── dataset-sell4all.csv
├── dataset-sell4all-clean.csv
├── main.ipynb
├── README.md
```

---

## Prérequis

Avant d'exécuter le projet, il faut disposer de :

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib

---

## Installation

Installer les bibliothèques :

```bash
pip install pandas matplotlib
```

ou avec Conda :

```bash
conda install pandas matplotlib
```

---

## Exécution

1. Ouvrir un terminal.
2. Se placer dans le dossier du projet.
3. Lancer Jupyter Notebook.

```bash
jupyter notebook
```

4. Ouvrir le fichier `main.ipynb`.
5. Exécuter les cellules dans l'ordre.

---

## Résultat

À la fin de l'exécution, un nouveau fichier est généré :

```
dataset-sell4all-clean.csv
```

Ce fichier contient uniquement les colonnes demandées après le nettoyage des données.

---

## Technologies utilisées

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Auteur

Projet réalisé dans le cadre du processus de sélection YouCode.