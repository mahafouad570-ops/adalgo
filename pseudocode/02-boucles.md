## Exo 1 - compterJusqua
DEBUT
recevoir un nombre (n)
  pour i allant de 1 à n faire 
    afficher i
  fin pour
FIN

## Exo 2 - afficherPairs
DEBUT
recevoir un nombre (n)
  pour i de 1 à n faire 
   si  le reste de i  divisé par 2 est égal à 0(i % 2 === 0) ALORS
      afficher i
    FIN SI 
  FIN POUR
FIN

## Exo 3 - somme
DEBUT
recevoir un nombre (n)
  total <- 0
  pour i allant de 1 à n FAIRE
    total <- total + i
 fin pour 
 retourner total
FIN

## Exo 4 - produit
DEBUT
recevoir un nombre (n)
  resultat <- 1
  pour i allant de 1 à n FAIRE
    resultat <- resultat * i
 fin pour 
 retourner resultat
FIN

## Exo 5 - compterPairs
DEBUT
recevoir un nombre (n)
  compteur <- 0
  pour i allant de 1 à n FAIRE
    si i % 2 === 0 ALORS 
      compteur <- compteur + 1
    fin si
 fin pour 
 retourner compteur
FIN

## Exo 6 - table
DEBUT
recevoir un nombre (n)
  tableau <- []
  pour i allant de 1 à n FAIRE
    ajouter n * i dans tableau
 fin pour 
 retourner tableau
FIN