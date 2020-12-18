# LES BOUCLES

## Qu'est-ce qu'une boucle ?

Une boucle sert une peu comme une condition. C'est enfaite quand un événement, action se déroule quand est atteint son but, ce pour quoi a été créé et pas avant.
C'est la reviens à peu a dire que TANT QUE la condition n'est pas rempli ou qu'elle n'a pas atteint son maximum, le programme continuera a s'exécuter.

## Code

Il y a d'abord deux mots principaux qui permettent de coder une boucle dans un script shell. Les mots _while_ et _for_. 

_While_ veux dire TANT QUE tandis que _for_ veux dire POUR.

    On utilise pour coder _while_, qui n'arrêtera pas le programme tant que la condition ne sera pas vérifiée.
    On utilse pour coder _for_, qui permet de stoper un programme seulement si la réponse correspond à un résultat précis et préalablement enregistré.
    
 ## While
 
 Quand on code une boucle _while_, il y a trois mots de base :
 
        - while => veux dire TANT QUE, début de la boucle
        - do => veux dire ALORS FAIT
        - done => veux dire TERMINÉ, fin de la boucle
    
 Cela ressemblera à cela :
 
        while [condition à vérifier]; do
            afficher/effectuer ...
        done
  
  ### Exemple
  
  Imaginons que tant que l'âge de Nems n'est pas trouvé, le programme continuera.
  
  Tout d'abord le code :
  
    while [ -z $age ] || [ $age = '19' ]; do
        read -p 'Age of Nems ? ' age
    done

 Maintenant quand on test ce code :
 
     @utilisateur ~ % go run exemple.sh
     Age of Nems ? 30
     Age of Nems ? 15
     Age of Nems ? 20
     Age of Nems ? 18
     Age of Nems ? 19
     @utilisateur ~ % 
     
 ## For
 
 Quand on code une boucle _for_, il y a quatre mots de base :
 
        - for => veux dire POUR, début de la boucle
        - in => veux dire PARMIS
        - do => veux dire ALORS FAIT
        - done => veux dire TERMINÉ, fin de la boucle
        
Le code d'une boucle ressemblerai à cela :

    for _donnée_ in _ _donnée1_ _donnée2_ _donnée3_; do
        afficher/effectuer...
    done
  
Cela veux enfaite dire que, pour la donnée qui fait partie soit de la donnée 1, de la donnée 2 ou de la donnée 3, afficher/actuer l'action.
