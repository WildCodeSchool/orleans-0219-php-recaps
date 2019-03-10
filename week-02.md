#Récap de la semaine 2

Semaine consacrée aux Projets 1.

##Bootstrap - Le modal

###Qu'est-ce qu'un modal ?

Un modal est une "fenêtre" s'ouvrant sur l'écran après avoir cliqué sur un bouton ou un élément cliquable ayant les éléments "data-target = #xxx" (qui définit la cible) et "data-toggle = modal" (qui définit le modal). Il est essentiel d'appeler Bootstrap et son code en javascript.

- $('#myModal').on('shown.bs.modal', function () {
  $('#myInput').trigger('focus')
})

Pour relier le modal à l'élément cliquable, le code du modal doit contenir l'élement "id = #xxx" correspondant au "data-target". Cet id est placé sur la première ligne de code du modal, la même ligne qui contient la class "modal". Un modal peut contenir:

**Un header**

.. class = modal-header

**Un body**

.. class = modal-body

**Un footer**

.. class = modal-footer

Pour créer un bouton permettant de fermer le modal, il suffit d'ajouter l'élement "data-dismiss = modal" au bouton. Un modal est entièrement personnalisable.

##Git - Quelques rappels

Il est essentiel de ne pas travailler directement sur master et de faire ses propres branches. Elles doivent être nommées en fonction de la fonctionnalité développée, et non pas de façon personnelle. Il faut gérer et structurer des branches en fonction du travail réparti par le groupe.

###Les conflits

Les conflits apparaissent lorsqu'au moins deux personnes modifient une même partie de code et le merge/push à la suite. Git remarque automatiquement que les mêmes lignes ont été modifiées et rapportera donc le conflit à la dernière personne ayant effectué la modification. Il suffit simplement d'effectuer la modification manuellement (ou de forcer le changement) afin de guider Git.
