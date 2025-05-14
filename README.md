# Caroline-menard
<p align="right">
  <img src="https://github.com/Caroline-menard/-Caroline-menard/blob/main/logo_blanc.png?raw=true" alt="Logo Caroline Ménard" width="160">
</p>

👉🇬🇧 [English Version](https://github.com/Caroline-menard/-Caroline-menard/blob/main/README.en.md)

---

### 👋 Salut, moi c’est Caroline

J’ai d’abord enseigné les mathématiques avant de plonger dans l’univers fascinant des données.  

Curieuse de nature et amoureuse des mots, je suis aujourd’hui data scientist spécialisée en NLP, au sein de la startup **U change**.  
Je conçois des outils qui écoutent, trient, expliquent, à partir d’un immense fouillis de données textuelles.  
Mes projets mêlent rigueur analytique, traitement du langage et sens du détail.

### 🧪 Ce portfolio présente mes projets personnels  
Parce que les projets perso nourrissent les compétences pro — et inversement.  
Explorer, apprendre, rater, réussir : ici, tout est prétexte à progresser.

> *“Once you stop learning, you start dying.”*  
> — Albert Einstein

Bienvenue dans mon monde mi-algo, mi-poésie...

---
# 1- Amazon Review Classifier & Dashboard

👉 [Découvrir le projet sur GitHub](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard)

Language:

➡️ 🇬🇧 [README English version](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard/blob/main/README.en.md)  
➡️ 🇫🇷 [README Version française](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard/blob/main/README.md)


**Classification** automatique d’avis clients et visualisation interactive via **Streamlit**.

Ce projet NLP détecte plusieurs typologies de problèmes dans des revues Amazon (produit endommagé, non conforme, etc.) grâce à une pipeline combinant TF-IDF, features sémantiques, et XGBoost.

Résultats explorables dans un dashboard, avec filtres, graphiques et export de données.

## Compétences mobilisées dans ce projet
*Traitement automatique du langage (NLP) :*
> - Nettoyage et préparation de texte, TfidfVectorizer, Réduction de dimension avec TruncatedSVD.

*Machine Learning multi-label :*
> - Construction d’un pipeline scikit-learn modulaire.<br>
> -  Entraînement et validation croisée (GridSearchCV).

*Feature engineering :*
> - Création de features via FunctionTransformer<br>
> - classes personnalisées de preprocessing et post-processing.

*Manipulation de données:*
> - Avec pandas,numpy <br>
> - Fichiers parquet optimisés pour le stockage.

*Data Engineering (light) :*
> - Interaction avec une base PostgreSQL hébergée sur Supabase.<br>
> -  Scripts d’ETL pour l’insertion et la mise à jour des prédictions.

*Visualisation et restitution interactive :*
> - Création d’un dashboard interactif Streamlit.<br>
> - Visualisation de résultats, filtres dynamiques, export de données.

*Déploiement :*
> - Hébergement du dashboard sur Streamlit Cloud.<br>
> - Optimisation des requirements.txt pour la compatibilité serveur.

*Organisation projet / bonnes pratiques :*
> - Modularisation des scripts (prediction, ETL, orchestration).<br>
> -  .gitignore propre, README détaillé, visualisation d’architecture.<br>
> - Référencement clair des dépendances et workflow reproductible.<br>
> - 🧘 Patience et ténacité, indispensables pour dompter les caprices de Streamlit Cloud à 2h du mat’.

____

# 2. Customer Insight Dashboard (synthetic data)

👉 [Découvrir le projet sur GitHub](https://github.com/Caroline-menard/Customer-insight-dashboard)

Language:

➡️ 🇬🇧 [README English version](https://github.com/Caroline-menard/Customer-insight-dashboard/blob/main/README.en.md)  
➡️ 🇫🇷 [README Version française](https://github.com/Caroline-menard/Customer-insight-dashboard/blob/main/README.md)

Petit dashboard Streamlit conçu pour simuler un **outil d’analyse d’activité client**, développé à partir d’un cas réel en environnement B2B.
Les données ont été générées synthétiquement pour des raisons de confidentialité, mais l’application reproduit fidèlement les usages :
suivi d’activité, détection de signaux faibles, export de données, et génération automatique de rapports PDF pour des équipes client.

Pensé pour les **Customer Success Managers**, **responsables clients** ou **chargés de l’onboarding**, ce projet illustre comment exploiter des logs minimalistes pour mieux comprendre les besoins des utilisateurs — tout en préservant leur intimité.

## Compétences mobilisées dans ce projet et enjeux

> - Adapter une interface à un public non technique, en construisant un dashboard **clair**, **ergonomique**, et **axé métier.**
> - Optimiser les **connexions aux APIs** grâce à un système de rafraîchissement manuel et à la mise en cache locale des données au format .parquet
> - Analyser les usages clients tout en préservant leur **confidentialité**, via des logs minimalistes et une approche éthique des données
> - Générer un jeu de **données synthétique**, simulant des structures d’équipes et des profils utilisateur variés pour tester le dashboard de manière réaliste.
