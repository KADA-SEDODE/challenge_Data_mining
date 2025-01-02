Prévision de la Désaffection Bancaire

Ce projet a été réalisé dans le cadre d'un challenge Kaggle lors du cours de Data Mining en Master 2 Modélisation Statistique, Économique et Financière (M2 MOSEF) à l'université Paris 1 panthéon Sorbonne. 
L'objectif était de construire un modèle performant pour prédire le taux de désabonnement bancaire (churn). Notre équipe a terminé 4ème lors de ce challenge.

Ce projet a été réalisé par : effoliguift@outlook.com   , bethuelasse9@gmail.com , kadasedodemarv@gmail.com 


1. Contexte
   
La désaffection des clients (churn) est un problème stratégique pour le secteur bancaire.
 Ce projet vise à identifier les clients à risque et à proposer des solutions préventives en utilisant des techniques avancées de machine learning.

3. Structure du projet
   
.codegpt/ : Dossier généré pour des configurations spécifiques à l'éditeur.
.venv/ : Environnement virtuel Python pour les dépendances du projet (non suivi par Git grâce à .gitignore).
catboost_info/ : Dossier contenant les logs générés par CatBoost.
data/ :
train.csv : Fichier de données d'entraînement.
test.csv : Fichier de données de test.
.gitignore : Exclut les fichiers et dossiers sensibles du suivi Git.
catboost_final.ipynb : Notebook principal contenant l'analyse exploratoire, la modélisation et l'évaluation.
requirements.txt : Liste des dépendances Python nécessaires pour reproduire le projet.

4. Fonctionnalités principales

Analyse exploratoire des données (EDA) pour comprendre les facteurs clés du churn.
Implémentation et optimisation des modèles de machine learning, dont :
CatBoostClassifier
XGBoostClassifier
LightGBMClassifier
Utilisation d'Optuna pour l'optimisation des hyperparamètres.
Évaluation des modèles avec des métriques comme le ROC AUC et la matrice de confusion.


5. Comment utiliser ce projet

git clone https://github.com/KADA-SEDODE/challenge_Data_mining.git
cd challenge_Data_mining

Créez un environnement virtuel et activez-le
python -m venv .venv
source .venv/bin/activate      # Sur Linux/Mac
.venv\Scripts\activate         # Sur Windows

Installez les dépendances :
pip install -r requirements.txt


Lancez le notebook principal 
jupyter notebook catboost_final.ipynb



