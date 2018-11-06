# glossaire

1. Framework : Composants logiciels configurant « un cadre de travail » pour les développeurs web leur permettant de construire des sites grâce à une architecture « prête à l’emploi ».

2. FTP : File Transfert Protocol est un protocole de transfert de fichier. Il permet d’établir une connection entre le serveur et un poste local. Il est utile notamment pour les personnes qui développent un site internet en local et qui veulent par la suite le mettre en ligne. Port : 21

3. SFTP : Secure File Transfert Protocol, est identique au FTP classique, à la seule différence près, que celui-ci est sécurisé. Port : 22

4. Yoda condition: Faire une condition dans le sens inversé.


**Exemple:**

    if($var = true)
      echo "Cette condition sera toujours vraie car il manque un égal ($var == true).";
      
    if(true = $var)
      echo "Il y aura une erreur car on ne peut pas assigner de valeur à true.";

 
 Ça permet de débuguer plus facilement en cas d'erreur de syntax & c'est une norme sur certains frameworks (cc symfony).

5. VPS : Virtual Private Server, est un serveur qui est hébergé chez un fournisseur (OVH, et compagnies) et qui permet de mettre en place des services, serveur web, SFTP, FTP, etc... Le VPS est quand à lui hébergé sur une machine dite " hôte " qui elle même héberge plusieurs VPS, tout dépendra de la puissance de l'hôte.

6. Dedicated Server : Est une machine au même fonctionnalité que le VPS, sauf que cette fois-ci, la machine dite " hôte " plus haut est la vôtre, vous en faite ce que vous souhaitez, vous avez donc un accès total à la machine. Vous pouvez entre autre faire de la virtualisation (création de VPS), serveur de jeux, etc... En règle général on utilise ce genre de machine quand le service demande beaucoup de puissance. Par exemple : Un site Web qui a beaucoup de visiteur (Amazon, Twitter, Facebook, pour ne citer qu'eux).

7. Alias : Des " alias " permet de créer un raccourcie pour une commande sur le terminal. Par exemple : lorsque j'écrit dans un dossier " html5 ", celui-ci me copie automatiquement tout le boilerplate html 5.

8. Front-End : Le Front-End s'occupe de la partie visible d'un site Web, en prennant en compte le Mobile First, l'UX, l'UI, ainsi que la compatibilité de tout les navigateurs disponibles.


8. Front-End : Le Front-End s'occupe de la partie visible d'un site Web, en prennant en compte le Mobile First, l'UX, l'UI, ainsi que la compatibilité de tout les navigateurs disponibles.

9. Back-End : Contrairement au Front-End, le Back-End est celui qui gère le développement côté serveur, il dois prendre en compte les requêtes, la sécurité des informations (mot de passe par exemple). On passe d'ailleurs d'un site dite Static à Dynamique.

10. Mobile First : Le Mobile First consiste à faire le développement d'un site Web pour la version mobile en premier. Pourquoi ? Car aujourd'hui beaucoup plus de monde consulte un site Web sur son mobile plutôt qu'un ordinateur. Il permet de faire également ce qu'on appel le DRY : Dont Repeat Yourself.

11. UX : User Experience, est le terme anglophone désignant le fait qu'un site soit " User-Friendly ", est-ce que ce bouton soit bien placé ? Est-ce que ceci ressemble à un bouton ? Etc, l'UX est très important, un bon UX vous permettra de faire revenir le visiteur.

12. UI : User Interface, est ni plus ni moins que l'interface d'un site Web. L'UI et l'UX sont souvent complémentaire et ne vont jamais séparément.

13. DRY : Dont Repeat Yourself : est une méthode de travail, un développeur est faignéant au moins de code il tapera au mieux il se portera. Quand vous avez 3-4 fois le même code qui se répète alors il n'est pas en " DRY ".

14. RTFM : "Read The Fuc**** Manual !!!" 
Pour faire court, si la réponse à votre question se trouve dans la documentation, ne la posez pas, au risque de vous faire remballer. Lisez la documentation ! ;)
