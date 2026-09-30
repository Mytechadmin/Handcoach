# HandCoach

Application web de création d’entraînements de handball.

HandCoach est né d’un besoin réel : en tant qu’entraîneur, pouvoir créer et organiser facilement des exercices et des séances, avec un support visuel clair, imprimable, et utilisable au quotidien.

---

## Présentation

Application web permettant de :

- Schématiser des exercices sur un terrain de handball
- Ajouter joueurs, plots, ballons, formes et annotations
- Dessiner des trajectoires et consignes tactiques
- Classer les exercices par catégories
- Construire des séances à partir des exercices
- Sauvegarder et synchroniser les données (cloud Supabase)
- Partager des bibliothèques d’exercices entre coachs
- Imprimer / exporter pour utilisation sur le terrain
- Personnaliser l’interface (logo club, couleurs, fond)

---

## Stack technique

- HTML / CSS / JavaScript (vanilla)
- Stockage local (`localStorage`) en cache
- Synchronisation cloud via **Supabase** (Auth + PostgreSQL + Storage)
- Hébergement possible : Netlify, GitHub Pages, ou ouverture directe du fichier HTML

---

## Fonctionnalités actuelles

### Éditeur
- Terrain de handball interactif (drag & drop)
- Joueurs A/B, plots, ballons, formes géométriques, texte
- Dessin libre (crayon) avec couleurs et épaisseurs
- Second terrain « Évolution »
- Annuler / rétablir
- Champs : mise en place, consignes, variantes, objectifs, durée

### Organisation
- Bibliothèque d’exercices par catégories
- Création de séances (glisser-déposer d’exercices)
- Réordonnancement des exercices dans une séance
- Impression d’un exercice ou d’une séance complète

### Compte & cloud
- Connexion / inscription (e-mail + mot de passe)
- Réinitialisation de mot de passe
- Sauvegarde cloud par utilisateur
- Bibliothèques partagées (codes d’invitation lecture / modification)
- Partage d’exercices et de séances vers une bibliothèque
- Déconnexion automatique après inactivité (timer côté app)

### Personnalisation
- Logo du club sur le terrain
- Couleurs des joueurs et plots
- Image de fond

---

## Contexte du projet

Je n’ai que des bases en développement.  
Ce projet a été conçu et développé avec l’aide d’une IA, à partir d’un besoin concret lié à ma pratique d’entraîneur.

L’objectif n’était pas de devenir développeur full-stack, mais de :

- Comprendre la logique d’une application complète
- Apprendre en construisant quelque chose d’utile
- Aboutir à un outil réellement utilisable au quotidien

Application déjà opérationnelle pour mon usage, encore perfectible (structure du code, UX, etc.).

---

## Compétences / apprentissages

Ce projet m’a permis de travailler concrètement sur :

- La structuration d’une application web
- La gestion de données côté client et cloud
- L’authentification utilisateurs (Supabase Auth)
- Les politiques d’accès et le partage de données
- L’organisation d’une interface utilisateur
- L’itération progressive d’un outil
- La résolution de problèmes concrets (sauvegarde, synchro, impression, second terrain, sessions)

---

## Utilisation

1. Ouvrir la démo en ligne, ou le fichier HTML dans Chrome / Edge
2. Créer un compte ou se connecter
3. Créer des exercices sur le terrain
4. Organiser des séances
5. Sauvegarder (synchronisation cloud automatique)
6. Imprimer si besoin pour le terrain

---

## Évolutions envisagées

- Mode hors-ligne plus robuste
- Amélioration de l’expérience d’impression
- Refactoring / structure du code
- Améliorations UX (mobile + desktop)
- Gestion fine des rôles dans les bibliothèques

---

## Sécurité / données

- Authentification Supabase (e-mail / mot de passe)
- Données isolées par utilisateur
- Bibliothèques partagées via codes d’invitation
- Clé frontend (publishable) côté client — les règles d’accès sont côté Supabase (RLS)
- Déconnexion après inactivité configurable dans l’app

---

## Auteur

Projet personnel réalisé dans un contexte de reconversion et de montée en compétences, en parallèle d’une formation en administration d’infrastructures sécurisées et d’une recherche d’emploi.

Coach de handball — besoin terrain → outil numérique.
