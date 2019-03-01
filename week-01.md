# Récapitulatif de la semaine 01

## _UNIX_

### Qu’est-ce qu’UNIX ?

UNIX est un sytème d’exploitation basé sur un interpréteur, le *shell* et de nombreux petits utilitaires, chacun accomplissant une action spécifique et étant appelé depuis la ligne de commande d’un terminal.

Dans UNIX, les fichiers sont organisés de façon arborescente depuis la racine /.
Ces mêmes fichiers sont référencés par un chemin dans l’arborescence. Ex. : /usr/dossier_machin/fichier_bidule.md


### Quelques commandes apprises :

* *_pwd_* : affiche le répertoire de travail et son chemin.
* *_mkdir_* : créé un répertoire
* *_touch_* : permet de créer un fichier vide s’il n’existe pas ; ou met à jour le fichier s’il existe déjà
* *_cd_* : change de répertoire de travail
  *_cd .._* : remonte dans le répertoire précédent
  *_cd -_* : descend dans le répertoire suivant
* *_ls_* : liste le contenu d’un répertoire
* *_chmod_* : change les droits d’un fichier
* *_man_* : affiche le manuel


***


## _Git_

### Qu'est-ce que Git ?

Git est un logiciel de gestion de versions décentralisé créé par Linus Torvalds (a.k.a.	créateur du noyaux Linux).

Git est donc un logiciel qui permet de stocker un ensemble de fichiers en conservant la chronologie de toutes les modifications qui ont été effectuées dessus. Il permet notamment de retrouver les différentes versions d'un lot de fichiers connexes.

Mais Git ne repose pas sur un serveur centralisé, il utilise un système de connexion pair à pair. Le code informatique développé est stocké non seulement sur l’ordinateur de chaque contributeur du projet, mais il peut également l'être sur un serveur dédié. C'est un outil de bas niveau, qui se veut simple et performant, dont la principale tâche est de gérer l'évolution du contenu d'une arborescence.


### Quelques commandes apprises :

* *_git status_* : donne la situation actuelle
* *_git init_* : crée un nouveau dépôt;
* *_git clone_* : Télécharge un dépôt local ou distant
… *_git clone_ /chemin/vers/dossier* pour télécharger un dépôt local
… *_git clone_ <username>@<url> /chemin/* pour télécharger un dépôt distant
* *_git add_* : Sauvegarde des changements
… *_git add all_* : sauvegarde dos les changements
* *_git commit_* : enregistre les modifications
* *_git branch_* : créé une nouvelle branche
… *_git checkout -b_ nom_branche* : crée et déplace dans la branche
… *_git branch -b_ nom_branche* : supprime la branche
… *_git checkout_ nom_branche* : déplace dans la branche
* *_git merge_* : fusionne une branche dans une autre
* *_git push_* : publie (« pousse ») les modifications vers le dépôt distant
… *_git push_ origin master* : envoi du « master » vers le dépôt central « origin »
* *_git pull_* : récupère les dernières modifications distantes et les fusionnent dans la branche courante



***

## _Bootstrap_

### Qu’est-ce que [*Bootstrap*](https://getbootstrap.com/docs/4.0/getting-started/introduction/) ?

*Bootstrap* est une collection d’outils (framework) pour la création du design de sites ou d’applications web.
C’est un ensemble qui contient des codes html et css, des formulaires, des boutons, des outils de navigations et d’autres éléments interactifs ; avec des extensions *Javascript* en option.

Bootstrap est compatible avec les dernières versions des principaux navigateurs et adopte la conception de sites web *responsive* (i.e. « adaptatifs » en french) permettant aux projets de s’adapter dynamiquement au format des supports depuis lesquels ils sont accédé (PC, tablettes, smartphone)


### Sytème de grille de Bootstrap

Boostrap dispose d’un système de grille, basé sur des *flexbox*, qui gère l’alignement des éléments de la page.
La grille est donc basée sur des colonnes. 12 pour être précis.
Les débordements de la grille sont automatiquement gérés par un retour à la ligne.

Boostrap définit cinq taille d’écrans pour son système de grille :
… * _xs_ pour les smartphones (< 576px)
… * _sm_ pour les tablettes au format portrait ( 576px)
… * _md_ pour les tablettes au format paysage ( 768px)
… * _lg_ pour les écrans de bureau ( 992px)
… * _xl_ pour les grands-écrans ( 1200px)


### Quelques indispensables :

* Le CSS de Bootstrap doit être appelé dès le début du fichier HTML, dans le <head>, et avant nos propres feuilles de style.
* Pour la bonne prise en compte du *responsive* sur tous les écrans, il faut ajouter une <meta viewport>.
* si besoin, les fichiers Javascript doivent être appelés à la fin du fichier HTMl avant >/body>
* La classe _container_ : *.container*. Elle permet d’englober le contenu du site.
* La classe _row_ : *.row*. Elle permet de créer des groupes horizontaux de colonnes.
* La classe _col_ : *.col*. Le contenu doit être placé dans des colonnes et seules les colonnes peuvent être des enfants directs des _row_.
