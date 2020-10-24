### Concernant l'instanciation

On peut instancier un tableau de plusieurs manières :

1. Soit en utilisant l'instruction `var myArray = new type;` où type représente le type de mon tableau (`string`, `int`, `bool` etc). et x la taille de mon tableau. Donc si j'écris `var myArray = new int[5];` j'aurai un tableau de valeur par défaut à savoir 0. [0,0,0,0,0].
2. Soit en utilisant l'instruction `var myArray = new type {*mesélements*};` où type représente également le type de mon tableau, x est optionnel et *meséléments* représentent les éléments que je souhaite directement ajouter au tableau séparés par une virgule. Donc, si j'écris `var myArray = new int[] {1,2,3,4};` j'aurai un tableau avec les valeurs suivantes : [1,2,3,4].

**La taille d'un tableau est fixe,** je ne peux pas le modifier plus tard !

### Concernant la récupération et la modification des données.

Si je souhaite récupérer ou modifier une valeur je vais utiliser l'index de l'élément que je souhaite modifier. **L'index d'un tableau commence toujours à zéro.**

Si je prends le tableau suivant :

`var myArray = new int[3] {7,5,12};`

je peux **récupérer** la valeur 5 située à l'index 1 en faisant `myArray[1];`

je peux **modifier** la valeur 12 par 8 (par exemple) située à l'index 2 en faisant `myArray[2] = 8;`

### Concernant la commande Array.IndexOf.

Je peux chercher un élément dans mon tableau en récupérant son index grâce à la commande :

`Array.IndexOf(x, y);`

où :

- X est le tableau dans lequel je souhaite effectuer une recherche.
- Y est la valeur à rechercher.

L'instruction me retournera :

- **1 si l'élément Y ne se situe pas dans mon tableau X.**
- L'index (donc 0 et +) si mon élément Y se trouve dans mon tableau X.

### Concernant les erreurs.

Une erreur **caractéristique** quand on essaie de modifier ou de récupérer une valeur à un index supérieur à la taille du tableau est l'erreur "Index out of range". **Si je vois cette erreur, je sais que j'essaie d'accéder à un index au delà des limites du tableau.**