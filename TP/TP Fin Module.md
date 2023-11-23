# Travaux Pratiques : Conception et Manipulation de Base de Données SQL pour un Système de Gestion de Stock

## Objectif du TP

Ce TP vise à développer vos compétences en SQL dans un contexte professionnel, en se concentrant sur la conception et la manipulation d'une base de données pour un système de gestion de stock.

## Partie 1: Conception de la Base de Données

1.1 Création du Schéma

Concevez un schéma de base de données pour un système de gestion de stock d'une entreprise. Votre schéma doit inclure les tables suivantes : Produits, Fournisseurs, Commandes, Clients.

Chaque table doit avoir une clé primaire appropriée.

Établissez des relations entre les tables, telles que les commandes liées aux clients et aux produits.

## 1.2 Définition des Tables

Définissez les attributs pour chaque table. Par exemple, la table Produits peut inclure des attributs comme ID_Produit, Nom, Prix, QuantitéEnStock.

## Partie 2: Requêtes SQL

## 2.1 Requêtes de Base

Création et Insertion:

Ajouter de nouveaux enregistrements dans les tables, comme l'ajout de nouveaux produits, clients, et fournisseurs.

Lecture et Recherche:

Récupérer des informations spécifiques, telles que la liste de tous les produits d'une certaine catégorie ou les détails d'un client spécifique.

Mise à Jour:

Modifier des données existantes, comme mettre à jour la quantité en stock d'un produit après une vente ou une livraison.

Suppression:

Retirer des enregistrements, par exemple supprimer un produit qui n'est plus vendu.

## 2.2 Requêtes Avancées

Suivi de Stock:

Identifier les produits avec un niveau de stock faible ou en rupture de stock.

Analyse des Commandes des Clients:

Extraire l'historique complet des commandes d'un client donné, y compris les détails des produits commandés.

Calcul du Chiffre d'Affaires:

Calculer le chiffre d'affaires généré par les ventes de chaque produit ou catégorie.

Rapports sur les Tendances de Vente:

Analyser les tendances des ventes sur différentes périodes, comme les ventes mensuelles ou annuelles.

## 2.3 Requêtes Avancées

Requête de Jointure Complexe:

Combinez des données de plusieurs tables (par exemple, Produits, Commandes, et Clients) pour fournir un rapport détaillé sur les commandes, incluant les informations des clients et les détails des produits commandés.

Requête d'Agrégation et de Groupement:

Calculez le chiffre d'affaires total par catégorie de produit sur une période spécifique, en utilisant des fonctions d'agrégation comme SUM et des groupements.

Analyse Temporelle:

Comparez les volumes de ventes mensuelles ou annuelles pour identifier les tendances ou les anomalies saisonnières.

Requête Corrélative Subtile:

Déterminez les produits qui n'ont jamais été commandés ou les clients qui n'ont pas passé de commande depuis une période donnée.

Requête de Fenêtrage:

Utilisez des fonctions de fenêtrage pour calculer des statistiques courantes (moyenne, total cumulé) sur les ventes ou les stocks.

Requête avec Sous-Requêtes:

Identifiez le produit le plus vendu dans chaque catégorie, en utilisant des sous-requêtes imbriquées.

Requête pour Analyse de Performance des Fournisseurs:

Évaluez les fournisseurs en fonction du nombre de commandes en retard ou du temps moyen de livraison.

Requête de Regroupement Conditionnel:

Classez les clients en différents segments (par exemple, VIP, régulier, occasionnel) basés sur leur volume d'achat total ou la fréquence des commandes.

Requête pour Détection de Fraude Potentielle:

Identifiez des anomalies dans les commandes ou les paiements qui pourraient indiquer des activités frauduleuses.

Optimisation des Stocks:

Proposez une stratégie pour minimiser le stock tout en évitant la rupture de stock, en analysant les modèles de vente.
