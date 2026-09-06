# Handcoach
Application Web de création d'entrainement de handball

# HandCoach

Application web de schématisation tactique pour le handball.

HandCoach est né d’un besoin réel : étant entraineur et coach de handball depuis des années, pouvoir créer et organiser facilement des exercices et des séances d’entraînement, avec un support visuel clair et imprimable.

## Présentation

Ce projet est une application web monopage permettant de :
- Schématiser des exercices sur un terrain de handball
- Ajouter joueurs, plots, ballons, formes et annotations
- Dessiner des trajectoires / consignes tactiques
- Classer les exercices par catégories
- Construire des séances à partir des exercices
- Sauvegarder localement, exporter/importer en JSON et imprimer en pdf afin de partager sur le cloud

## Contexte

Je n’ai que des notions en développement.  
Ce projet a été conçu et coder avec l’aide d’une IA, à partir d’un besoin concret lié à ma pratique.

L’objectif n’était pas de devenir développeur, mais de :
- Comprendre la logique d’une application complète
- Apprendre en construisant quelque chose d’utile
- Aller jusqu’à une version fonctionnelle et utilisable

Il s’agit d’une ébauche déjà bien abouti pour mon usage : déjà utilisable au quotidien, mais perfectible (structure du code, évolutions fonctionnelles, etc.).

## Compétences / apprentissages

Même avec un niveau débutant en code, ce projet m’a permis de travailler sur :
- La structuration d’une application web
- La gestion de données côté client (localStorage)
- L’organisation d’une interface utilisateur
- L’itération progressive d’un outil
- La résolution de problèmes concrets (sauvegarde, import/export, impression, organisation des séances…)

## Utilisation

1. Ouvrir le fichier HTML dans un navigateur moderne (Chrome ou Edge recommandés)
2. Créer des exercices sur le terrain
3. Sauvegarder et organiser les séances
4. Exporter ou imprimer selon les besoins

## Évolutions envisagées

- Amélioration de la structure du code
- Mode deux terrains (situation initiale / situation après déplacement)
- Amélioration de l’expérience d’impression
- Nettoyage et clarification du code

## Sécurité

HandCoach fonctionne entièrement côté client (aucune donnée n’est envoyée sur un serveur).

Dans sa version actuelle, le projet n’intègre pas encore de mesures de sécurisation avancées :
- Pas de validation stricte des fichiers importés
- Pas de chiffrement des données sauvegardées
- Stockage local en clair (localStorage / fichiers JSON)

Ces points pourront être travaillés ultérieurement, notamment dans une logique d’amélioration de la robustesse de l’application.

## Auteur

Projet personnel réalisé dans un contexte de reconversion / montée en compétences, en parallèle d’une formation en administration d’infrastructures sécurisées et d’une recherche d’emploi.
