# Mon Projet de test "Codewriting Banckend Developer" en Symfony demander par IZICHANGE

Ce projet est une application Symfony conçue pour implémenter le CRUD (Create, Request, Update, Delete) pour pouvoir mettre à jour les données.

## Installation

1. Installer les pré-requis de Symfony 6.4 (LTS Version) en suivant le lien suivant : 

   https://symfony.com/doc/6.4/setup.html#technical-requirements

1. Clonez ce dépôt sur votre machine locale en utilisant la commande suivante :

   git clone https://github.com/alladeson/izichange-test-codewriting.git
   
2. Accédez au répertoire du projet :

  cd izichange-test-codewriting

3. Installez les dépendances en exécutant :

  composer install

4. Mettez à jour les informations de la base de données dans le fichier .env avec vos informations d'accès.

5. Exécutez les migrations de base de données :

  php bin/console doctrine:migrations:migrate

6. Démarrer le projet :

   symfony serve





