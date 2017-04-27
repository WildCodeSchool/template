#Template de docummentation projet

##Objectifs

Description du projet : rappel du problème auquel répond le projet, qui est le client, qui sont les membres de l'équipe

##Prérequis

Quelles sont les librairies et autres soft à installer. Si possible donner les commandes unix, par example :

    sudo apt install composer
    npm install -g soft

Sinon mettre un lien vers la doc d'install du soft. Par exemple :

* composer ==> [https://getcomposer.org/doc/00-intro.md](https://getcomposer.org/doc/00-intro.md)

##Installation

Comment s'installe le projet sur une machine vierge ?

Exemple : 

    git clone https://github.com/WildCodeSchool/projet-intranet_hopital.git
    cd projet-intranet_hopital
    composer install
    bash bash/chmod.sh
    php app/console doctrine:database:create
    php app/console doctrine:schema:update --force
    php app/console doctrine:fixtures:load
    phpunit -c app

##Mise en prod

Décrire la procédure de mise en production comme si tu t'adressais à un Devops
