# 💳 SecurePay – Système de détection de fraude bancaire

SecurePay est un projet de **base de données relationnelle** réalisé dans le cadre du module **Base de Données** à **Sup'Com (2025–2026)**.

L'objectif est de concevoir une base de données robuste permettant de gérer les clients, les comptes bancaires et les transactions, tout en intégrant des mécanismes de détection de fraude afin d'identifier automatiquement les comportements suspects.

---

## 📖 Présentation

Les institutions financières traitent quotidiennement un grand volume de transactions. Il est donc essentiel de disposer d'un système capable de détecter rapidement les opérations potentiellement frauduleuses.

SecurePay répond à cette problématique en proposant une modélisation complète d'une base de données bancaire intégrant :

- la gestion des clients et des comptes ;
- le suivi des transactions bancaires ;
- l'historique des connexions ;
- la génération d'alertes de fraude ;
- le calcul d'indicateurs de risque.

---

## ✨ Fonctionnalités

### 👤 Gestion des clients

- Création et gestion des clients  
- Gestion des comptes bancaires  
- Blocage et déblocage des comptes  

### 💳 Gestion des transactions

- Enregistrement des transactions  
- Gestion des virements entre comptes  
- Suivi de l'historique des opérations  
- Gestion des statuts des transactions  

### 🌍 Suivi des connexions

- Historique des connexions  
- Enregistrement des adresses IP  
- Détection des connexions inhabituelles  
- Identification des connexions multiples  

### 🚨 Détection de fraude

Le système permet notamment de détecter :

- les transactions anormalement élevées  
- les opérations répétées proches du seuil réglementaire (*Structuring*)  
- les chaînes de virements suspectes  
- les connexions provenant d'un pays ou d'un appareil inhabituel  
- les comportements à risque grâce à un score calculé par utilisateur  

### 📊 Gestion des alertes

- Génération automatique d'alertes  
- Classification par niveau de gravité  
- Suivi du traitement des alertes  
- Statistiques de résolution  

---

## 🗃️ Modèle de données

La base de données repose sur un modèle relationnel reliant plusieurs entités principales :

- Clients  
- Comptes bancaires  
- Transactions  
- Connexions  
- Alertes  
- Analystes  
- Administrateurs  

Le modèle respecte les principes de normalisation afin de garantir :

- l'intégrité des données  
- la cohérence des informations  
- la réduction des redondances  
- de bonnes performances lors des requêtes  

---

## 🛠️ Technologies utilisées

- Oracle SQL 19c  
- Oracle SQL Developer  
- SQL  
- Modélisation relationnelle  
- Contraintes d'intégrité  
- Requêtes SQL avancées  

---

## 📚 Documentation

Ce dépôt contient :

- le cahier des charges du projet  
- le rapport complet  
- la présentation des principales requêtes SQL  
- le schéma relationnel  
- la description détaillée des tables et de leurs attributs  

---

## 🎯 Objectifs pédagogiques

Ce projet m'a permis de mettre en pratique :

- la conception d'une base de données relationnelle  
- la modélisation d'un système bancaire  
- l'écriture de requêtes SQL complexes  
- la gestion des contraintes d'intégrité  
- l'optimisation de la structure des données  
- la conception d'un système de détection de fraude  

---

## 👥 Auteurs

- **Anas Saoudi**  
- **Mohamed Batti**

Projet réalisé dans le cadre du module **Base de Données** — **Sup'Com (2025–2026)**
