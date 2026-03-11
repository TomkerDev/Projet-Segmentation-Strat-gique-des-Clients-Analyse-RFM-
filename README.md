# 🛒 Segmentation Client E-Commerce (Analyse RFM & K-Means)

## 📌 Présentation du Projet
Ce projet de **Data Mining** vise à analyser le comportement d'achat des clients d'un site de vente en ligne (Dataset: *Online Retail*). L'objectif est de segmenter la base client pour optimiser les stratégies marketing.

## 🚀 Méthodologie
L'analyse repose sur le modèle **RFM** (Récence, Fréquence, Montant) et l'algorithme de clustering **K-Means**.

### Étapes clés :
1. **Nettoyage des données** : Gestion des valeurs manquantes et suppression des retours de commandes.
2. **Ingénierie des caractéristiques** : Calcul des scores R, F et M par client.
3. **Prétraitement** : Transformation logarithmique et normalisation (StandardScaler) pour stabiliser la variance.
4. **Clustering** : Utilisation de la méthode du "Coude" (Elbow Method) pour définir le nombre optimal de segments.
5. **Interprétation** : Identification des profils types (ex: Champions, Clients à risque, Nouveaux clients).

## 🛠️ Technologies utilisées
* **Python 3.10+**
* **Pandas & NumPy** : Manipulation des données.
* **Scikit-Learn** : Algorithme K-Means et mise à l'échelle.
* **Matplotlib & Seaborn** : Visualisation des segments.

## 📊 Résultats
Les clients ont été segmentés en 4 groupes distincts permettant des actions ciblées :
- **Segment 1 (Or)** : Clients fidèles dépensant beaucoup -> Programme de fidélité VIP.
- **Segment 2 (À risque)** : Anciens clients qui ne commandent plus -> Campagnes de réactivation.
- ...

## 📁 Structure du Repo
- `data/` : Lien vers le dataset original.
- `notebook.ipynb` : Analyse complète et commentée.
- `requirements.txt` : Liste des dépendances.
