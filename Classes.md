# Classes 

Dans Unreal Engine, une **classe** est un modèle de code définissant les propriétés et comportements d’un objet, comme un personnage, une arme ou un élément de décor. Elle sert à créer des instances (objets) dans le jeu, permettant de contrôler leur logique, apparence et interactions.

Au lieu de créer manuellement tout les objets et de leur créer un script directement dans le Level-Blueprint, les Classes peuvent être modifiée et gérer indépendamment et avoir leur propre Blueprint, ce qui simplifie grandement la construction d'un jeu.

![image 1]() 

## Créer une classe 

#### À partir de 0 

Pour créer une nouvelle classe à partir de 0, il suffit de faire un clic droit dans le dossier où tu souhaite faire ton image, et de choisir une nouvelle classe Blueprint. 

![image 2]() 

#### À partir d'un objet existant 

![image 3]() 

#### À partir de plusieurs objets existants 

Lorsque l'on souhaite créer une classe à partir de plusieurs objets existants (ce qui arrive notammant lorsque l'on crée des formes complexes via l'outil de modélisation) on accède à la conversion depuis le panneau d'édition du niveau :

![image 4]() 

## Interface d'une classe 

Les principaux éléments de l'interface d'une classe que nous allons utiliser sont : 
  - (1) le Viewport, qui permet de voir à quoi ressemble l'objet.
  - (2) le Graphique d'évènement, dans lequel nous allons mettre le programme du blueprint.
  - (3) Les composants de notre objet. Ici nous pouvons ajouter de nouveau objets, commes des collisions ou des lumières.
  - (4) Les détails de l'objet, comme la texture, les paramètres physiques, ....
  - (5) les variables, event ou fonctions propre à notre objet.

![image 5]() 
