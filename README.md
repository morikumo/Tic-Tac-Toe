# Tic-Tac-Toe en C#

Un jeu de Tic-Tac-Toe simple en mode console, développé en C# pour 2 joueurs.

## Fonctionnalités

- **Grille 3x3** : le jeu suit la structure classique du Tic-Tac-Toe.
- **Tour par tour** : les joueurs placent leurs symboles (X et O) chacun leur tour.
- **Détection automatique de fin de partie** : le jeu vérifie automatiquement si un joueur a gagné ou si la partie est une égalité.
- **Affichage de la grille en temps réel** : la grille est mise à jour après chaque tour, montrant clairement les positions occupées.

## Structure du Code

- **Gestion des Entrées** : Le code vérifie la validité des entrées pour éviter les positions déjà occupées et les valeurs hors de la grille.
- **Contrôle du Jeu** : Une boucle principale contrôle le déroulement du jeu, vérifiant à chaque tour les conditions de victoire ou d'égalité.
- **Conditions de Victoire** : Les conditions sont implémentées pour détecter les alignements gagnants en lignes, colonnes et diagonales.
- **Affichage en Console** : Le code utilise `Console.WriteLine` pour afficher la grille, simplifiant la visualisation de chaque mouvement en temps réel.

## Règles du Jeu

Les joueurs se relaient pour placer X et O dans la grille 3x3 jusqu'à ce qu'un alignement gagnant soit réalisé ou que la grille soit pleine.

---

**Prêt à jouer ?**