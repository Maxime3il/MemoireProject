# MemoireProject

Tout d'abord, j'ai intialisé ma page d'acceuil pour choisir sa difficulté via une comboBox et un bouton pour quitter la page.
Ensuite, j'ai créé 3 vues pour différencier une partie difficile de facile et de normal.
De plus, chaque vue possède un controller très similaire avec quelques changement.
J'ai codé la partie controller du projet afin de réussir à sélectionner deux cartes et qu'elles se suppriment si elles sont identiques.
Après avoir fait l'essentiel du projet je suis passé à la gestion du timer et du score.
Enfin grâce au timer et au score je peux enfin savoir si oui ou non l'utilisateur gagne la partie.
J'ai attaqué la partie graphique du projet pour styliser les boutons, le fond de l'application et les label.
Pour ce qui est des cartes sur le plateau j'ai pas réussi à importer une image dos et une image face d'une carte. Alors j'ai fait avec des chaines de caractères. En effet, si la carte est retournée il y a marqué "button" sinon il y a marque l'id de la carte ("1", "2", "3" etc en fonction de la difficulté).
La difficulté change le nombre de paires à trouver et ne modifie pas le timer ni la méthode du calcul du score.
