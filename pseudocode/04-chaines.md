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

## Exo 3 - compterVoyelles
DEBUT
recevoir une chaine
  voyelles <- "aeiouy"
  compteur <- 0
  pour i allant de 0 à  longueur de la chaine - 1  FAIRE
    si vouelles contient chaine[i] ALORS 
    compteur <- compteur + 1
  fin si 
 fin pour 
 retourner compteur
FIN
