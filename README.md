# Les objectifs
Le but de cet exercice est de mettre en pratique les éléments principaux abordés durant la
partie théorique sur le versionning de code source avec Git. Il vous est demandé de réaliser un projet
qui servira de support au travail d’équipe via Git. Ce projet consiste à réaliser un programme en ligne
de commande appelé “bmpfilter” qui permet d’appliquer des filtres prédéfinis sur une image au
format bitmap (voir ses caractéristiques ici) encodée en 24bpp (24 bits par pixel). L'exécution du
programme se fait selon l’usage suivant :

./bmpfilter <bmp_file_path> [red|green|blue|blur|mirror]

Ce programme prend en entrée le chemin vers un fichier bitmap 24bpp valide, applique un ou
plusieurs filtres à cette image dans l’ordre des arguments passés dans la ligne de commande, et crée
le fichier bitmap 24bpp résultant au même emplacement que le fichier original avec le suffixe “_mod”
ajouté à son nom.
Le programme est à réaliser en C (ANSI). L’objectif principal n’étant pas la révision du langage C mais
bien l’expérimentation des commandes Git dans un cadre pseudo-réaliste, chaque groupe projet
disposera d’une archive de départ comportant le code source avec des méthodes vides qu’il faudra
compléter en suivant les consignes données.
