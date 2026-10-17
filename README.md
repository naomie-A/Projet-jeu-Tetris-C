# Jeu de logique inspiré de Tetris — C

![Langage](https://img.shields.io/badge/Langage-C-A8B9CC?logo=c&logoColor=black)
![Interfaces](https://img.shields.io/badge/Interfaces-Terminal%20%2B%20SDL2-343A40)
![Structures](https://img.shields.io/badge/Structures-Listes%20cha%C3%AEn%C3%A9es-2E8B57)

## Présentation

Ce projet est un **jeu de logique en langage C**, inspiré de Tetris, proposé en **deux versions** : une version dans le terminal et une interface graphique développée avec **SDL2**. Plutôt qu'une grille classique, il utilise une liste de pièces à manipuler pour créer des combinaisons.

Le programme s'appuie sur des **listes doublement chaînées circulaires** pour représenter les pièces et gérer différents éléments du jeu, notamment les couleurs, l'historique et les prochaines pièces.

## Fonctionnalités

- **Quatre formes de pièces** identifiées par les lettres `C`, `R`, `T` et `L`.
- **Quatre couleurs** : rouge, vert, jaune et bleu.
- **Insertion à gauche ou à droite** de la liste principale.
- **Décalage par forme ou par couleur** pour réorganiser les pièces et créer des combinaisons.
- **Suppression automatique** des suites d'au moins trois pièces identiques.
- **Calcul du score** selon le type d'action ou de suppression.
- **Sauvegarde et chargement** des parties.
- **Classement des dix meilleurs scores** avec pseudonymes.
- **Affichage coloré dans le terminal** à l'aide de séquences d'échappement ANSI.\n- **Version graphique SDL2**, avec rendu des formes et affichage du texte via SDL_ttf.

## Principe du jeu

1. Observer les pièces et leurs caractéristiques.
2. Choisir où insérer une pièce : à gauche ou à droite.
3. Réorganiser la liste en effectuant des décalages par forme ou par couleur.
4. Former des groupes d'au moins trois pièces identiques pour déclencher leur suppression.
5. Accumuler des points et tenter d'entrer dans le **top 10**.

## Aspects techniques

| Élément | Utilisation dans le projet |
| --- | --- |
| **C** | Implémentation de la logique du jeu |
| **Listes doublement chaînées circulaires** | Organisation et manipulation des pièces |
| **Gestion des couleurs et des formes** | Identification des pièces et création de combinaisons |
| **Sauvegarde / chargement** | Conservation et reprise d'une partie |
| **Codes ANSI** | Couleurs et rafraîchissement de l'affichage terminal |\n| **SDL2 / SDL_ttf** | Fenêtre graphique, dessin des pièces et texte |

## Récupérer le projet

Le projet est fourni sous forme d'archive dans ce dépôt :

📦 **[Télécharger les fichiers du jeu](Projet_C.zip)**

Pour l'explorer :
1. Télécharger puis extraire l'archive.
2. Repérer les fichiers sources en C et les éventuels fichiers d'instructions.
3. Pour la version terminal, consulter `tetriste.c`, `list.c` et `forme.c` (ainsi que leurs fichiers d'en-tête).\n4. Pour la version graphique, ouvrir le dossier `SDL_interface`, qui contient notamment `tavalide.c`, `SDL_Forme.c` et les fichiers associés. Cette version utilise SDL2 et SDL_ttf.

## Compétences illustrées

Programmation en C · Structures de données dynamiques · Manipulation de listes chaînées · Logique de jeu · Gestion d'état · Affichage en console

---

*Projet de programmation en C autour des structures de données et des mécaniques de jeu.*
