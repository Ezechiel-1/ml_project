# 🧠 Projet Machine Learning – Analyse et Prédiction sur Données League of Legends

Ce projet vise à analyser un ensemble de données provenant de parties de **League of Legends**, et à construire des modèles de Machine Learning permettant de faire de la **prédiction** sur différents événements clés des matchs.

Les données sont constituées de plusieurs tables contenant :
- des informations sur les champions,
- des statistiques détaillées des joueurs,
- des informations globales sur les matchs,
- des données de rang des joueurs,
- des données agrégées au niveau des équipes.

---

## 🎯 Objectifs du Projet

1. **Explorer et nettoyer les données**
   - Comprendre la structure des différentes tables.
   - Identifier les colonnes utiles.
   - Fusionner les tables pertinentes.
   - Traiter les valeurs manquantes et les incohérences.

2. **Construire un ensemble de données exploitable**
   - Feature engineering (gold/min, dmg/min, vision score, etc.).
   - Encodage des variables catégorielles.
   - Agrégation par joueur ou par équipe selon l'objectif choisi.

3. **Modéliser**
   Selon l’objectif retenu (choix final à valider) :

   ### Option A – *Prédiction de victoire d'une équipe*
   - Entrée : stats globales équipe (dragons, barons, kills, tourelles, etc.).
   - Sortie : `BlueWin` ou `RedWin`.

   ### Option B – *Prédiction de la performance d’un joueur*
   - Entrée : champion, rôle, niveau, items, etc.
   - Sortie : dégâts, KDA, gold/min, autres métriques.

4. **Évaluer les modèles**
   - Train/Test Split
   - Accuracy, F1, ROC-AUC, etc.
   - Analyse des features importantes.

---

## 📂 Structure du Projet

