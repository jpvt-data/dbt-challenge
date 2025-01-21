# 🌟 ETL/ELT : DBT Introduction 🌟

Bienvenue dans le dépôt dédié à la quête **DBT Introduction**.

Cette quête est une introduction à l'outil **DBT (Data Build Tool)**, qui joue un rôle clé dans les transformations de données dans un processus ELT.

---

## 🎯 Objectifs de la quête

- ✅ Découvrir le fonctionnement et l'utilité de DBT dans le cadre des transformations de données.
- ✅ Installer et configurer DBT Core localement.
- ✅ Comprendre la structure d'un projet DBT.

---

## 📚 Contenu du dépôt

Ce dépôt contient les éléments suivants :

- **Structure du projet DBT** : Dossiers et fichiers générés après la commande `dbt init`.
- **Configuration DBT** :
  - Le fichier `dbt_project.yml`, qui contient les configurations globales du projet.
  - Un exemple de fichier `profiles.yml` pour la connexion à une base de données MySQL.
- **Scripts SQL** : Modèles de transformation et fichiers pour gérer les données.
- **Base de données MySQL** : Un script Python pour importer les données brutes dans une base MySQL via SQLAlchemy.

---

## 🚀 Instructions pour lancer le projet

### 1. Prérequis
- Python installé sur la machine.
- Une base de données MySQL installée localement.
- La bibliothèque **DBT Core** installée dans un environnement virtuel Python.

### 2. Installation

1. Créer un environnement virtuel Python :
   ```bash
   python -m venv my-dbt-env
   source my-dbt-env/bin/activate  # Mac/Linux
   .\my-dbt-env\Scripts\activate  # Windows
