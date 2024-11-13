# DOURVILLE Jérémy netlist_simulator
Exécution : 
L'éxécution se fait de la même manière que ce qui est fait dans le TP.

Choix de programmation : 
A tout instant ona deux environnement. 
  -Le premier pour les variables du tour de boucles précédent.
  -Le second pour les variables du tour actuel.

Convention choisies : 
-Tous les registres sont initialisés à false/tableau de false.
-Tous les equations de types RAM sont effectués à la fin.
-Les résulats de RAM sont donc obtenus avec le dictionnaires des variables du tour précédents.
(A chaque fin de tour de boucle, on recopie les valeurs des variables qui recoivent une RAM dans le nouvelles environnements.)
-Tous les registres sont initialisés à false/tableau de false.

Remarques : 
-Je n'ai pas vérifier la ROM car il n'y as pas de test fournis

Difficultés rencontrés lors du projet:
-J'ai eu des difficultés pour coder la RAM.
