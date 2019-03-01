{\rtf1\ansi\ansicpg1252\cocoartf1404\cocoasubrtf470
{\fonttbl\f0\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;}
\paperw11900\paperh16840\margl1440\margr1440\vieww25400\viewh14500\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f0\fs22 \cf0 \CocoaLigature0 #R\'e9capitulatif de la semaine 01\
\'97\'97\'97\
\
##_UNIX_\
\
###Qu\'92est-ce qu\'92UNIX ?\
\
UNIX est un syt\'e8me d\'92exploitation bas\'e9 sur un interpr\'e9teur, le *shell* et de nombreux petits utilitaires, chacun accomplissant une action sp\'e9cifique et \'e9tant appel\'e9 depuis la ligne de commande d\'92un terminal.\
\
Dans UNIX, les fichiers sont organis\'e9s de fa\'e7on arborescente depuis la racine /.\
Ces m\'eames fichiers sont r\'e9f\'e9renc\'e9s par un chemin dans l\'92arborescence. Ex. : /usr/dossier_machin/fichier_bidule.md\
\
\
### Quelques commandes apprises :\
\
* *_pwd_* : affiche le r\'e9pertoire de travail et son chemin.\
* *_mkdir_* : cr\'e9\'e9 un r\'e9pertoire\
* *_touch_* : permet de cr\'e9er un fichier vide s\'92il n\'92existe pas ; ou met \'e0 jour le fichier s\'92il existe d\'e9j\'e0\
* *_cd_* : change de r\'e9pertoire de travail\
\'85 *_cd .._* : remonte dans le r\'e9pertoire pr\'e9c\'e9dent\
\'85 *_cd -_* : descend dans le r\'e9pertoire suivant\
* *_ls_* : liste le contenu d\'92un r\'e9pertoire\
* *_chmod_* : change les droits d\'92un fichier\
* *_man_* : affiche le manuel\
\
\
\
***\
\
##_Git_\
\
###Qu'est-ce que Git ?\
\
Git est un logiciel de gestion de versions d\'e9centralis\'e9 cr\'e9\'e9 par Linus Torvalds (a.k.a.	cr\'e9teur du noyaux Linux).\
\
Git est donc un logiciel qui permet de stocker un ensemble de fichiers en conservant la chronologie de toutes les modifications qui ont \'e9t\'e9 effectu\'e9es dessus. Il permet notamment de retrouver les diff\'e9rentes versions d'un lot de fichiers connexes.\
\
Mais Git ne repose pas sur un serveur centralis\'e9, il utilise un syst\'e8me de connexion pair \'e0 pair. Le code informatique d\'e9velopp\'e9 est stock\'e9 non seulement sur l\'92ordinateur de chaque contributeur du projet, mais il peut \'e9galement l'\'eatre sur un serveur d\'e9di\'e9. C'est un outil de bas niveau, qui se veut simple et performant, dont la principale t\'e2che est de g\'e9rer l'\'e9volution du contenu d'une arborescence.\
\
\
###Quelques commandes apprises :\
\
* *_git status_* : donne la situation actuelle\
* *_git init_* : cr\'e9e un nouveau d\'e9p\'f4t;\
* *_git clone_* : T\'e9l\'e9charge un d\'e9p\'f4t local ou distant\
\'85 *_git clone_ /chemin/vers/dossier* pour t\'e9l\'e9charger un d\'e9p\'f4t local\
\'85 *_git clone_ <username>@<url> /chemin/* pour t\'e9l\'e9charger un d\'e9p\'f4t distant\
* *_git add_* : Sauvegarde des changements\
\'85 *_git add all_* : sauvegarde dos les changements\
* *_git commit_* : enregistre les modifications\
* *_git branch_* : cr\'e9\'e9 une nouvelle branche\
\'85 *_git checkout -b_ nom_branche* : cr\'e9e et d\'e9place dans la branche\
\'85 *_git branch -b_ nom_branche* : supprime la branche\
\'85 *_git checkout_ nom_branche* : d\'e9place dans la branche\
* *_git merge_* : fusionne une branche dans une autre\
* *_git push_* : publie (\'ab\'a0pousse\'a0\'bb) les modifications vers le d\'e9p\'f4t distant\
\'85 *_git push_ origin master* : envoi du \'ab\'a0master\'a0\'bb vers le d\'e9p\'f4t central \'ab\'a0origin\'a0\'bb\
* *_git pull_* : r\'e9cup\'e8re les derni\'e8res modifications distantes et les fusionnent dans la branche courante\
\
\
\
***\
\
##_Bootstrap_\
\
### Qu\'92est-ce que [*Bootstrap*](https://getbootstrap.com/docs/4.0/getting-started/introduction/) ?\
\
*Bootstrap* est une collection d\'92outils (framework) pour la cr\'e9ation du design de sites ou d\'92applications web.\
C\'92est un ensemble qui contient des codes html et css, des formulaires, des boutons, des outils de navigations et d\'92autres \'e9l\'e9ments interactifs ; avec des extensions *Javascript* en option.\
\
Bootstrap est compatible avec les derni\'e8res versions des principaux navigateurs et adopte la conception de sites web *responsive* (i.e. \'ab\'a0adaptatifs\'a0\'bb en french) permettant aux projets de s\'92adapter dynamiquement au format des supports depuis lesquels ils sont acc\'e9d\'e9 (PC, tablettes, smartphone)\
\
\
###Syt\'e8me de grille de Bootstrap\
\
Boostrap dispose d\'92un syst\'e8me de grille, bas\'e9 sur des *flexbox*, qui g\'e8re l\'92alignement des \'e9l\'e9ments de la page.\
La grille est donc bas\'e9e sur des colonnes. 12 pour \'eatre pr\'e9cis.\
Les d\'e9bordements de la grille sont automatiquement g\'e9r\'e9s par un retour \'e0 la ligne.\
\
Boostrap d\'e9finit cinq taille d\'92\'e9crans pour son syst\'e8me de grille :\
\'85 * _xs_ pour les smartphones (< 576px)\
\'85 * _sm_ pour les tablettes au format portrait ( 576px)\
\'85 * _md_ pour les tablettes au format paysage ( 768px)\
\'85 * _lg_ pour les \'e9crans de bureau ( 992px)\
\'85 * _xl_ pour les grands-\'e9crans ( 1200px)\
\
\
### Quelques indispensables :\
\
* Le CSS de Bootstrap doit \'eatre appel\'e9 d\'e8s le d\'e9but du fichier HTML, dans le <head>, et avant nos propres feuilles de style.\
* Pour la bonne prise en compte du *responsive* sur tous les \'e9crans, il faut ajouter une <meta viewport>.\
* si besoin, les fichiers Javascript doivent \'eatre appel\'e9s \'e0 la fin du fichier HTMl avant >/body>\
* La classe _container_ : *.container*. Elle permet d\'92englober le contenu du site.\
* La classe _row_ : *.row*. Elle permet de cr\'e9er des groupes horizontaux de colonnes.\
* La classe _col_ : *.col*. Le contenu doit \'eatre plac\'e9 dans des colonnes et seules les colonnes peuvent \'eatre des enfants directs des _row_.\
\
\
\
\
}