# L'argent, le nerf de la guerre ! 

Dans Blop, il faut ramasser toutes les pièces du niveau pour gagner la partie. 

Si ce n'est pas déjà fait, il faut ajouter des pièces dans le jeu. 

(image 1)

##Variables pour compter les pièces

Avant de s'occuper des évènements, nous allons devoir créer une [variables de scène](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Variables.md) **ArgentMax**. Il s'agit du nombre de pièce présent dans la scène.

(image variable)

Dans les évènements, on va initialiser cette variable : Au lancement de la zone, on la remplis avec le nombre de pièces de la scène grâce à la commande *count()*.

(image au lancement de la scène)

Lorsque le nombre de pièce sur la scène est égal à 0 : le joueur a remporter la partie. Pour l'instant, ça fait recommencer le jeu, mais on verra plus tard comment changer de niveaux.

(image fin)

## Rammasser et afficher les pièces 

Pour rammasser les pièces, il nous faut un [évènement](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/%C3%A9v%C3%A8nements.md). Cet évènement se décompose en plusieurs choses : 
  -Condition : l'évènement se déclenche quand notre personnage entre en collision avec une pièce. 
  -Action 1 : on supprime la pièce 
  -Action 2 : on met à jour la variable ArgentMax. 

  (image évènement) 

  Il faut tester le jeu pour voir si la partie se relance lorsqu'on rammasse toutes les pièces. Si oui, alors bravo ! 

  Désormais, il nous reste à afficher le nombre de pièce qu'il faut rammasser pour gagner. 

  Nous allons d'abord créer un nouveau calque, que nous allons appelé UI. 

  (image calque)

  Dans ce calque, nous allons ajouter un objet de type Texte, nommé **TextGold**. 

  (image objet texte) 

  Une fois que le texte est mis sur la scène, il faut lancer l'aperçus pour vérifier qu'il apparait bien où il faut et qu'il suit le personnage correctement. Sinon, il y a une erreur qu'il faut corriger. 

  Il ne reste plus qu'à ajouter les actions propre au texte dans les évènements : 

  (image evenement texte) 

  Et voilà, désormais, on peut rammasser des pièces pour remporter la partie ! 
  
