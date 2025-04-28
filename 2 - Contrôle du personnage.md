# Contrôle du personnage

Passons maintenant aux contrôles du personnage. 

*Le personnage peut se déplacer dans quatre directions : haut, bas, gauche, droite. Lorsque le Joueur choisis d'avancer, le personnage se déplace dans la direction souhaité et ne s'arrête que s'il rencontre un obstacle, obligeant le joueur à être réactif : il faut éviter de tomber dans un piège.*

### Déplacements

Pour commencer, ajoutez une variable **Direction** à votre personnage. Cette variable servira à savoir dans quelle direction il doit aller. 

Ensuite, allez dans la fenêtre des évènements. Commencez à ajouter des évènements permettant de changer la variable **Direction** en fonction de la touche sur laquelle on appuie. 

(Image pour les évènements)

Une fois que c'est fait, ajoutez les évènements qui déplacent le personnage en fonction de la valeur de sa variable **Direction** : 
  - "Droit" : Le personnage se déplace de 100 sur l'axe X 
  - "Gauche" : Le personnage se déplace de -100 sur l'axe X
  - "Haut" : Le personnage se déplace de -100 sur l'axe Y
  - "Bas" : Le personnage se déplace de 100 sur l'axe Y

(Image pour les évènements) 

### Séparer le personnage des murs

Et maintenant, le personnage peut se déplacer grâce aux touches que nous avons choisies ! Lancez l'aperçus pour voir ce que ça donne. 

Les personnages traversent les murs ? pas de panique : il faut rajouter des évènements pour empécher le personnage de traverser les murs. 
Puisque nous voulons que notre personnage ne puisse jamais traverser les murs, il n'y a pas besoin de condition. 

