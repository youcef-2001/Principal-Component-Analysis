## Projet de Machine Learning    PCA

### Le contexte 

Vous êtes un data scientist pour un client (fictif ou non) et vous devez présenter une analyse de données complètes, de la spécification des besoins, élaboration d'une problématique pertinente ainsi qu'une mise en oeuvre technique respectant les conditions ci-dessous. 

### Le livrable 

**Jupyter notebook** avec les datas (ou liens raw git ? kaggle pour accéder aux datas si > 5Mo)
le travail devra être déposé sur un gist et l’étudiant devra envoyer le lien par mail ou messagerie


#### Contraintes 

- Data avec minimum 8 à 10 colonnes avec au moins une colonne représentant une date
- Un maximum de commentaires dans le code
- Texte type Markdown après chaque graphique/tableau (ex: description textuelle des features après chargement)
- Tous les graphiques doivent être lisible (taille du graphique, infos représenté), si diagramme pas lisible, en faire une version filtrée dessous
- Exposer concrètement votre problématique / question à définir : quel est le but de votre modèle et à quelle situation métier peut il correspondre ?

#### Partie 1 : Analyse graphique des données (EDA)

Diagrammes de répartition des données (type gaussienne sur les données)
Vérification du nombre de données, si plusieurs données sont peu représentés (<3%) alors regrouper dans une seule et même catégorie, 1 pie chart avant/apres
Nettoyage des données manquantes, encodage (OneHot, dictionnaire ou Sklearn Encoder)
Boites à moustache avec données extrêmes si besoin 
Heatmap + observations sur les corrélations


#### Partie 2: Model Building

Utiliser un algorithme la librairie sklearn avec 3 paramètres différents (ex dans le cadre de l’algorithme random forest: max_depth, n_estimators,….)
Affichage des metrics de votre model : coefficients/ accuracy / confusion matrix …  
Sélection du meilleur paramétrage si le temps vous le permet
Le model est-il en overfitting/underfitting/OK expliquer votre raisonnement ?
#### Partie 3 : Implementation from scratch 

Implementer votre algorithme en python basique et expliquer le pseudo code 
Livraison sur git avec documentation, tests et README EXPLICITE qui résume votre projet et les principales commandes pour le lancer
 

 
### Présentation orale 
 
Ci dessous les consignes de votre présentation orale. 
 
**Le support** : Jupyter notebook ou PPT 
 
#### Le barème indicatif : 

Compréhension du sujet (5points)
Synthèse pertinente du sujet et explication simple 
Phrases et légendes personnelles (non recopiées ou « copiées-collées ») 
Choix pertinent des illustrations variées (photo, graphique, schéma...)  

Structure de l’exposé (5points)
Annonce du plan
Introduction, problématique et conclusion 
Présentation des graphiques

Présentation technique (10points)
Définitions et vocabulaire précis 
Avoir un jeu de données originale 
Concepts techniques présenté(s) et expliqué(s) 
Le pseudo code est compris et expliqué clairement avec un/des examples simples
Identification des applications et besoin métier associé au sujet 
Perspectives d'évolutions 


- Prof **Benjamin Dallard**
- Ecole H3Hitema  2024/2025
