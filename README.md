# SecurIT Memory

SecurIT Memory est un mini-jeu de cartes Memory développé en C# avec Windows Forms pour le stand de la start-up SecurIT lors d’un salon de l’innovation tech.  
Le but est de proposer un jeu simple et attractif mettant en scène des icônes liées à la cybersécurité et de mesurer le temps et le nombre d’essais des joueurs. 

## Contexte

Ce projet est réalisé en binôme dans le cadre d’un module C# / WinForms. 
L’objectif est de concevoir une application complète avec :
- un menu principal (Jouer / Options / Quitter),
- une interface de jeu générée en WinForms,
- une logique de Memory orientée objet (classe `Carte`, gestion du jeu `JeuMemory`),
- un chronomètre et un compteur d’essais pour la partie.

## État actuel du projet

À ce stade, nous avons mis en place :

- Un projet C# Windows Forms dans Visual Studio Community. 
- Un **menu principal** (`Form1`) avec :
  - un titre `SecurIT Memory`,
  - des boutons `Jouer`, `Options` et `Quitter`. 
- Un **formulaire de jeu** (`FormGame`) séparé qui sera responsable de :
  - la logique de partie via la classe `JeuMemory`,
  - l’affichage du temps de jeu et, plus tard, du nombre d’essais. 
- L’intégration Git/GitHub pour le travail en binôme (pull, résolution de conflits, push).

## Technologies utilisées

- C# (.NET, Windows Forms). 
- Visual Studio Community (designer WinForms, gestion du projet). 
- Git et GitHub pour le versionnement et le travail collaboratif.

## Prochaines étapes

- Implémenter la classe `Carte` (id de paire, image, état Cachée/Révélée/Trouvée). 
- Compléter la classe `JeuMemory` (liste de cartes, mélange, vérification des paires). 
- Générer dynamiquement la grille de cartes dans `FormGame`. 
- Ajouter le chronomètre complet et le compteur d’essais.
- (Bonus) Ajouter un tableau des scores, des thèmes de cartes et des effets sonores.
