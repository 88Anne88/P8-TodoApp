# P8-Projet d'application "todoList" 
Ce projet fait parti du parcours Développeur d'application Front-End d'OpenClassrooms-P8.

Le but étant de reprendre et Optimiser un projet d'application "to-do list" existant.

Compétences évaluées:

    -Mettre en oeuvre des tests unitaires et fonctionnels dans une application web
    -Optimiser les performances d'un projet à l'aide des DevTools
    -Reprendre en main un projet JavaScript existant

Etape 1 : Correction des bugs

    Le premier est une faute de frappe.
    Le deuxième introduit un conflit éventuel entre deux IDs identiques.

Il y a également des améliorations proposées: 

    -optimisation de boucles 
    -annulation d'informations sur la console non nécéssaires

Etape 2 : Les tests

    -Ajout de tests unitaires et fonctionnels. 
L'objectif est de solidifier le projet. Ainsi, lorsqu'on le modifiera par la suite, 
on pourra se baser sur ces tests pour vérifier que l'on ne casse rien.

Il est nécessaire d'utiliser la commande  npm install  pour installer tous les fichiers Jasmine.

Il y a déjà un fichier existant pour les tests de ce projet :  ControllerSpec.js .  
À l'intérieur de ce fichier, les tests à ajouter sont indiqués dans le code. Ils sont indiqués avec le commentaire suivant :
// TODO: write test

Plus précisément, vous pouvez les trouver sur les lignes #62, #86, #90, #137, #141, #146, #150, #156, et #196 de  ControllerSpec.js .

Astuce : gagnez du temps en adoptant la méthode TDD. Comme beaucoup de développeur·ses, si vous rédigez vos tests et corrigez des bugs
en même temps, vous pouvez utiliser des tests pour identifier ce qui ne fonctionne pas - ce qui accélère la correction des bugs.

Etape 3 : Optimiser la performance

Réalisation d'un Audit de performance avec les outils de développement du navigateur Chrome (devtools et lighthouse).

Analyse de la performance d'un site concurrent: "todolistme.net" pour identifier ce qui marche bien et ce qui ne marche pas, 
au cas où l'on décide de "scaler" notre application.

Focus sur les ressources utilisées par les différents éléments du site (ce qui est lent, ce qui est rapide, etc),
et aux ressources utilisées par les publicités sur le site et celles utilisées pour effectuer les fonctionnalités 
"To-do" pour la liste elle-même.

L'audit se compose en 2 parties:

        -Comparatif de performance du site concurrent avec notre application 
        -Leviers d'optimisation de la performance de notre application

Etape 4 : Améliorer le projet

Ajout des informations supplémentaires à la documentation.
Ecriture de la documentation technique comportant les éléments suivants :

    -Le projet lui-même (l'usage non technique)
    -Comment il fonctionne techniquement (documentation fonctionnelle)
    -L'audit

Fichiers fournis

    -La base de code mise à jour avec les améliorations et les tests
    -La documentation technique du projet, y compris l'audit.

 
Presentation Orale:

Vous ferez une presentation de votre projet avec un évaluateur, afin de simuler des conditions réelles.
La présentation suivra la structure ci-dessous :

    Présentation de votre code, des tests et de vos optimisations : 15-20 minutes
    Questions / réponses : 10 minutes
    À la fin de votre présentation, l'évaluateur fera un débriefing pendant environ 5 minutes.

