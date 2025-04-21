# 📊 Analyse des Données E-commerce : Rapport de Ventes et Retours

---

## 📝 Introduction

Ce projet analyse un ensemble de données e-commerce pour :
- Identifier les **tendances des ventes**
- Analyser les **performances par catégorie de produits**
- Évaluer les **taux de retour**
- Étudier l’impact du **temps de livraison** sur les retours  

🎯 **Objectif** : Aider à la prise de décisions éclairées pour optimiser les ventes et réduire les retours.

---

## 🎯 Objectifs

- 📦 Identifier les catégories de produits les plus performantes  
- 📈 Analyser les tendances saisonnières des ventes  
- 🔁 Évaluer les taux de retour par produit et pays  
- ⏱ Étudier l’impact du temps de livraison sur les retours  
- 💡 Proposer des recommandations stratégiques  

---

## 🗂 Données

- **Colonnes** : Order ID, Customer Name, Product Category, Product Name, Order Date, Delivered Date, Quantity, Unit Price, Status, Country, Payment Method, Year, Month, Day Name  
- **Période couverte** : 2024 à 2025  
- **Catégories** :
  - 📱 Électronique
  - 📚 Livres
  - 👕 Vêtements
  - 🥫 Épicerie
  - 🏺 Décoration intérieure
- **Pays** : Australie 🇦🇺, Nigeria 🇳🇬, Royaume-Uni 🇬🇧, États-Unis 🇺🇸, Chine 🇨🇳  
- **Taille** : 554 lignes

---

## 🧹 Méthodologie

- **Power Query** : Nettoyage des doublons, gestion des valeurs manquantes, formatage des dates  
- **Power Pivot** : Modélisation relationnelle  
- **DAX** : Calcul des métriques clés (ventes, marges, retours)  
- **T-Test** : Analyse de l’impact des délais sur les retours  
- **Excel** : Dashboards et visualisations

---

## 📊 Résultats Principaux

### 1. 🛍 Ventes par Catégorie

- 💰 **Total des Ventes** : $57,928 (+15%)
- 💸 **Coût Total** : $38,550
- 🏦 **Profit Net** : $19,378
- 📱 **Électronique** : Plus grande part des revenus (Smartphones et Headphones)
- 👕 **Vêtements** : Quantité élevée, marges plus faibles
- 📚 **Livres** : Ventes stables, taux de retour faibles

---

### 2. 🔁 Taux de Retour

- 📉 **Global** : 48% des commandes retournées
- 🚨 **Électronique** : Taux élevé (Headphones, Smartphones)
- 🏺 **Décoration** : Lampes et vases souvent retournés
- 🌍 **Pays concernés** :
  - 🇦🇺 Australie
  - 🇳🇬 Nigeria

---

### 3. 📅 Tendances Saisonnières

- 🎄 **Pic des ventes** : 10 décembre 2024 — $10,132
- 🔙 **Retours fréquents** : Janvier (période post-Noël)

---

### 4. ⏱ Impact du Temps de Livraison

- 📊 **T-Test Résultat** :
  - **P-Value** = 0.03208 < 0.05 → impact significatif
- 📦 **Temps moyen de livraison** :
  - Commandes retournées : 7 jours
  - Commandes non retournées : 4 jours
- ⚠️ Les livraisons > 7 jours sont plus susceptibles d’être retournées

---

### 5. 📐 Statistiques Descriptives

| 🧮 Métrique       | Moyenne   | Écart-type | Min - Max       |
|------------------|-----------|------------|-----------------|
| 💵 Ventes        | 2,651.75  | 2,200.86   | 13 - 9,740      |
| 💲 Coûts Totaux  | 1,725.65  | 1,475.48   | 8 - 7,305       |
| 🏦 Profit Net    | 926.10    | 839.53     | 5 - 4,615       |
| 📦 Quantité      | 5.40      | 2.94       | 1 - 10          |
| 💰 Prix Unitaire | 496.95    | 286.96     | 10 - 998        |

---

## 📈 Visualisations

- 📊 Graphique en Barres : Ventes par catégorie
- 📈 Graphique Linéaire : Évolution mensuelle des ventes
- 🍩 Graphique en Anneau : Taux de retour par produit
- 🌍 Carte Géographique : Répartition des ventes par pays

---

## 🧠 Recommandations

- 🔧 **Réduction des retours** :
  - Améliorer les descriptions des produits (électronique, déco)
  - Réduire les délais de livraison à < 7 jours
- 🧳 **Optimisation des stocks** :
  - Prévoir des stocks renforcés en décembre (livres, vêtements)
- 📍 **Ciblage géographique** :
  - Lancer des campagnes en Australie et au Nigeria
- 🚚 **Logistique** :
  - Suivi renforcé pour garantir une livraison rapide

---

## 🛠 Outils Utilisés

- 🧮 **Excel** : Visualisation & reporting  
- 🔄 **Power Query** : Préparation des données  
- 📈 **DAX** : Mesures & KPIs personnalisés  

---

## ✅ Conclusion

Cette analyse met en lumière :
- Les **forces** : ventes solides (électronique, vêtements)
- Les **faiblesses** : retours élevés et liés au délai
- Des **axes d'amélioration** concrets pour :
  - Réduire les retours
  - Optimiser la logistique
  - Accroître la rentabilité
