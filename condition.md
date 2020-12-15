# LES CONDiTiONS

## Qu'est-ce qu'une condition ?

Une condition permet d'exécuter une opération SI la contidion est vérifiée par le programme.

Autrement dit, SI la réponse rentre dans les critères de la condition, ALORS cela affichera un certain résulat. Et SI la réponse ne rentre pas dans les critères de la condition, ALORS il affichera un autre résultat.

## Code

Pour coder une condition, il y a cinq mots de base :

      - if => veux dire SI, début d'une condition
      - else => veux dire SINON
      - elif => veux dire SINON SI
      - then => veux dire ALORS
      - fi => veux dire FIN, fin d'une condition
 
 Cela resemblera à cela :
 
    if [condition a vérifer], then
      si la condition est vérifiée, afficher/effectuer ...
    else
      si la condition n'est pas vérifiée, afficher/effectuer ...
    fi
 
## Exemple

Si la condtion est vérifié, alors le résulat sera 'Ok', si se sera 'beau travail'.

Tout d'abord le _code_ 

      if [ $1 = "VA"], then
            echo "Ok"
      else
            echo "beau travail"
      fi

Maintenant quand on test le code qui codé en shell

      @utilisateur ~ % go run exemple.sh WHATS UP
      beau travail
      @utilisateur ~ % go run exemple.sh VA
      Ok
      @utilisateur ~ %

## Comparer des nombres, valeur, ..

Il y a la commande double parenthèse (()) et la commande entre crochet [ ] .
        
      (( val == vel)) => vérifie si val est égal à vel <= [ $val -eq $vel ]
      (( val != vel)) => vérifie si val n'est pas égal à vel <= [ $val -ne $vel ]
      (( val >= vel)) => vérifie si val est supérieur ou égal à vel <= [ $val -ge $vel ]
      (( val <= vel)) => vérifie si val est inférieur ou égal à vel <= [ $nb1 -le $nb2 ]
      (( val > vel)) => vérifie si val est strictement supérieur à vel <= [ $val -gt $vel ]
      (( val < vel)) => vérifie si val est strictement inférieur à vel <= [ $val -lt $vel ]
