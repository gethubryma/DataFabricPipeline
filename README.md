

# DataFabric

## Description
DataFabric est un projet de data engineering qui met en place un pipeline de traitement de données complet en utilisant Microsoft Fabric.

Le projet suit une architecture moderne basée sur le modèle Lakehouse avec trois niveaux :

- Bronze : ingestion des données brutes depuis des fichiers CSV
- Silver : nettoyage, transformation et validation des données avec PySpark
- Gold : modélisation des données sous forme de schéma en étoile pour l’analyse

Les données sont ensuite exploitées dans Power BI pour créer des tableaux de bord interactifs et des indicateurs clés (KPI).

---

## ⚙️ Technologies utilisées
- Python
- PySpark
- Microsoft Fabric
- Lakehouse (Bronze / Silver / Gold)
- ETL Pipeline
- Power BI
- DAX

---

## 📁 Structure du projet

```

.
├── src/            # Code source
├── data/           # Données
├── captures/       # Screenshots / résultats
├── README.md
└── rapport.pdf

````

---

##  Lancement

```
# Installer les dépendances
pip install -r requirements.txt

# Lancer le projet
python main.py
````

---

##  Objectif

Ce projet illustre la mise en œuvre d’un pipeline ETL complet :

* ingestion des données dans un Lakehouse
* transformation et nettoyage avec PySpark
* modélisation en étoile (fact table + dimensions)
* création d’un modèle sémantique
* calcul de métriques avec DAX
* visualisation des données avec Power BI
* orchestration des traitements via un pipeline automatisé

L’objectif est de reproduire une architecture de données moderne utilisée en entreprise pour l’analyse et la prise de décision

---

##  Résultats

Voir le dossier `captures/` pour les résultats du projet.

---

## 📘 Rapport

Le rapport détaillé est disponible dans le fichier PDF du projet.

