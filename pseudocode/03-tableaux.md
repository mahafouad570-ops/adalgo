## Exo 1 - maximum
 DEBUT
 recevoir un tableau
   max <- tableau[0]
   pour i allant de 0 à longueur du tableau - 1 FAIRE
  si tableau[i] > max ALORS
   max <- tableau[i]
  FIN SI
  FIN POUR
   retourner max
FIN

## Exo 2 - minimum
 DEBUT
 recevoir un tableau
   mini <- tableau[0]
   pour i allant de 0 à longueur du tableau - 1 FAIRE
  si tableau[i] < mini ALORS
   mini <- tableau[i]
  FIN SI
  FIN POUR
   retourner mini
FIN

## Exo 3 - moyenne
DEBUT
recevoir un tableau
  si longueur du tableau === 0 ALORS
    retourner null
 fin si 
  total <- 0
  pour i allant de 0 à longueur du tableau - 1 FAIRE
    total <- total + tableau[i]
 fin pour 
 retourner total / longueur du tableau
FIN

## Exo 4 - contient
DEBUT
recevoir un tableau et une valeur
  pour i allant de 0 à longueur du tableau - 1 FAIRE
  si tableau[i] === valeur ALORS
    retourner true
 fin si 
 fin pour 
 retourner false
FIN

## Exo 5 - compter
DEBUT
recevoir un tableau et une valeur
  compteur <- 0
  pour i allant de 0 à longueur du tableau - 1 FAIRE
  si tableau[i] === valeur ALORS
    compteur <- compteur + 1
 fin si 
 fin pour 
 retourner compteur
FIN