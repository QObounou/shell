## DEFiNiTiON

### Qu'est-ce que le shell ?

Pour faire simple, le shell est entre autre ce qui permet le bon fonctionnement d'un ordre donné par un utisateur à sa machine.
Plus précisement le shell est interpréteur de commandes données par l'utilisateur de la machine, que notre *système d'exploitation* exécutera dans la foulée.

Pour mieux comprendre la notion du SHELL, je vais expliquer la notion de *système d'exploitation* puisque le shell fait partie à part entière de ce systyème.


### Le système d'exploitation

Le système d'exploiation, également connu sous le nom de OS (initiales de Operating System) est un environnement console, et aussi un programme de base qui contrôle les différents composants de l'apparteil informatique à la suite d'instructions du logiciel ou de l'utilisateur. 

L'OS sert entre autre à assruer la connection entre ce que l'ont appelle le HardWare (qui veux dire en français matériel), donc les composants matérielles de la machine, et le SoftWare (qui veux dire en français logiciel) qui correspond entre autre aux applications.

Le système d'exploition regroupe ces trois parties distinctes : le Kernel, puis le Shell et enfin les Applications.

https://www.google.com/imgres?imgurl=http%3A%2F%2Fwww.linux-france.org%2Fprj%2Fembedded%2Fsdcc%2Fimages%2Fos.png&imgrefurl=http%3A%2F%2Fwww.linux-france.org%2Fprj%2Fembedded%2Fsdcc%2Fsdcc_course.dev_os.html&tbnid=1BNkQWeAEx7FzM&vet=12ahUKEwjg2amqgs7tAhUPmhoKHRLgBAwQMygBegUIARCmAQ..i&docid=OxEimeBTiPRwLM&w=686&h=475&q=syst%C3%A9me%20d%27exploitation%20kernel%20shell%20app&ved=2ahUKEwjg2amqgs7tAhUPmhoKHRLgBAwQMygBegUIARCmAQ

   ### :Kernel:
    - Comme la traduction laisse à deviner, il s'agit du noyau du système d'exploitation                                                                                  
       
    - Gère les ressources et permet aux différents composants matériels et logiciels de communiquer entre eux  
       
    - Gestion des divers logiciels (tâche) de la machine ( lancement des programmes,…)
       
    - Gestion du matériel (mémoire, processeur, périphérique, stockage)
       
  ### :Shell:
    - Interface système ou coque logicielle
    
    - Communique avec l'OS par intermédiaire d'une langage de commande
   
    - Interpréteur de commande
    
  ### :Application: 
    - Programmme (ou logiciel) pour réaliser une tâche 
    
    - S'éxécute en utilisant les services de l'OS pour utiliser les ressources matérielles

=> Pour conclure sur cette notion de sysytème d'exploitation, on peux dire que l'OS est un programme système qui interconnecte le Kernel, le Shell et les Applications entre eux.


### Pour en finir sur le Shell

Le shell lui est un programme qui reçoit _des commandes_, tapper par l'utilisateur, qui ensuite va les transmettre au système d'exploitation, qui _les exécutera_.

L'utilisateur transmet les commandes au shell depuis le clavier, directement via le terminal de la console. 

Chaque machine à son terminal propre à sa marque, qui ne sont pas parametré de la même façon et n'ont pas forcément les même fonctionnalitées non plus. Mais celle-ci peuvent être changées pour intégrer un nouveau type de shell (chapitre que nous verrons prochainement). 

Le shell sert également a automatiser des actions, tout un code long a retapper, cela se nomme les Script Shell (que nous verrons par la suite).

 Le shell sert à :
     
     - intéragir avec le système de la machine
     - automatiser des actions avec le Script Shell
     - exécuter des commandes
     - créer, supprimer et modifier des fichiers et dossiers
     - explorer l'arborécance d'un système 
     - gérer les permissions
