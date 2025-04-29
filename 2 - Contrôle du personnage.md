# Contrôle du personnage

Passons maintenant aux contrôles du personnage. 

>Le personnage peut se déplacer dans quatre directions : haut, bas, gauche, droite. Lorsque le Joueur choisis d'avancer, le personnage se déplace dans la direction souhaité et ne s'arrête que s'il rencontre un obstacle, obligeant le joueur à être réactif : il faut éviter de tomber dans un piège.

### Déplacements

Pour commencer, ajoutez une [variable](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Variables.md) **Direction** à votre personnage. Cette variable servira à savoir dans quelle direction il doit aller. 

Nous allons également faire une variable **Movable**, qui permet de savoir si notre personnage peut bouger ou non.

![variable](https://github.com/g404-code-gaming/Blop/blob/main/Image/deplacement_evenement_0.JPG)

Ensuite, allez dans la fenêtre des [évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/%C3%A9v%C3%A8nements.md). Commencez à ajouter des évènements permettant de changer la variable **Direction** en fonction de la touche sur laquelle on appuie. 

Une fois que c'est fait, ajoutez les évènements qui déplacent le personnage en fonction de la valeur de sa variable **Direction** : 
  - "Droit" : Le personnage se déplace de 100 sur l'axe X 
  - "Gauche" : Le personnage se déplace de -100 sur l'axe X
  - "Haut" : Le personnage se déplace de -100 sur l'axe Y
  - "Bas" : Le personnage se déplace de 100 sur l'axe Y

![variable](https://github.com/g404-code-gaming/Blop/blob/main/Image/deplacement_evenement_1.JPG)

Et maintenant, le personnage peut se déplacer grâce aux touches que nous avons choisies ! Lancez l'aperçus pour voir ce que ça donne. 

### Séparer le personnage des murs

Les personnages traversent les murs ? pas de panique : il faut rajouter des évènements pour empécher le personnage de traverser les murs. 
Puisque nous voulons que notre personnage ne puisse jamais traverser les murs, il n'y a pas besoin de condition. 

![variable](https://github.com/g404-code-gaming/Blop/blob/main/Image/deplacement_evenement_3.JPG)

Avec tout ça, nous avons un personnage qui peut se déplacer et qui ne traverse pas les murs. Le Labyrinthe prend vie petit à petit. 

[étape 3 : Gestion des pièces et de la fin de partie](https://github.com/g404-code-gaming/Blop/blob/main/3%20-%20Argent)
