# Blueprint

Dans Unreal Engine 5, un **Blueprint** est un système de programmation visuelle qui permet de créer du code sans écrire avec un langage. Il fonctionne comme un organigramme interactif où l’on connecte des nœuds représentant des actions, des événements ou des variables.

Les Blueprints sont une manière plus intuitive et accessible d'apprendre à programmer. 

(image 1)

Dans les cours sur Unreal Engine, nous allons utiliser deux types de blueprints : 

### Lvl Blueprint 

Le **Level Blueprint** sert à gérer les événements et la logique spécifiques à un niveau, comme déclencher une cinématique ou ouvrir une porte quand le joueur entre dans une zone. Il n’est pas réutilisable entre plusieurs niveaux, car il est lié uniquement à la scène en cours.

(image 2)

### Class Blueprint 

Les **Class Blueprints** permettent de créer des objets ou entités réutilisables (personnages, ennemis, objets interactifs) avec leur propre logique. Ils sont basés sur des classes comme Actor ou Pawn et peuvent être utilisés dans n’importe quel niveau.

(image 3)

## Créer un évènement à partir de Node

Les Blueprints se résument en une connexion de **node** (ou noeud) : une unité visuelle représentant une action, une fonction, un événement ou une variable, que l’on connecte à d’autres nœuds pour créer la logique du jeu.

Il faut utiliser la **barre de recherche** pour trouver le node que l'on souhaite ajouter au blueprint.

(image 4)

Un Node possède des **données d'entrées** (input) qui vont recevoir des signaux et informations d'autres Nodes, et des **données de sortie** (output) qui vont transmettre des signaux ou informations aux Nodes suivants, permettant de créer un chemin.

(image 5)

> Note : tout les input et output d'un node ne sont pas forcément utilisés dans le blueprint : on ne connecte que ceux dont on a besoin.
