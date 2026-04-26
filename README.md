# Projet-jeu-Tetris-C

 # Projet Tetris-like en C (listes chaînées, couleurs, sauvegarde)

Ce projet est une implémentation d’un Tetris-like dans le terminal.
Le jeu repose entièrement sur des listes doublement chaînées circulaires pour gérer les pièces, les couleurs, l’historique et les futures pièces.

Fonctionnalités: 

- Pièces définies par une lettre (C, R, T, L) et une couleur (rouge, vert, jaune, bleu).
- Deux modes d’insertion : à droite ou à gauche de la liste principale.
- Décalages (déphasage) : choisir une forme ou une couleur pour réorganiser la liste et créer des combos.
- Suppression automatique des séquences de 3 pièces identiques ou plus.
- Système de score différent selon suppression simple ou décalage.
- Sauvegarde / chargement d’une partie.
- Tableau des 10 meilleurs scores avec pseudo.
- Affichage dynamique dans la console (ANSI/VT100).
