 Rapport de développement du projet
.+++++++++++Introduction

Ce rapport décrit les étapes de développement, les problèmes rencontrés et les solutions apportées pour un projet de développement web. 
Ce projet consiste en une application web de galerie de photos permettant aux utilisateurs de créer des albums, 
d'ajouter des images à ces albums et de les visualiser.
Étapes de développement

    +++++++++++Création de la structure de base de l'application

La structure de base de l'application a été créée en utilisant Node.js, Express et EJS. 
Cette structure comprend les fichiers et dossiers nécessaires pour gérer les routes, 
les vues et les données de l'application.

    +++++++++++++Création de la page d'accueil

La page d'accueil a été créée en utilisant HTML et EJS. 
Cette page affiche un message de bienvenue et un lien vers la page des albums.

    +++++++++++++Création de la page des albums

La page des albums a été créée en utilisant HTML et EJS. 
Cette page affiche une liste des albums existants et un lien pour créer un nouvel album.

    +++++++++++Création de la page de création d'un nouvel album

La page de création d'un nouvel album a été créée en utilisant HTML et EJS. 
Cette page affiche un formulaire permettant à l'utilisateur de saisir le nom de l'album et de le créer.

    ++++++++++++Création de la page de visualisation d'un album

La page de visualisation d'un album a été créée en utilisant HTML et EJS. 
Cette page affiche les images de l'album et un formulaire pour ajouter une nouvelle image.

    +++++++++++Ajout de la fonctionnalité d'ajout d'une image

La fonctionnalité d'ajout d'une image a été ajoutée en utilisant HTML, EJS et JavaScript. 
Cette fonctionnalité permet aux utilisateurs d'ajouter des images à un album existant 
en utilisant un formulaire HTML et EJS valide et fiable.
Problèmes rencontrés

    ++++++++++++Problèmes de validation de formulaire

Lors de la validation des formulaires, des messages d'erreur étaient affichés même si les données saisies étaient valides. 
Ce problème a été causé par une mauvaise utilisation des attributs HTML required et pattern.
Solutions apportées

    +++++++++++Correction de la validation de formulaire

Pour résoudre le problème de validation de formulaire, les attributs HTML required et pattern ont été correctement utilisés. 
Les messages d'erreur ne sont désormais affichés que lorsque les données saisies sont invalides.

    +++++++++++Problèmes de gestion des images

Lors de l'ajout d'images, des problèmes de gestion des fichiers ont été rencontrés. 
Ces problèmes ont été causés par une mauvaise utilisation des fonctions de gestion de fichiers de Node.js.
Solutions apportées

    ++++++++++Correction de la gestion des images

Pour résoudre les problèmes de gestion des images, les fonctions de gestion de fichiers de Node.js ont été correctement utilisées. 
Les images sont désormais correctement ajoutées à l'album sélectionné.

++++++++++++Conclusion

Ce rapport décrit les étapes de développement, les problèmes rencontrés et les solutions apportées pour un projet de développement web. 
Grâce à ces étapes, les utilisateurs peuvent désormais créer des albums, ajouter des images à ces albums et les visualiser en utilisant une application web fiable et fonctionnelle. 
Les problèmes de validation de formulaire et de gestion des images ont été résolus, garantissant ainsi une expérience utilisateur optimale.