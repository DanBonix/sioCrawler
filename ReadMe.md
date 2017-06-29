 # Projet sioCrawler #
 
 Présentation du projet : le but est de réaliser un jeu de rôle permettant un jeu peu massivement multi joueur permettant aux étudiants du bts sio de se divertir pendant les heures de cantine mais surtout d'améliorer leurs compétences en développement.
 
 Les outils mis en oeuvre :

 * Git
 * Visual studio
 * Mysql
 * Apache

 Le développement tourne autour de 3 grandes parties

1. L'inscription en ligne
2. Développement du jeu en lui même permettant l'exploration d'un labyrinthe
3. La sauvegarde des personnages et du contexte du jeu

|Développement         |Langages  |Techniques de programmation                          |
|----------------------|:--------:|----------------------------------------------------:|
|inscription en ligne  |PHP, Mysql|Développement web MVC avec Code Igniter              |
|sio crawler le jeu    |C#        |Programmation objet, tests unitaires                 |
|sauvegarde du contexte|C#, Mysql |Programmation procédural procédures stockées en mysql|

## L'inscription en ligne ##

Site web permettant à un joueur de s'inscrire en ligne. le projet prévoit le principe suivant pour l'inscription en ligne.

[acteurFluxInscription.PNG](https://github.com/DanBonix/sioCrawler/blob/master/acteurFluxInscription.PNG)

## sio crawler le jeu ##

Le joueur possédera les fonctionnalités suivantes :

![useCasePersonnage.PNG](https://github.com/DanBonix/sioCrawler/blob/master/useCasePersonnage.PNG)

Les classes développées :

![diagrammeClassePersonnage.PNG](https://github.com/DanBonix/sioCrawler/blob/master/diagrammeClassePersonnage.PNG)

## Sauvegarde du contexte ##

La sauvegarde du contexte se fera dans la base de données :

![mcdSauvegarde.PNG](https://github.com/DanBonix/sioCrawler/blob/master/mcdSauvegarde.PNG)