# Slim Framework 3 Skeleton Application

Use this skeleton application to quickly setup and start working on a new Slim Framework 3 application. This application uses the latest Slim 3 with the PHP-View template renderer. It also uses the Monolog logger.

This skeleton application was built for Composer. This makes setting up a new Slim Framework application quick and easy.

## Install the Application

Run this command from the directory in which you want to install your new Slim Framework application.

php composer.phar create-project slim/slim-skeleton [my-app-name]

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

* Point your virtual host document root to your new application's `public/` directory.
* Ensure `logs/` is web writeable.

To run the application in development, you can also run this command. 

php composer.phar start

Run this command to run the test suite

php composer.phar test

That's it! Now go build something cool.


Internaute

1. En tant qu'internaute non-connecté, je dois me connecter pour accéder aux fonctionnalités d'utilisateur ou d'administrateur (y compris la liste des films).

Utilisateur

1. En tant qu'utilisateur, j'accède à la page d'accueil du site pour consulter la liste des films disponibles.
2. En tant qu'utilisateur, je peux trier la liste des films par titre, durée ou année de sortie.
3. En tant qu'utilisateur, je peux rechercher un film dans la liste par mot-clé (présent dans le titre ou le résumé de celui-ci).
4. En tant qu'utilisateur, je peux filtrer les films de la liste par disponibilité.
5. En tant qu'utilisateur, depuis la liste, je peux ajouter un ou plusieurs films à mon panier.
6. En tant qu'utilisateur, depuis la liste, je peux accéder à mon panier afin de consulter la liste des films que je veux emprunter.
7. En tant qu'utilisateur, depuis mon panier, je peux valider ce panier pour emprunter les films.
8. En tant qu'utilisateur, depuis mon panier, je peux retourner à la liste des films.

En tant qu'utilisateur, lorsque je valide mon panier, je suis ramené à la liste des films.
En tant qu'utilisateur, lorsque je valide mon panier, mon panier est vidé.
En tant qu'utilisateur, lorsque je valide mon panier, les films empruntés sont affichés sur la liste des films mais indiqués comme empruntés.
En tant qu'utilisateur, depuis la liste des films, je peux rendre un ou plusieurs films qui sont alors à nouveau disponibles.

Administrateur

1. En tant qu'administrateur, depuis la liste des films, je peux supprimer un film.
2. En tant qu'administrateur, depuis la liste des films, je peux accéder à l'écran d'ajout des films.
3. En tant qu'administrateur, depuis la liste des films, je peux accéder à l'écran de modification de chaque film.
4. En tant qu'administrateur, depuis l'écran de modification d'un film, je peux modifier tous les champs d'un film sauf le titre.

En tant qu'administrateur, depuis l'écran d'ajout des films, je peux chercher des films via l'API OMDB puis les ajouter à la liste.
En tant qu'administrateur, lorsque je supprime un film, un écran de confirmation me permet de confirmer ou non mon choix.