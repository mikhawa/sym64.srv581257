# sym64.srv581257

Début : 29/09/2024

    symfony new sym64.srv581257 --version=lts --webapp

## Chargement d'entitées

Les dossiers `Entity` et `Repository`

https://github.com/mikhawa/EntitySymG2/tree/main/src

Installation pour apache

    composer require symfony/apache-pack

## Création de la base de données

    php bin/console doctrine:database:create

Ou

    php bin/console d:d:c

Puis création des tables

    php bin/console make:migration
    php bin/console ma:mi

et

    php bin/console doctrine:migrations:migrate
    php bin/console d:m:m

# Installation de mailjet-mailer

    composer require symfony/mailjet-mailer
    

## EasyAdmin
