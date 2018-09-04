# glossaire

1. Framework : Composants logiciels configurant « un cadre de travail » pour les développeurs web leur permettant de construire des sites grâce à une architecture « prête à l’emploi ».

2. FTP : File Transfert Protocol est un protocole de transfert de fichier. Il permet d’établir une connection entre le serveur et un poste local. Il est utile notamment pour les personnes qui développent un site internet en local et qui veulent par la suite le mettre en ligne.

3. Yoda condition: Faire une condition dans le sens inversé.

**Exemple:**

    if($var = true)
      echo "Cette condition sera toujours vraie car il manque un égal ($var == true).";
      
    if(true = $var)
      echo "Il y aura une erreur car on ne peut pas assigner de valeur à true.";

 
 Ça permet de débuguer plus facilement en cas d'erreur de syntax & c'est une norme sur certains frameworks (cc symfony).
