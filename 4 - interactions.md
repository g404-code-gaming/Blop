# Interactions avec l'environnement

Maintenant que nous avons la base du jeu, nous allons ajouter des **éléments d'interaction** pour le rendre plus difficile et plus amusant.

## Lave et mort du joueur
Ajoutons un moyen de faire perdre le joueur : un **lac de lave** qui le force à recommencer le jeu en cas de contact.

(image 1)

Il faut d'abord ajouter un objet pour représenter notre lac de lave.

Ensuite, il faut créer un événement qui, lorsque le personnage du joueur touche la lave, le supprime et le fait recommencer la partie.

(image 2)

C'est tout ! Il ne reste plus qu'à jeter le personnage dans la lave pour vérifier si notre programme fonctionne.

## Porte et clé

Nous allons ajouter une **porte**. Elle bloque le passage du personnage et ne peut s'ouvrir qu'avec une **clé**.

(image 3)

Dans un premier temps, il faut ajouter la porte et la clé à la scène. La porte est un objet qu'il faut placer dans le groupe Bloc.

Commençons par créer une variable de scène Key qui compte le nombre de clés que possède le joueur :

(image 4)

Ensuite, ajoutons un texte **TextKey** qui va afficher à l'écran le nombre de clés possédées par le joueur.

Nous pouvons maintenant créer l’événement qui permet de ramasser une clé.

(image 5)

Maintenant que notre personnage peut ramasser des clés, il nous reste à créer l’événement permettant d’ouvrir la porte si le joueur possède une clé.

(image 6)

Il faut vérifier que tout fonctionne : on ne doit pas pouvoir traverser la porte sans clé !

## Bloc poussable

Ajoutons un **bloc**, un obstacle que le personnage peut pousser.

(image 7)

Ajoutez l'objet à la scène. N'oubliez pas que c'est un objet que le personnage ne peut pas franchir : il doit faire partie du groupe **Bloc**.

L'événement qui permet au joueur de déplacer le bloc fonctionne de la manière suivante : lorsque le personnage entre en contact avec le bloc, on déplace ce dernier en fonction de la variable Direction du personnage.

(image 8)

Utilisez le bloc pour condamner un passage, forçant le joueur à le pousser pour trouver son chemin.

Voilà ! Vous avez ajouté de la lave pour tuer le personnage, ainsi que des portes et des blocs poussables pour augmenter le défi. Blop commence à devenir un vrai jeu !

