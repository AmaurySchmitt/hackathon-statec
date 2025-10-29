# Hackathon STATEC : Architecture Solution

## 1. Présentation du projet

Ce projet propose une architecture légère et réactive pour la **visualisation et l’analyse des données économiques du Luxembourg de façon simple et vulgarisée**, en s’appuyant sur les datasets de la STATEC.  
Objectif : permettre aux utilisateurs de poser des questions liées à l’économie luxembourgeoise et d’obtenir des réponses assistées par l’IA, tout en visualisant les indicateurs clés via un dashboard interactif.

### Principales briques :
- **Dashboard** : Visualisation des indicateurs et graphiques économiques par thème (finance, démographique et territoire), si besoin extensible.
- **Indice explicatif** : Facilite la compréhension des thématiques économiques.
- **Assistant IA** : Répond aux questions de l'utilisateur grâce à un modèle GPT connecté à PowerBI pour orchestrer tout type de conversation autour de la donnée.

---

## 2. Pourquoi ce projet est important pour la STATEC

- **Clarification et accessibilité** : Rend les statistiques publiques plus compréhensibles, accessible et visuelles.
- ****: Faciliter l'utilisation de l'IA autour des données.
- **Coût optimisé** : Toute l'architecture peut être consdtruite avec des compoosants open-source et gratuit (dashboard en python, moteur de workflow N8N local et gratuit, GenAI open-source).
- **Modularité et rapidité** : Briques indépendantes, mise en œuvre décentralisée, sans infrastructure lourde. Développement du dashboard indépendant du moteur workflow et de l'IA.

---

## 3. Comment exécuter le projet

### Prérequis techniques
- **Datasets STATEC** : Disponibles localement.
- **Front-end** : Local, sans serveur ni API externe.
- **Middleware** : N8N (24€/mois) pour gérer les flux (possible en no-code).
- **IA** : API OpenAI (coût ≈ 0,01€ par requête).

### Outils recommandés
- **Microsoft PowerBI** : Dashboard.
- **Microsoft PowerApps** : Champ de saisie.
- **Microsoft PowerAutomate** : Orchestration des flux.
- **N8N** : Middleware léger.
- **OpenAI API** : Assistant IA.

### Étapes
1. Créer les comptes (OpenAI, N8N).
2. Élaborer un PMV.
3. Tester et valider.

---

## 4. Principes à respecter
- Architecture légère et modulaire.
- Minimisation des appels de données.
- Maximisation de la gratuité + pay-per-use.
- Standardisation des flux.
- Décentralisation (low/no-code).
- Éviter VM, middleware centralisé, full cloud.

---

**Auteur : Hackathon STATEC – EY Teams**  
© 2025 Ernst & Young S.A.
