# LES VARiABLES

## Qu'est-ce qu'une variable ?

En shell, et d'ailleurs presque partout en langage informatique, la notion de variable est commune. Une variable est ce qui sert pour marquer un 'nom' à un contenu. Elle permet de stocker temporairement des informatiormations en mémoire.

Une variable se créer comme cela :  

     var=exemple

Le nom _var_ à marquer le contenu _exemple_.

Pour mieux comprendre on peux faire l'exemple d'afficher le contenu de _var_.

Pour utilser le contenu d'une variable, il suffit simplement de mettre le signe $ avant la variable, sinon cela ne marchera pas.

Voici un exemple (echo permet d'afficher le contenu d'une fonction):
   
    @utilisateur ~ % var=exemple
    @utilisateur ~ % echo $var
    exemple
    @utilisateur ~ %

Le contenu d'une variable peut être modifié autant fois que l'ont souhaite. Tout comme le 'nom' du contenu qui ne se supprimera pas tant que la variable existera.
De plus pour être bien sur que nous sommes dans un script, il faut qu'il y est #!/bin/bash dans le contenu du fichier où est situé la variable, sinon cela ne marchera pas.

Il y a aussi les  variables que nous n'avons pas créer, qui sont déjà contenu dans notre système. Il s'agit des variables d'environnement.
Ces variables sont exclusivement écrites en majuscule. 


En voilà quelques unes : USER (ou LOGNAME) = nom de l'utilisateur  •  HOME = nom du répertoire personnel  •  SHELL = nom du shell utilsé  •  PATH =  liste de répertoires dans lesquels le shell va chercher les commandes  •  EDITOR (ou VISUAL) =  nom de l'éditeur de textes préféré 

#### Variable dans Script Shell

Nous pouvons illustrer ceci à travers un exemple.

Nous allons créer un ficher shell puis ensuite modifier le contenu du fichier pour y écrire un petit programme. Après il faudra lui donner les permissions et ensuite tester le fichier.

       @utilisateur ~ % touch test.sh
       @utilisateur ~ % cat test.sh
       var=exemple
       
       echo $var
       @utilisateur ~ % chmod 777 test.sh
       @utilisateur ~ % go run test.sh
       exemple
       @utilisateur ~ %
       
Voilà à travers l'exemple, le principe d'une variable dans Scrpt Shell.
