# COMMANDE DE BASE

En effet, les commandes dans shell sont quasiment les même que pour une programmation en go, c, ...

Nous allons lister les pricipales commandes en précisant leurs utilisations pour mieux les comprendres et les utilsées.

### C'est parti

    ls
_ls_ permet de lister les ficher d'un repertoire. 

_ls -.._ est une autre forme de _ls_ . Dans les points, on peux y mettre un a, h, l, qui auront chacun leurs spécificités propre au fait de lister.

Par exemple, ls -a affiche tous les fichiers et répertoires même ceux cachés du répertoire.

    man
_man_ sert a se renseigner sur l'utilisation d'une commande et sa définition. Pour l'utilser, il faut juste précédé la commande par _man_.

    cd
_cd_ permet de changer de dossier, repertoire dans lequel en se trouve. Il suffit de faire _cd_ suivi du nom du dossier dans lequel on veux aller. On peut également revenir au répertoire précédant en faisant _cd .._ .

    touch
_touch_ permet de créer un fichier

    mkdir
_mkdir_ permet de créer un dossier

    chmod
_chmod_ est une commande qui gère les permissions. Une façon de l'utiliser est de mettre à la suite du nom de la commande, indiquer les 3 chiffres en fonction des permissions que l'ont souhaite puis le nom du ficher, programme à qui on veux donner une permission. 

    chown
_chown_ sert a changer le propriétaire.

    sudo
_sudo_ est la commande qui permet de forcer notre machine a faire la commmande suivante.

    pwd
_pwd_ permet de savoir dans quel répertoire nous nous trouvons.

    rm
_rm_ permet de supprimer un ficher. _rm -d_ supprime lui un dossier.

    cat
_cat_ sert a modifier le contenu d'un fichier.

    cp
Comme les initiales laissaient à deviner, _cp_ sert à copier/coller un ficher, ou dossier.
