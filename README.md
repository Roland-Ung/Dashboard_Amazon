# Dashboard_Amazon

## Objectifs
- Transformer des données de ventes brutes (10 000+ lignes) en un outil d'aide à la décision interactif.
- Analyser la performance commerciale, la segmentation produit et la répartition géographique
- Identifier les zones de croissance et les comportements d'achat des clients

## Technologies utilisés
- Power BI
- Langage DAX
- Power Query

## Key Features

### 1 - Nettoyage de données
- Traitement des formats de dates hétérogènes et conversion des types de données avec gestion des paramètres régionaux

### 2 - KPI
- Chiffre d'affaires
- Prix de vente moyen
- Nombre de commandes
- Quantité total commandé
- Nombre d'Etats
- Nombre de villes
- Chiffre d'affaires moyen par Etat
- Chiffre d'affaires moyen par ville

### 3 - Analyse temporelle
- Graphique d'évolution par jour combinant Chiffre d'Affaires et Volume de commandes pour détecter les pics d'activité

### 4 - Segmentation avancée
- Analyse de la répartition par catégorie (Treemap) et par taille (Bar Chart) pour optimiser les stocks.
- Filtres par le statut de la commande (annulé, en attente, expédié) et par la date

### 5 - Intelligence géographique
- Cartographie de la performance par État et Ville avec identification des "Top 10 des villes" générateurs de revenus

### 6 - info-bulle
- Evolution du chiffre d'affaires par mois pour les catégories, les tailles et les Etats

### 7 - Dashboarding multidimensionnel
- Création d'un menu permettant de naviguer entre plusieurs onglets

## Key Insights

### 1 - Dominance d'une catégorie
- La catégorie "Set" domine le marché avec plus de 50% du chiffre d'affaires (26,2M€). C'est le cœur de l'activité.

### 2 - Courbe d'évolution
- Le chiffre d'affaires dépasse 0,8M€ par jour. Il serait intéressant d'analyser s'il s'agissait d'une promotion ou d'un événement saisonnier

### 3 - Analyse de taille
- Les tailles M, L et XL sont les plus vendues. La taille XS est la moins performante, ce qui suggère une réduction possible de ces stocks

### 4 - Concentration géographique
- Les Etats Maharashtra et Karnataka sont les moteurs de croissance.

### 5 - Villes championnes
- Bengaluru est la ville n°1, dépassant largement Hyderabad en termes de chiffre d'affaires

### 6 - Corrélation CA/Quantité
- La corrélation linéaire est presque parfaite, le prix de vente moyen est stable à travers les États, il n'y a pas d'État où l'on vend "peu mais très cher"

## Utilisation
- Télécharger le fichier `dashboard_amazon.pbix`
- Ouvrir sur Power BI Desktop

## Compétences démontrés
- Nettoyage de données : Power Query (gestion des formats régionaux US/FR, traitement des dates, typage des données).
- Modélisation : Création d'un schéma en étoile (Table de faits et Tables de dimensions).
- DAX : Création de mesures calculées (KPI).
- Visualisation : Design de dashboards interactifs avec navigation par onglets
