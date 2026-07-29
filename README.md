# Projet de sélection — Exploration de données avec Python

## Présentation

Ce projet a été réalisé dans le cadre du processus de sélection du parcours **Développement en Intelligence Artificielle** de YouCode.

L'objectif est d'explorer, d'analyser et de nettoyer les données clients de l'entreprise fictive **Sell4All** afin de préparer ces données pour une future utilisation dans un projet d'intelligence artificielle.

---

# Objectifs du projet

Les principales tâches réalisées sont :

- Lire le fichier CSV avec Pandas.
- Explorer le jeu de données.
- Afficher un résumé technique des données.
- Calculer la moyenne et la médiane.
- Calculer la médiane de l'âge par pays (Bonus).
- Créer un graphique des dépenses des clients par pays.
- Nettoyer les données.
- Exporter les données nettoyées dans un nouveau fichier CSV.

---

# Étapes de réalisation

### Jour 1

- Installation de Miniconda.
- Installation de Jupyter Notebook.
- Installation des bibliothèques Pandas et Matplotlib.
- Lecture du fichier CSV.
- Première exploration des données.

### Jour 2

- Analyse des données.
- Calcul de la moyenne et de la médiane.
- Calcul de la médiane de l'âge par pays.
- Création du graphique des dépenses par pays.

### Jour 3

- Nettoyage des données.
- Suppression des doublons.
- Export du fichier CSV nettoyé.
- Vérification des résultats.
- Organisation du notebook et rédaction du README.

---

# Fonctionnalités développées

- Importation des données avec Pandas.
- Exploration des données.
- Analyse statistique.
- Visualisation avec Matplotlib.
- Nettoyage des données.
- Export des données finales.

---

# Difficultés rencontrées

Je n'ai pas rencontré de difficultés majeures pendant la réalisation du projet.

Pour mieux comprendre chaque étape, j'ai pris le temps de lire les consignes, de tester les fonctions utilisées et de vérifier les résultats obtenus avant de passer à l'étape suivante.

---

# Structure du projet

```text
sell4all-project/
│
├── dataset-sell4all.csv
├── dataset-sell4all-clean.csv
├── main.ipynb
└── README.md
```

---

# Environnement de développement

Le projet a été réalisé sous **Linux**.

Outils utilisés :

- Linux
- Python
- Miniconda
- Jupyter Notebook
- Pandas
- Matplotlib
- Git
- GitHub

---

# Installation

## 1. Cloner le dépôt

```bash
git clone <git@github.com:oqori-1/Sell4All_Project.git>
```

## 2. Accéder au dossier du projet

```bash
cd sell4all-project
```

## 3. Créer un environnement Conda

```bash
conda create -n sell4all python=3.13
```

## 4. Activer l'environnement

```bash
conda activate sell4all
```

## 5. Installer les bibliothèques nécessaires

```bash
conda install pandas matplotlib notebook
```

## 6. Lancer Jupyter Notebook

```bash
jupyter notebook
```

Puis ouvrir le fichier :

```text
main.ipynb
```

et exécuter les cellules dans l'ordre.

---

# Résultat

Après l'exécution du notebook, un nouveau fichier est généré :

```text
dataset-sell4all-clean.csv
```

Ce fichier contient uniquement les colonnes suivantes :

- Country
- Age
- Gender
- Customer spendings

Les données ont été nettoyées conformément aux consignes du projet.

---

# Technologies utilisées

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Git
- GitHub
- Linux

---

# Auteur

Projet réalisé dans le cadre du processus de sélection du parcours **Développement en Intelligence Artificielle** de **YouCode**.
