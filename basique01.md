## Exercice 1

Écrire un programme qui affiche la figure suivante (la figure est composée du caractère étoile '*').
Faire en sorte d'afficher les 30 premières lignes de la figure.

```
*
**
***
****
*****
******
*******
********
*********
**********
etc...
```

## Exercice 2

Écrire un programme qui affiche la figure suivante (la figure est composée du caractère étoile '*').
Faire en sorte d'afficher les 30 premières lignes de la figure.

```
*
**
*
**
*
**
*
**
*
**
*
**
*
```

## Exercice 3

Écrire un programme qui affiche la liste des carrés des 100 premiers entiers (chercher l'usage de la fonction range() pour générer la liste des entiers).
Le programme doit afficher les résultats sous la forme qui suit :

```
1*1 = 1
2*2 = 4
3*3 = 9
4*4 = 16
5*5 = 25
etc...
```

## Exercice 4

Sans utiliser la fonction max(), trouver l'entier le plus grand de la liste suivante (copier/coller le code ci-dessous pour obtenir la liste d'entiers à utiliser).

```python
import random
ma_liste = [ random.randint(0, 10000)  for _ in range(1000) ]
```

Sans utiliser la fonction min(), trouver également l'entier le plus petit de la liste.


## Exercice 5

Petit exercice pour essayer de faire travailler les listes, les boucles et un peu d'algorithmique.

L'objectif est de calculer une sorte de somme de contrôle simplifiée (c'est utilisé pour vérifier l'intégrité de fichiers par exemple).
Pour calculer la somme de contrôle, on doit calculer la somme de tous les chiffres qui sont égaux au prochain chiffre de la liste.
La liste est "circulaire", le dernier chiffre est considéré comme étant également le premier chiffre de la liste.

Quelques exemples sur lesquels tu peux t'entraîner à mettre au point ta fonction :

- 1122 produit une somme de 3 ( 1 + 2 ) car le premier chiffre est égal au deuxième chiffre et le troisième chiffre est égal au quatrième chiffre.
- 1111 produit une somme de 4 car tous les chiffres sont égaux au chiffre qui suit
- 1234 produit une somme de 0 car aucun chiffre ne correspond au chiffre qui suit dans la liste


Quel est le résultat pour la valeur suivante :

```
181445682966897848665963472661939865313976877194312684993521259486517527961396717561854825453963181134379574918373213732184697746668399631642622373684425326112585283946462323363991753895647177797691214784149215198715986947573668987188746878678399624533792551651335979847131975965677957755571358934665327487287312467771187981424785514785421781781976477326712674311994735947987383516699897916595433228294198759715959469578766739518475118771755787196238772345762941477359483456641194685333528329581113788599843621326313592354167846466415943566183192946217689936174884493199368681514958669615226362538622898367728662941275658917124167353496334664239539753835439929664552886538885727235662548783529353611441231681613535447417941911479391558481443933134283852879511395429489152435996669232681215627723723565872291296878528334773391626672491878762288953597499218397146685679387438634857358552943964839321464529237533868734473777756775687759355878519113426969197211824325893376812556798483325994128743242544899625215765851923959798197562831313891371735973761384464685316273343541852758525318144681364492173465174512856618292785483181956548813344752352933634979165667651165776587656468598791994573513652324764687515345959621493346623821965554755615219855842969932269414839446887613738174567989512857785566352285988991946436148652839391593178736624957214917527759574235133666461988355855613377789115472297915429318142824465141688559333787512328799783539285826471818279818457674417354335454395644435889386297695625378256613558911695145397779576526397241795181294322797687168326696497256684943829666672341162656479563522892141714998477865114944671225898297338685958644728534192317628618817551492975251364233974374724968483637518876583946828819994321129556511537619253381981544394112184655586964655164192552352534626295996968762388827294873362719636616182786976922445125551927969267591395292198155775434997827738862786341543524544822321112131815475829945625787561369956264826651461575948462782869972654343749617939132353399334744265286151177931594514857563664329299713436914721119746932159456287267887878779218815883191236858656959258484139254446341
```

## Exercice 6

Calculer de manière itérative (en utilisant une boucle) les 10 premiers termes de la suite de Fibonacci.

```
0 + 1 = 1
1 + 1 = 2
1 + 2 = 3
2 + 3 = 5
3 + 5 = 8
etc...
```

## Exercice 7 (optionnel)

Même exercice que l'exercice 6 mais en utilisant la récursivité.
https://openclassrooms.com/fr/courses/438849-la-recursivite

## Exercice 8

Copier les données ci-dessous dans un fichier 'data.txt' :

```
Prenom: Paul
Nom: Dupont
Age: 27
Ville: Toulouse

Prenom: Pierre
Nom: Martin
Age: 58
Ville: Strasbourg

Prenom: Jacques
Nom: Moretti
Age: 65
Ville: Paris

Prenom: Marie
Nom: Kondo
Age: 35
Ville: Tokyo
```

Écrire un programme qui lit le contenu du fichier et stocke les données dans une liste de dictionnaires (chaque personne doit être stockée dans un dictionnaire dédié).
A partir du contenu de la liste, le programme doit donner le détail pour chaque personne de la manière suivante :

```
Personne n°1 : Paul Dupont a 27 ans et habite à Toulouse
Personne n°2 : Pierre Martin a 58 ans et habite à Strasbourg
Personne n°3 : Jacques Moretti a 65 ans et habite à Paris
Personne n°4 : Marie Kondo a 35 ans et habite à Tokyo
```
