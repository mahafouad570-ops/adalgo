## Exo 1 - inverserChaine 
DEBUT
recevoir une chaine
  resultat <- ""
  pour i allant de longueur de la chaine - 1 à 0 FAIRE 
    resultat <- resultat + chaine[i]
 fin pour 
 retourner resultat 
FIN

## Exo 2 - estPalindrome
DEBUT
recevoir une chaine
  retourner chaine === inverserChaine(chaine)
FIN

