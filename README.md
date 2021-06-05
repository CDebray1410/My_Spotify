# Projet : Rush_Spotify
___
## Index
1. Infos générales
2. Fonctionnalités
3. Utilisation
4. Prérequis
___
## 1) Infos générales
### Nom du projet : Rush_Spotify
### Statut du projet : Fini
- Version : 1.0 
### Auteurs: 
- Christopher Debray ( linkedin : https://www.linkedin.com/in/christopher-debray/ )
- Amine Belkheiri ( linkedin : https://www.linkedin.com/in/amine-belkheiri/ )
- Edmond Loembe-sauthat ( linkedin : https://www.linkedin.com/in/edmond-loembe-24ba75206/ )
- Bryan Da-silva ( linkedin : https://www.linkedin.com/in/bryan-da-silva-developpeur-web/ )
### Répartition des tâches ( de manière générale ) :
- Front-end , React : Christopher Debray, Amine Belkheiri
- Back-end , API : Edmond Loembe-sauthat, Bryan Da-silva
### Objectif (résumé du sujet) :
- Développer un site en 2 jours ( Avec un autre projet de 2 semaines en parallèle ). Ce projet devra ressembler ( en terme de fonctionnalités ) au site **Spotify**.
### Restrictions :
- Le site devra être développé en React.
- Le site devra utiliser une API à créer ( en PHP ) qui sera en relation avec le front-end via React.
### Compétences Travaillées :
- React
- Création et utilisation d'une API
### Précisions sur le projet :
- Comme indiqué dans la répartition des tâches, il s'agit d'une répartition générale. Tout le monde à eu l'occasion de travailler sur la partie back-end et la partie front-end. Cela indique les parties sur lesquelles chaque membre à majoritairement travaillé.
- Les musiques et images étant récupérées via des URLs dont certaines sont plutôt anciennes, il est possible que certains éléments soit indisponible. 
___
## 2) Fonctionnalités :
### Fonctionnalités par page :
- *( Done )* Page **Accueil**. ( Liste les albums de manière aléatoire ).
- *( Done )* Page **Albums**. ( Liste les albums par ordre d'id dans la base de données ).
- *( Done )* Page **Genres**. ( Permet de trouver des albums par genre musical ).
- *( Done )* Page **Artistes**. ( Permet de sélectionner un artiste afin de consulter sa page ).
- *( Not Done )* Page **Recherche**. ( Permet de rechercher albums et artistes selon différents critères, **non implémenté** ).
___
### Fonctionnalités pour les albums :
***Chaque albums affichés peut être consultés, la page de détail d'un album contient :***
- L'année de sortie de l'album
- Sa popularité
- Son popularité
- Une description de l'album
___
### Fonctionnalités pour les artistes :
***La page de l'artiste séléctionné contiendra :***
- La description du style musical de l'artiste
- Sa biographie
- Une liste des albums que l'artiste à créé 
___
## 3) Utilisation :
Suivez bien les étapes ci-dessous !
### Étape 1 :
- Clonez ensuite le repository dans votre dossier **/htdocs** ou **/html** ( en général, il s'agit de l'endroit où sont stocké les sites pour le localhost ).
- Le dossier peut varier en fonction de si vous utilisez **MAMP**, **WAMP**, **LAMPP** ou **XAMPP**.
### Étape 2 :
- Pour pouvoir profiter de notre projet, vous devrez créer une base de données nommée **database_music**.
- Ensuite, il vous faudra importer le fichier **database_music.sql** dans la base données créée précédemment.
### Étape 3 :
- Dans le dossier API modifiez le fichier spotify.php ( vous allez modifiez les informations concerant la connexion à la base de données ) :
    - Ligne 10 changez ***UTILISATEUR*** et ***PASSWORD*** par le nom d'utilisateur et le mot de passe que vous utilisez pour accéder à votre phpMyAdmin
### Étape 4 :
- Une fois l'étape 3 fini , copier le dossier API dans la racine de votre localhost ( **/htdocs** ou **/html** en général )
### Étape 5 :
- Ouvrez un terminal dans le dossier que vous avez clonné
    - Utiliez la commande : npm install
    - Puis la commande : npm start
- Une fois cela fait vous serez redirigé vers le site, si ce n'est pas le cas :
    - Allez sur http://localhost:3000/ dans votre navigateur
### Étape 6 :
- Profitez du site !
___
## 4) Prérequis :
- LAMP / MAMP / XAMP