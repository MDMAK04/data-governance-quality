# 🏢 GlobalStore — Data Governance & Data Quality

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Description
Mise en place d'un système complet de **Data Governance** et **Data Quality** 
sur les données de ventes mondiales de GlobalStore Inc.

## 🎯 Objectifs
- Définir les rôles et règles de Data Governance
- Détecter et corriger les problèmes de qualité
- Appliquer les 6 dimensions de Data Quality
- Assurer la traçabilité des modifications

## 📁 Structure
```text
📦 data-governance-quality
┣ 📂 data
┃ ┣ 📄 dirty_superstore.csv
┃ ┗ 📄 cleaned_superstore.csv
┣ 📂 notebooks
┃ ┗ 📓 data_governance.ipynb
┣ 📂 reports
┃ ┗ 📄 tracabilite.csv
┣ 📂 images
┗ 📄 README.md
```
## 🔍 Problèmes détectés
| Problème | Impact |
|---|---|
| Doublons | 1313 lignes |
| Valeurs unknown | 5385 lignes |
| Outliers Quantity=9999 | 2693 lignes |
| Dates incohérentes | 3231 lignes |
| Mauvais formats | Sales, Profit, Dates |

## ✅ Résultats
| Étape | Avant | Après |
|---|---|---|
| Dataset initial | 53854 lignes | — |
| Suppression doublons | 53854 | 52541 |
| Suppression unknown | 52541 | 47167 |
| Suppression outliers | 47167 | 44763 |
| Dates incohérentes | 44763 | 32404 |
| **Dataset final** | — | **32404 lignes** |

## 📊 Règles Data Quality
- ✅ Sales > 0
- ✅ Quantity entre 1 et 100
- ✅ Ship Date >= Order Date
- ✅ 0 doublons
- ✅ Formats corrects

## 🛠️ Outils
- Python 3.13 — Pandas, Matplotlib, Seaborn
- Jupyter Notebook
- Power BI
- Git & GitHub

## 👨‍🎓 Auteur
**El Makhloufi Mohammed** — Master ML/AI  
Université Sidi Mohamed Ben Abdallah, Fès
