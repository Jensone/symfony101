# symfony101

Super checklist pour accompagner les devs dans la conception d'application web avec le framework Symfony

## Modélisation

[ ] Créer un diagramme de cas d'utilisation
[ ] Créer un diagramme de classe
[ ] Créer un diagramme de séquence
[ ] Créer un schéma de la base de données
[ ] MCD et MLD (Facultatif)

---

## Assets

[ ] Webdesign (maquettes, identité visuelle)
[ ] Médias (images, vidéos, audio)
[ ] Police d'écriture
[ ] Librairie CSS

---

## Outils & Technique

[ ] Éditeur de code (VSCode, PHPStorm)
[ ] Version de PHP (dépendant de Symfony 5 ,6 ,7)
[ ] Composer (dernière version)
[ ] Installer Symfony-CLI
[ ] Git
[ ] GitHub ou GitLab
[ ] Docker (Facultatif)

---

## Bootstrapping

[ ] Créer un nouveau projet Symfony
[ ] Installer les dépendances
[ ] Configurer le `.env`
[ ] Créer la base de données
[ ] Créer les entités
[ ] Créer les fixtures
[ ] Créer les contrôleurs
[ ] Créer les vues
[ ] Créer les formulaires
[ ] Créer les tests

---

## Tests

[ ] UnitTest Case
[ ] WebTest Case
[ ] Tests des entités

---

## Base de données

[ ] Sélectionner un type de SGBDR
[ ] Contrôller l'ensemble du schéma et des types

---

## Déploiement

[ ] Acheter un nom de domaine
[ ] Choisir un hébergement web
[ ] Rattacher le nom de domaine au serveur (si besoin)
[ ] Définir le dossier public comme cible de la racine de l'application
[ ] Créer une base de données sur le serveur de production
[ ] Mettre en plen un seul fichier de version de migration
[ ] Faire la compilation des éléments JS (si besoin)
[ ] Mettre le fichier .env (APP_ENV, DATABASE_URL, MAILER_DSN, etc.)
[ ] Générer un .htaccess `composer require symfony/apache-pack`
[ ] Commit et Push du projet vers GithHub ou GitLab
[ ] Cloner le projet sur le serveur de production avec git clone
[ ] Renommer le dossier de l'application (www, public_html, etc.).
[ ] Se connecter en SSH au terminal du serveur
[ ] Installer les dépendances avec `composer install`
[ ] Exécuter la migration avec `php bin/console d:m:m`
[ ] Nettoyer le cache avec `APP_ENV=prod APP_DEBUG=0 php bin/console cache:clear`
[ ] Préchauffer le cache avec `php bin/console cache:warmup`
[ ] Optimiser l'application avec `composer install --no-dev --optimize-autoloader`
[ ] Vérifier que l'application est bien en ligne
[ ] Vérifier le bon fonctionnement des routes, formulaire etc.


## Conception
## Sécurité
