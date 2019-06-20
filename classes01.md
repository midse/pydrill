## Exercice 1

Créer une classe représentant une Personne.

Une Personne est définie par les attributs suivants :
- prenom : chaîne de caractères
- nom : chaîne de caractères
- age : entier positif
- sexe : chaîne de caractères

Implémenter les méthodes suivantes :
- `vieillir()` : l'âge de la personne augmente de 1
- `presenter()` : la méthode doit afficher `"Je m'appelle {self.prenom} {self.nom}. J'ai {self.age} ans et je suis un {self.sexe}."`
- `saluer(p: Personne)` : la méthode prend en paramètre une Personne et doit afficher `"Bonjour {p.prenom} ! Comment vas-tu?"`

Instancier 3 personnes et tester les différentes méthodes.


## Exercice 2

Créer une nouvelle classe Item.
Un item est défini par les attributs suivants :
- nom : chaîne de caractères
- prix : nombre flottant


Ajouter de nouveaux attributs à la classe Personne :
- argent : nombre flottant
- items : liste d'items

Implémenter les nouvelles méthodes sur la classe Personne :

- `travailler()` : Travailler permet de gagner 50 argent en plus
- `acheter(i: Item)` : La méthode acheter permet de s'approprier des Items. Ils sont alors ajoutés à la liste "items". 
                      Si la personne n'a pas assez d'argent, elle ne peut pas acheter l'item.
                      Acheter un item enlève le prix de l'item de l'attribut argent.
- `vendre(i: Item, p: Personne)` : La méthode permet de vendre un Item à une autre personne. 
                                  On ne peut vendre à une personne un item que si elle a suffisamment d'argent pour l'acheter.

Modifier la méthode presenter() définie dans l'exercice précédent.
Elle doit maintenant afficher en plus la liste des items qu'une Personne possède.

Instancier plusieurs personnes et plusieurs items. Tester les différentes méthodes.
