# 🏦 Prévision de la Désaffection Bancaire (Churn)

## 📌 Présentation

Ce projet a été réalisé dans le cadre d’un **challenge Kaggle** du cours de **Data Mining** en **Master 2 Modélisation Statistique, Économique et Financière (M2 MOSEF)** à l’Université **Paris 1 Panthéon-Sorbonne**.  

🎯 **Objectif** : Construire un modèle performant pour prédire le **désabonnement bancaire (churn)**.  
🏅 Notre équipe a terminé **4ᵉ sur l’ensemble des participants.**

👥 **Projet réalisé par** :
- kadasedodemarv@gmail.com
- effoliguift@outlook.com
- bethuelasse9@gmail.com

---

## 📝 Contexte

La **désaffection des clients (churn)** est un enjeu stratégique majeur pour les banques, impactant directement la rentabilité et la fidélité des clients.  

Ce projet vise à :
- **Identifier les clients à risque de churn**
- **Proposer des solutions préventives basées sur les prédictions du modèle**
- Utiliser des **techniques avancées de machine learning** pour améliorer la précision de prédiction.

---

## 📂 Structure du projet

| Dossier/Fichier           | Description                                                        |
|--------------------------|--------------------------------------------------------------------|
| `.venv/`                  | Environnement virtuel Python (non suivi par Git grâce à `.gitignore`) |
| `catboost_info/`          | Logs générés par CatBoost                                          |
| `data/train.csv`          | Données d’entraînement                                             |
| `data/test.csv`           | Données de test                                                    |
| `.gitignore`              | Exclut les fichiers sensibles ou inutiles                          |
| `catboost_final.ipynb`    | Notebook principal (EDA, modélisation, évaluation)                 |
| `requirements.txt`        | Liste des dépendances Python du projet                             |

---

## 🚀 Fonctionnalités principales

✅ **Analyse exploratoire des données (EDA)** pour identifier les facteurs clés du churn  
✅ **Modélisation** avec plusieurs algorithmes de machine learning, dont **CatBoostClassifier**  
✅ **Optimisation des hyperparamètres** avec **Optuna**  
✅ **Évaluation des modèles** avec des métriques comme :
- **ROC AUC**
- **Matrice de confusion**

---

## 🛠️ Guide d’utilisation

1️⃣ **Clonez le projet :**

```bash
git clone https://github.com/KADA-SEDODE/challenge_Data_mining.git
cd challenge_Data_mining
2️⃣ Créez et activez un environnement virtuel :
python -m venv .venv
source .venv/bin/activate      # Sur Linux/Mac
.venv\Scripts\activate         # Sur Windows
3️⃣ Installez les dépendances :
pip install -r requirements.txt
4️⃣ Lancez le notebook principal :
jupyter notebook catboost_final.ipynb

✨ Notes

Ce projet a été développé dans un cadre académique, avec une approche pratique orientée compétition et optimisation.

Pour toute question ou contribution, n’hésitez pas à ouvrir une issue ou un pull request.


---

## ✅ **Améliorations apportées :**
- Meilleure mise en page avec des emojis et titres hiérarchisés
- Explications plus **fluides et pro**
- Instructions terminal **mieux mises en valeur**
- Tableau pour la structure (au lieu de texte brut)
- Ajout d’une section "Notes" pour la finition

---
