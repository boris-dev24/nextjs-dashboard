# Projet Dashboard avec Next.js

## Description

Ce projet est une application de tableau de bord (dashboard) réalisée avec Next.js. Il permet de visualiser les données de revenus et de gérer des factures à l'aide de composants interactifs et d'une base de données intégrée. Ce projet utilise plusieurs bibliothèques et API modernes telles que Next.js, React, et des fonctionnalités liées à la gestion des données sur un serveur (SSR, API routes).

## Fonctionnalités implémentées

- **Affichage des revenus** : Un graphique montrant les revenus des 12 derniers mois.
- **Gestion des factures** : Consultation des factures d'un montant précis avec les informations des clients associés.
- **Seeding de base de données** : Initialisation de la base de données avec des données fictives pour le développement.

## Étapes suivies dans le tutoriel

1. **Création d'un projet Next.js** : Mise en place du projet en utilisant Next.js pour la gestion des composants côté serveur et client.
2. **Mise en place de l'interface utilisateur** : Création des différents composants UI, y compris le graphique des revenus et la liste des factures.
3. **Implémentation des routes API** : Utilisation de la route `app/query/route.ts` pour interroger la base de données avec une requête SQL.
4. **Seed de la base de données** : Script de peuplement de la base de données avec des données fictives pour simuler des utilisateurs et des factures.
5. **Personnalisation du graphique** : Utilisation de la bibliothèque `Chart.js` ou d'un autre outil similaire pour générer un graphique à partir des données de revenus.

## Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

- Node.js (version recommandée : 18.x ou supérieure)
- npm ou pnpm (gestionnaire de paquets)
- PostgreSQL ou une autre base de données compatible

## Installation


1. Clonez le projet :

```bash
git clone https://github.com/boris-dev24/nextjs-dashboard/tree/master
cd <nextjs-dashboard>


