# OPC_DATA_ANALYST_PROJET9
Produisez une étude de marché avec R ou Python

# Analyse des Marchés Internationaux - Projet La Poule qui Chante

## Contexte

Je travaille chez **La Poule qui Chante**, une entreprise française de l’agroalimentaire spécialisée dans les produits à base de poulet. Dans le cadre de son développement à l'international, l'entreprise souhaite identifier les groupements de pays les plus pertinents pour l'exportation de ses produits. Mon rôle en tant que Data Analyst est de réaliser une première segmentation des pays afin de proposer des cibles potentielles pour l’exportation.

Mon manager, **Patrick**, m'a confié cette mission en autonomie, me laissant le choix des données et des outils d'analyse (R ou Python). Les données de base proviennent de la **FAO (Food and Agriculture Organization)**, mais je suis libre d'incorporer des données supplémentaires, notamment pour enrichir l'analyse avec des critères PESTEL si nécessaire.

## Objectifs du Projet

1. **Préparation des Données** : Nettoyer et explorer les données de la FAO sur les **balances alimentaires** pour obtenir une vue claire des caractéristiques des pays et des indicateurs alimentaires.
   
2. **Segmentation des Pays** : Utiliser des techniques de clustering pour identifier les groupes de pays avec des caractéristiques similaires. Cette segmentation aidera à cibler les marchés potentiels pour l'expansion internationale de l’entreprise.

3. **Comparaison des Méthodes de Clustering** : Appliquer deux méthodes de clustering (classification ascendante hiérarchique et k-means) pour comparer les résultats et affiner l’analyse. L’analyse des centroïdes sera également effectuée pour mieux comprendre les classes formées.

4. **Analyse en Composantes Principales (ACP)** : Réaliser une ACP pour visualiser les relations entre les variables et les individus, et pour mieux comprendre les groupes de pays identifiés.

5. **Présentation des Résultats** : Synthétiser les résultats dans une présentation incluant le contexte, la méthodologie, et les recommandations finales pour le choix des marchés à cibler.

## Étapes du Projet

### Étape 1 : Préparation et Exploration des Données

- **Objectif** : Effectuer le nettoyage et l’analyse exploratoire des données de la FAO.
- **Détails** :
  - Traiter les valeurs manquantes et les outliers dans les données.
  - Analyser la distribution des variables et examiner les statistiques descriptives pour chaque indicateur.
- **Livrable** : Un notebook ou fichier R contenant les étapes de préparation, de nettoyage et d’analyse exploratoire des données.

### Étape 2 : Clustering des Pays

- **Objectif** : Appliquer les techniques de clustering pour segmenter les pays.
- **Méthodes** :
  - **Classification Ascendante Hiérarchique (CAH)** : Créer un **dendrogramme** pour visualiser la structure des groupes et identifier les clusters initiaux.
  - **K-means** : Affiner les clusters en appliquant la méthode des k-means et comparer les résultats avec ceux obtenus par la CAH.
  - Analyser les **centroïdes** de chaque cluster pour comprendre les caractéristiques de chaque groupe.
- **Livrable** : Un notebook ou fichier R contenant les clusters formés et les visualisations (dendrogramme, résultats des k-means, etc.).

### Étape 3 : Analyse en Composantes Principales (ACP)

- **Objectif** : Réaliser une ACP pour visualiser les relations entre les variables et les groupes de pays.
- **Détails** :
  - Effectuer une ACP pour réduire la dimensionnalité des données et mieux comprendre la structure des clusters.
  - Visualiser les individus (pays) et les variables sur les axes principaux pour observer les associations et les similarités entre les pays.
- **Livrable** : Visualisations ACP pour interpréter les liens entre les pays et les variables principales.

### Étape 4 : Synthèse et Présentation des Résultats

- **Objectif** : Préparer une présentation pour récapituler les résultats de l’analyse et fournir des recommandations pour le ciblage des marchés.
- **Détails** :
  - Présenter le contexte du projet et expliquer la méthodologie de manière vulgarisée pour faciliter la compréhension des parties prenantes.
  - Exposer les résultats principaux des analyses (dendrogramme, clusters k-means, visualisation ACP).
  - Fournir des recommandations basées sur les groupes de pays identifiés.
- **Livrable** : Présentation PowerPoint ou autre format de présentation, avec un résumé des résultats et des recommandations.

## Détails Techniques

- **Fichiers** :
  - `New Food Balances (FAO)` : Ensemble de données sur les balances alimentaires des pays, fourni en pièce jointe par Patrick.
  - **Notebook de Préparation des Données** : Notebook ou fichier R contenant les étapes de nettoyage et d’analyse exploratoire.
  - **Notebook de Clustering et Visualisations** : Notebook ou fichier R contenant les clusters et les visualisations (dendrogramme, k-means, ACP).

- **Outils Utilisés** :
  - Langage de programmation au choix : **Python** ou **R**.
  - **Techniques de Clustering** : Classification ascendante hiérarchique (CAH) et k-means.
  - **Analyse en Composantes Principales (ACP)** pour la visualisation et la compréhension des groupes.

- **Compétences Utilisées** :
  - Nettoyage et préparation de données.
  - Techniques de clustering et interprétation des clusters.
  - Visualisation des données (dendrogramme, graphique des centroïdes, ACP).
  - Synthèse des résultats et communication des insights.

## Résumé

Ce projet me permet de réaliser une analyse stratégique pour soutenir l’expansion internationale de **La Poule qui Chante**. En segmentant les pays selon leurs caractéristiques alimentaires et socio-économiques, je fournis des insights permettant de cibler des marchés potentiels pour l’exportation. Les résultats obtenus par les méthodes de clustering et l’ACP aideront à orienter les décisions de l’équipe de direction concernant les priorités géographiques.
