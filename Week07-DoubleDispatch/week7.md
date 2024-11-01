## DASSI-Helyana

# WEEK 7 :

## HOMEWORK : 
 

# VISITOR 

Le pattern Visitor permet de séparer des opérations d’un ensemble d'objets sans modifier leur classe, il introduit un objet visiteur qui va effectuer des des opérations spécifiques sur ces objets.
Ajouter de nouvelles opérations  = ajouter de nouveaux visiteurs toujours sans toucher aux classes

### VISITOR et DOUBLE DISPATCH

Le Visiteur utilise le double dispatch, à chaque objet du domaine de spécifier la manière dont il doit être visité par un Visiteur.
Le double dispatch est essentiel pour gérer les visites.

### Quand l'utiliser

Le pattern Visitor est utile quand on doit appliquer plusieurs opérations différentes sur des structures d'objets

