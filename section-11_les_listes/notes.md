### Généralités sur les listes

Les listes sont des collections d'éléments **du même type**. **La taille n'est pas définie au moment de l'instanciation à la différence des tableaux.**

Il y a **deux manières** de déclarer une liste.

Syntaxe A :

```
var myList= new List<int>(); //liste de nombres vide.
```

Syntaxe B

```
var myList = new List<int>() { //si je souhaite préremplir ma liste.
      1,2,3
    };
```

et ensuite je pourrai **ajouter des éléments à ma liste** en faisant :

`myList.Add(1);`

pour ajouter le chiffre 1 par exemple.

Il est tout à fait possible d'utiliser un index pour accéder à une valeur de ma liste.

Si je reprends l'exemple de la syntaxe B, je peux faire

`myList[2];` 

et j'obtiendrai la valeur 3 car les index commencent toujours à 0 et à la 3ième entrée (donc index 2) j'ai la valeur 3.