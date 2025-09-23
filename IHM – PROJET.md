IHM – PROJET

https://pellierd.github.io/homepage/teaching/hci/

Choix → Ember.js

Présentation TECHNOLOGIE:


    La cible applicative de la technologie choisie (mobile, web, etc.);
        Bien qu'il soit considéré comme un framework pour les sites web, Ember.js peut également être utilisé pour développer des applications de bureau et mobiles. L'exemple le plus marquant d'une application de bureau utilisant Ember est Apple Music.

    Les technologies concurrentes avec avantages et inconvénients;
    Angular et React 

    Ember.js 
        Avantages :  
            Extrême cohérence et configuration facile.
            Routeur intégré.
            Outil de débogage propre (Ember Inspector).
            Options de développement Full Stack.
            Liaison bidirectionnelle des données.
        
        Inconvénients :  
            La courbe d'apprentissage est raide. Ember n'est pas facile pour les débutants.
            Impossible de réutiliser les composants lorsque l'on travaille sur le framework Ember Js.
            L'un des frameworks les plus rigides et les plus lourds.
            Ne convient pas aux petits projets.
            Il existe un grand nombre de contenus et d'exemples liés à Ember qui sont obsolètes.

    Les acteurs du marché;
        Il est actuellement utilisé sur de nombreux sites web tels que Square, Discourse, Groupon, LinkedIn, Live Nation, Twitch et Chipotle. 

    Les outils associés à la technologie;
    Les principales références bibliographiques associées;
        https://github.com/emberjs/ember.js
        https://emberjs.com/ —- Documentation officiel
        https://en.wikipedia.org/wiki/Ember.js
        https://guides.emberjs.com/release/ —- guías 
        https://www.geeksforgeeks.org/javascript/ember-js-introduction/ 
        https://www.simform.com/blog/react-vs-ember/ -- technologies concurrentes


        https://github.com/discourse/discourse/tree/main --- 
    




    Les bases de la technologie :
    Au travers d'un exemple de type Helloworld tiré de votre projet IHM qui servira de base à la rédaction d'un tutoriel en ligne accessible à tous vos camarades;
    Les logiciels et librairies à installer.


Projet/développer l'IHM:


    Le cahier des charges donnant une description des fonctionnalités souhaitées de l'application (3 à 6 pages);
    Les scénarios d'utilisation entre 5 et 10;
    Le modèle de l'utilisateur cible de l'application (2 à 3 pages);
    Le modèle de tâches;
    Le modèle d'interface abstraite ou prototype papier;
    Le prototypage ou l'interface concrète.



Qu'est-ce que c'est Ember?

->  framework open-source JavaScript tourné vers les applications web
-> architecture de type MVC
-> est l'un des frameworks d'applications frontend qui connaît la plus forte croissance et le plus grand succès au niveau mondial.



- 


KACPER--------------------------------

* Les logiciels et librairies à installer:

- npm, yarn, ou pnpm (Node est inclut dans yarn et npm)
- Node.js (inclut dans yarn et npm)

- (git -> recommandé mais pas obligatoire)
- (Watchman peut être necessaire pour les utilisateurs Linux et Mac)

Installer ember avec la commande :
npm install -g ember-cli


* Au travers d'un exemple de type Helloworld tiré de votre projet IHM qui servira de base à la rédaction d'un tutoriel en ligne accessible à tous vos camarades:

A FAIRE A LA FIN


* Les bases de la technologie :

C'est un framework JavaScript web open-source qui utilise un pattern service-composant (???). Incorpore des pratiques, idioms et patterns des écosystemes single-page-app. 

Ember consiste de 5 concepts-clef:
- Routes : l'état de l'application est représenté par un URL. Chaque URL a un "route object" correspondant qui contrôle ce qui est visible à l'utilisateur
- Modèles : a chaque route est associée un modèle qui contient les données associées à l'état courant de l'application. Ces données peuvent être récupérées avec 
- Templates : templates sont utilisés pour construire le HTML de l'application et sont écrit dans le langage de template HTMLBars
- Composants (components) : se sont des balises personnalisées (custom tags) HTML. Leurs comportements sont implementés avec JavaScript et leur apparence est définie avec les templates HTMLBars. Les composants "possèdent" leurs données. Ils peuvent aussi être imbriqués (nested) et communiquer avec leur composant parent par les actions (évènements). D'autres librairies, telles que Polymer, peuvent être utilisées avec Ember.
- Services : se sont des objets singleton (???) qui tiennent des données de longue durée tels que les sessions utilisateurs. Ember fournit aussi des injections de dépendance, des "declarative one-way data-flow", des propriétés suivies et des mises à jour automatiques des templates.

Ember.js est un composant d'un stack front-end complet.

Ember CLI: définit la convention sur la configuration pour construire les outils.

Ember Data: une librairie de données persistantes qui fournit des installations de ORM (object-relationnal mapping).

Ember Inspector: une extension Firefox et Google Chrome pour le debugage des applications Ember.

Fastboot: un add-on CLI qui permet de faire marcher les applications dans Node.js.

Liquid Fire: fournit le support des animations pour les applications Ember. 


