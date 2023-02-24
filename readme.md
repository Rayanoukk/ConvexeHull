# <center>**Projet Enveloppe Convexe dans le plan Prog-C**</center>
&nbsp;
### **Membres du groupe :** 
- ### Salem SAOUDI **TD04 / TP06** 
- ### Rayan OUKACI **TD03 / TP06**

&nbsp;

## Mode de fonctionnement:


1. Ou trouver nos fichiers exécutables ?
     Dans un dossier nommé L2S3.Projet.OUKACI.SAOUDI.zip vous trouverez 3 fichiers :

     <b>env_convexes_p1.c<b> : Le programme en c de notre premiere partie du projet .

     <b>env_convexes_p2.c<b> : Le programme en c de notre deuxieme partie du projet .

     <b>README <b> : Un fichier markdown pour expliquer brievement le fonctionemment de notre projet .


2. Fonctionnement de la compilation :

    La compliation des 2 programmes ce fait comme suit : 
    (clang -std = c17 -Wall env_convexes_p1.c -o env_convexes_p1 -lMLV)
    (clang -std = c17 -Wall env_convexes_p2.c -o env_convexes_p2 -lMLV)


3. Fonctionnement de l'interface graphique  :
    Bibliotheque de travaille : MLV.

    Apre l'exécution un menu s'affiche avec 2 choix possible : 

    <b>Souris<b> : Comme son nom l'indique ça sera la partie ou c'est a l'utilisateur de cliquer sur des points pour afficher son convexe,
        l'utilisateur pourra commencer a jouer juste apre .

    <b>Aleatoire<b> : Comme son nom l'indique aussi ça sera donc la partie ou les points se génere de maniere aleatoire,
     apre la selection plusieure choix possibles: 
        Forme du convexe : Carré ou cercle .
    <br>
        Mode d'affichage : Point par point ou mode terminal
              
4. Explications des modes d'affichages : 
    <br>
    Point par point: où l'utilisateur sera en mesure de voir l'évolution du convexe étape par étape jusqu'à la fin .
    <br>
    Mode terminal: ou l'utilisateur ne verra que le résultat final de son convexe comme il est indiqué dans l'enoncé.

5. Porte de sortie : 
    Pour terminer a l'exécution  cliquez simplement sur le bouton quitter de la fenêtre , 
    puis toutes les cellules du programme sera libéré correctement .

##  Ce qui marche ? ce qui ne marche pas ? :

    Toutes les taches demendées ont été reussites (a confirmer avec nos professeurs)
     et certains bonus on été ajouté notament les commentaires doxygen .

## Ameliorations possibles 
    Par faute de temps on aurait aimé ameliorer notre menu pour faciliter mieux l'acces aux programmes
    notament pour recommencer ou pour revienir aux menu principal et changé facilement les differents mode de jeu proposés 

## Repartition 

    Le projet tout entier a été fait par les 2 binomes en groupe notre entente et le fait d'habiter prés l'un de l'autre nos 
    a permis de s'entraider dans les moindres details du projet