# HandCoach

Application web de création d’entraînements de handball.

HandCoach est né d’un besoin réel : en tant qu’entraîneur de handball, pouvoir créer et organiser facilement des exercices et des séances, avec un support visuel clair, imprimable, et accessible sur ordinateur comme sur téléphone.

## Présentation

Application web permettant de :

- Schématiser des exercices sur un terrain de handball
- Ajouter joueurs, plots, ballons, formes et annotations
- Dessiner des trajectoires et consignes tactiques
- Classer les exercices par catégories
- Construire des séances à partir des exercices
- Sauvegarder et synchroniser les données (local + cloud)
- Imprimer / exporter pour utilisation sur le terrain


## Stack technique

- HTML / CSS / JavaScript (vanilla)
- Stockage local (`localStorage`)
- Synchronisation cloud via **Supabase** (PostgreSQL + API)
- Hébergement de la version mobile : GitHub Pages

## Fonctionnalités actuelles

- Éditeur d’exercices sur terrain (drag & drop, dessin, formes)
- Bibliothèque d’exercices et de séances
- Création de séances à partir d’exercices
- Sauvegarde locale
- Synchronisation multi-appareils (PC ↔ smartphone) via Supabase
- Impression / export

## Contexte du projet

Je n’ai que des bases en développement.  
Ce projet a été conçu et développé avec l’aide d’une IA, à partir d’un besoin concret lié à ma pratique d’entraîneur.

L’objectif n’était pas de devenir développeur full-stack, mais de :

- Comprendre la logique d’une application complète
- Apprendre en construisant quelque chose d’utile
- Aboutir à un outil réellement utilisable au quotidien

Il s’agit d’une application déjà opérationnelle pour mon usage, encore perfectible (structure du code, authentification utilisateurs, etc.).

## Compétences / apprentissages

Ce projet m’a permis de travailler concrètement sur :

- La structuration d’une application web
- La gestion de données côté client et côté cloud
- L’organisation d’une interface utilisateur
- L’itération progressive d’un outil
- La résolution de problèmes concrets (sauvegarde, synchro, impression, organisation des séances)
- La mise en place d’un backend simple (Supabase, tables, politiques d’accès)

## Utilisation

1. Ouvrir la démo en ligne, ou le fichier HTML dans un navigateur moderne (Chrome / Edge)
2. Créer des exercices sur le terrain
3. Organiser des séances
4. Sauvegarder (local + cloud selon la version)

## Évolutions envisagées

- Authentification utilisateurs (chaque coach ses données)
- Partage de séances entre entraîneurs
- Amélioration de la structure du code
- Amélioration de l’expérience d’impression
- Mode hors-ligne plus robuste

## Sécurité / données

- Version actuelle : synchronisation via Supabase
- Clé frontend (publishable) utilisée côté client
- Row Level Security prévu pour isoler les données par utilisateur
- Pas encore de comptes utilisateurs finalisés dans la version publique

## Auteur

Projet personnel réalisé dans un contexte de reconversion et de montée en compétences, en parallèle d’une formation en administration d’infrastructures sécurisées et d’une recherche d’emploi.

Coach de handball – besoin terrain → outil numérique.
