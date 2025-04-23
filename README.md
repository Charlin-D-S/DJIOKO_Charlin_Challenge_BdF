# 📊 Challenge Banque de France 2025 – Analyse Économique et Modélisation

## 🔍 Objectif

Ce projet a été réalisé dans le cadre du **Challenge Banque de France**, dont l’objectif était de :

- Analyser le lien entre le **solde TARGET2** et les **composantes de la balance des paiements**.
- Étudier les comportements bancaires relatifs à la **facilité de dépôt (FD)** dans l’Eurosystème.
- Proposer une modélisation économétrique et une réflexion économique fondée sur les données fournies par la Banque de France et la BCE.

## 🧰 Contenu du projet

Le répertoire contient :

- `rapport_final.tex` : Rapport en LaTeX avec graphiques et analyses.
- `references.bib` : Bibliographie du rapport.
- `scripts/`
  - `partie1_modele_target2.Rmd` : Analyse descriptive et modélisation ARDL du solde TARGET2.
  - `partie2_fd_et_remuneration.R` : Analyse de la facilité de dépôt et calcul des rémunérations journalières.
- `donnees/` : Fichiers CSV utilisés.
- `base_finale.csv` : Base nettoyée avec rémunération journalière calculée.

## 📈 Méthodologie

### Partie 1 : TARGET2 et Balance des paiements

- Séries utilisées : solde TARGET2, transactions courantes, investissements directs, autres investissements.
- Tests de stationnarité (ADF) et vérification de cointégration (test de Pesaran).
- Modélisation ARDL : estimation de la relation de court terme entre TARGET2 et les composantes de la balance des paiements.

### Partie 2 : Facilité de dépôt

- Visualisation par pays et par banque.
- Calcul de la rémunération FD journalière :  
  `Rémunération = Montant FD × Taux BCE / 365`
- Corrélation avec la politique monétaire de la BCE.

## 📎 Sources

- Banque de France Webstat : [https://webstat.banque-france.fr](https://webstat.banque-france.fr)
- BCE Statistical Data Warehouse : [https://data.ecb.europa.eu](https://data.ecb.europa.eu)

## 👤 Auteur

**Charlin DJIOKO**  
Master Data Science & Finance  
ENSAI 

