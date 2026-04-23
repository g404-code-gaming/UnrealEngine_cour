# Utiliser une vidéo comme texture 

Dans vos projets Unreal Engine, vous pourrez utiliser des vidéos MP4 en guise de texture pour vos objets.

C'est un excellent moyen d'apporter du vivant à votre jeu. 

Dans notre exemple, nous allons chercher a ajouter une texture d'eau personnalisée à notre jeux. 

## Création des fichiers 

### 1 - Choisir sa vidéo

Pour commencer, il faut chercher sur Internet une vidéo MP4. 

Vous pouvez trouver des exemples de vidéo MP4 gratuites sur Pixabay 

### 2 - Dossier 

Dans votre jeu, créer un nouveau dossier **Vidéo**

-image dossier 1 

Dans ce dossier, vous aurez un dossier pour chacune des textures animées que vous ajouterez au jeu.

Dans l'exemple, ajoutez un dossier **Eau**

-image dossier 2 

### 3 - Créer Media Source 

Dans le dossier **Eau**, créer un Media Source nommé Eau_Media_Source 

-image media source 

### 4 - Ajouter la vidéo dans le dossier 

Ouvrez votre dossier

-ouvrir dossier

Dans ce dossier, placez votre image (généralement, elle se trouve dans les téléchargement)

### 5 - Créer Media Player 

Dans le même dossier, créer un Media Player Eau_Media_Player. 

-image media player création 

Cela va créer un même temps un Media Texture. 

## Préparation 

### 1 - Media Source 

Ouvrez le Media Source, puis choissisez le chemin vers la vidéo

- image media source 

Dans la liste, choissisez votre vidéo. 

- image choisir vidéo

### 2 - Media Player

Ouvrir le Media Player

à l'intérieur, choississez la vidéo, et cochez les options "Play on Open" et "Loop". 

-image media player 

## Placement et gestion de la texture animée 

### 1 - Placer la texture 

Dans votre niveau, placez la **Media texture** sur votre objet. 

- image poser texture

### 2 - Variable media player 

Dans votre **Level Blueprint**, ajouter une nouvelle variable de type **Media Player**. Dans les détails de cette variable, choississez votre **Eau_media_player**. 

NOTE : si votre vidéo est liée à une classe, cette démarche peut être faite directement dans le blueprint de la classe. 

-image variable

### 3 - Programme de lancement de la vidéo

Une fois que la variable est créée, il faut créer le programme qui l'active. 

Dans notre exemple, elle se lance au début du niveau (grâce à BeginPlay). 

Utilisez le node Open Source et la variable utilisée précédemment. 

- image code

Vous pouvez tester votre niveau : désormais, vous avez une image animée sur votre objet !




