# Recap de la semaine

Du 18 au 22 Mars 2018

1.  Bases de données Mysql
    
2.  Les formulaires php
    
3.  Organigramme d'algorithmie
    
4.  Fondamentaux Codewars
    
5.  Intervention métiers du numérique


### 1 Les Bases de données MySQL:

Créer une nouvelle base de données :
   •mysql> CREATE DATABASE *name*;

Afficher une base de données existante :
   •mysql> SHOW DATABASES;

Choisir une base de données dans la quelle créer une Table :
   •mysql> USE *name*;

Créer une Table:

   •mysql> CREATE TABLE *name*;

Afficher une Table:

   •mysql> SHOW TABLES *name*;

Afficher les informations (en tableau) d’une Table :
Mysql> DESCRIBE *name*;

### 2 Les formulaires PHP:

    • <form action=" " method="post"> 	
    • 	<div> 
    • 		<label for="name">Nom :</label> 
    • 		<input type="text" id="name" name="user_name">
    •  	</div>
    •  	<div> 
    • 		<label for="mail">e-mail :</label>
    •  		<input type="email" id="mail" name="user_mail"> 
    • 	</div> 
    • 	<div>
    • 		<label for="msg">Message :</label> 
    • 		<textarea id="msg name="user_message"> </textarea> 
    • 	</div> 
    • </form>
    • 
La méthode GET (celle qui est utilisée par défaut si rien n'est renseigné) fait circuler les informations du formulaire en clair dans la barre d'adresse en suivant le format ci-après :
http://www.unsite.com/chemin/script.php?var1=valeur1&var2=valeur2

    • La méthode POST, quant à elle, transmet les informations du formulaire 
    • de manière masquée mais non cryptée. 
    • Les informations utilisent le protocole HTTP et non HTTPS qui lui crypte les données.
Exemple :
http://wwww.google.fr/search?q=php

Ce qu’il faut bien comprendre : le client soumet son formulaire, le php l’envoie au serveur qui le traite, agit en conséquence des réponses données par l’utilisateur, et lui envoie une réponse (succès/redirection…)
Certaines restrictions existent dans la gestion des formulaires : temps, poids, nombre d’éléments au sein du formulaire... Ces restrictions peuvent être levées via le fichier php.ini

### 3 Organigramme d’algorithmie:

L’organigramme est un modèle à utiliser pour mettre en place des fonctions de manière optimale.
Le début est représenté en haut par une ellipse.
Il est suivi d’un parallélogramme contenant les paramètres.
Puis d’un rectangle à l’intérieur duquel se trouvent les instruction.
Ensuite, on trouve les conditions sous forme de losange (deux sorties : « oui » ou « non » ; ainsi que le reste de l’algorithme, jusqu’à la fin, matérialisée par une ellipse.

### 4 Fondamentaux CodeWars:
    • Modulo
	Si $nombre %2 == 0 alors, ce nombre est impair 
(le Modulo (%) donne le reste d’une division euclidienne)
 Ex: 9%2 = 1 (1 est le reste de la division).
    • -$nombre 
	donne l’opposé de nombre : 
	si $nombre= -19 , alors -$nombre = 19.
    • str_repeat ($chaine , $multiplicateur) 
	permet de répéter une chaîne de caractères 	$multiplicateur fois.

### 5 Intervention métiers du numérique:

Qui est Stan Chollet ?
Il est architecte réseau pour Dailymotion.
Le créateur d’Orléans Tech (Les organisateurs de conférence).
Ainsi que le créateur du projet Gazr (outil de rassemblement de langages/frameworks...).
Et le chef du projet Tartiflette.io (Outil facilitant la création d’interfaces de programmation).

Ses conseils
    • Mettre en valeur ses expériences variées en entretiens.
    • Et ne pas sous-estimer le côté humain.
    • Il est très important d’être CURIEUX.
    • En restant informé par la Veille Techno (ainsi que par les livres, les vidéos, etc..).
    • Postuler dans les entreprises correspondant à ses performances et son caractère. 
    • Ne pas hésiter d’y aller au « CULOT ».

Veilles de la semaine :
-Application web Can’t Unsee :
Can’t Unsee est une application intéressante et divertissante qui permet d’aiguiser l’œil en matière de design, et d’expérience utilisateur, avec des explications pour progresser : https://cantunsee.space
-L’accessibilité d’internet aux non-voyants
Mettre en place des procédés facilitant la compréhension d’une page web pour les non-voyants est relativement simple, et profitable à tous !







