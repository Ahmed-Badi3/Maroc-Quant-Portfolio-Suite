# Maroc-Quant-Portfolio-Suite
Maroc Quant Portfolio Suite: A quantitative portfolio optimization and risk management suite for the Casablanca Stock Exchange (ATW.MA, BCP.MA, IAM.MA, LHM.MA, MNG.MA vs MASI). Features Markowitz Monte-Carlo simulations, 30% concentration constraint, VaR, stress testing, 3-year backtesting, and an interactive Power BI dashboard.
# 🇲🇦 Maroc Quant Portfolio Suite

> **Laboratoire d'Optimisation Quantitative et de Gestion des Risques pour la Bourse de Casablanca**

## 📌 Présentation du Projet
**Maroc Quant Portfolio Suite** est une solution complète d'ingénierie financière et d'allocation d'actifs conçue pour analyser, optimiser et piloter des portefeuilles d'actions sur le marché financier marocain (Bourse de Casablanca). 

Le projet combine des méthodes quantitatives avancées sous **Python**, une modélisation rigoureuse des risques et un tableau de bord décisionnel interactif sous **Power BI** destiné aux comités d'investissement.

---

## 🛠️ Périmètre & Actifs Financiers
Le modèle intègre un panier diversifié représentatif des poids lourds de la cote marocaine :
* **ATW.MA** (Attijariwafa bank - Secteur Bancaire)
* **BCP.MA** (Banque Centrale Populaire - Secteur Bancaire)
* **IAM.MA** (Maroc Telecom - Télécommunications)
* **LHM.MA** (LafargeHolcim Maroc - Industrie / BTP)
* **MNG.MA** (Managem - Mines)
* **Benchmark** : Indice **MASI** (Moroccan All Shares Index).

---

## 🚀 Fonctionnalités Clés
1. **Optimisation de Markowitz & Monte-Carlo** : Simulation de 10 000 portefeuilles pour tracer la frontière efficiente et déterminer le portefeuille **Max Sharpe** et **Minimum Variance**.
2. **Gouvernance & Contraintes Institutionnelles** : Application d'un plafond strict de **30% d'exposition maximale par actif** pour limiter le risque de concentration sectorielle.
3. **Analyse Avancée des Risques** : 
   * Calcul de la **VaR (Value-at-Risk) 95% 1-Jour**.
   * Simulation de **Stress Tests** sur des scénarios de choc de marché (-10% à -20%).
   * Matrice de corrélation croisée inter-sectorielle.
4. **Backtest Historique & Performance** : Simulation de performance cumulée sur une base de départ de **100 000 MAD** (2023-2026) avec mesure de surperformance nette face au MASI.
5. **Dashboard Power BI Interactif** : Restitution visuelle sous forme de courbes de backtest, heatmap de corrélation et histogrammes de répartition du capital.

---

## 📊 Aperçu des Résultats & KPIs
* **Valeur Finale du Portefeuille (Base 100k MAD)** : 161,63K MAD
* **Surperformance vs Indice MASI** : +59% sur la période de test.
* **Allocation Max Sharpe (Contraint 30%)** : Saturation du plafond sur Managem (30%), surpondération de LafargeHolcim (~27%) et Attijariwafa bank (~23%).

---

## ⚙️ Technologies & Outils
* **Python (Pandas, NumPy, SciPy, Matplotlib)** : Moteur de calcul quantitatif, simulations et génération du rapport Word institutionnel.
* **Power BI & DAX** : Modélisation des données relationnelles et création du tableau de bord décisionnel.
* **Bureautique** : Automatisation des exports CSV et intégration des métriques de marché.

---
*Développé dans le cadre de travaux en ingénierie financière et analyse de données boursières.*
