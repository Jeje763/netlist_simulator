# DOURVILLE Jérémy netlist_simulator

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

Remarques
