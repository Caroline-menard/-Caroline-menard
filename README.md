# -Caroline-menard
<p align="right">
  <img src="https://github.com/Caroline-menard/-Caroline-menard/blob/main/logo_blanc.png?raw=true" alt="Logo Caroline Ménard" width="160">
</p>

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

# 1- Amazon Review Classifier & Dashboard

👉 [Découvrir le projet sur GitHub](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard)

**Classification** automatique d’avis clients et visualisation interactive via **Streamlit**.

Ce projet NLP détecte plusieurs typologies de problèmes dans des revues Amazon (produit endommagé, non conforme, etc.) grâce à une pipeline combinant TF-IDF, features sémantiques, et XGBoost.

Résultats explorables dans un dashboard, avec filtres, graphiques et export de données.

## Compétences mobilisées dans ce projet
*Traitement automatique du langage (NLP) :*
> — Nettoyage et préparation de texte, TfidfVectorizer, Réduction de dimension avec TruncatedSVD.

*Machine Learning multi-label :*
> — Construction d’un pipeline scikit-learn modulaire.<br>
> —  Entraînement et validation croisée (GridSearchCV).

*Feature engineering :*
> — Création de features via FunctionTransformer<br>
> — classes personnalisées de preprocessing et post-processing.

*Manipulation de données:*
> — Avec pandas,numpy <br>
> — Fichiers parquet optimisés pour le stockage.

*Data Engineering (light) :*
> — Interaction avec une base PostgreSQL hébergée sur Supabase.<br>
> —  Scripts d’ETL pour l’insertion et la mise à jour des prédictions.

*Visualisation et restitution interactive :*
> — Création d’un dashboard interactif Streamlit.<br>
> — Visualisation de résultats, filtres dynamiques, export de données.

*Déploiement :*
> — Hébergement du dashboard sur Streamlit Cloud.<br>
> — Optimisation des requirements.txt pour la compatibilité serveur.

*Organisation projet / bonnes pratiques :*
> — Modularisation des scripts (prediction, ETL, orchestration).<br>
> —  .gitignore propre, README détaillé, visualisation d’architecture.<br>
> — Référencement clair des dépendances et workflow reproductible.<br>
> - 🧘 Patience et ténacité, indispensables pour dompter les caprices de Streamlit Cloud à 2h du mat’.
