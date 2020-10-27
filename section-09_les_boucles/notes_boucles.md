### Généralités sur les boucles.

Les boucles permettent de répéter un bout de code. C'est également une bonne manière d'itérer au travers des éléments constituants une tableau, une liste, ou tout type d'énumération.

Pour cette raison, je dois faire très attention 🚨 à ce que **la boucle ait une fin**. Sinon je tombe dans le cas **d'une boucle infinie.**

### Concernant la boucle for

La boucle for s'écrit de la manière suivante 👇 :

```
for(var i = 0; i <= 100; i ++){
    // affiche le nombre de 0 à 100.
    Console.WriteLine(i);
}
```

**i** est le nom de la variable qui va servir d'index d'itération. Mais je peux éviter la nommer comme je veux.

**i <= 100** C'est la condition qui permet de dire que tant qu'elle est vraie, alors le code continue à s'exécuter.

**I++** Permet d'incrémenter la boucle de 1. J'aurai pu tout aussi bien l'incrémenter de 35 ou de - 12 si ça avait du sens. On appelle ça le pas.

Et à l intérieur des accolades, le code qui va se répéter.

Je vais utiliser cette boucle quand j'ai besoin d'avoir un contrôle sur l'index et l'avancé de l'itération. ⚠️**Mais également quand l'ordre des éléments a une importance !**⚠️

### Concernant la boucle foreach

La boucle foreach s'écrit de la manière suivante 👇 :

```
foreach(var i in item){
// le code s'exécute pour le nombre de fois que l'élément i se trouve dans l'objet item.
}
```

Il faut lire ce code de la manière suivante : "Pour chaque élément i compris dans l'objet item, alors je vais faire quelque chose."

Dans le cas d'un tableau (si item représente un tableau) alors pour chaque valeur du tableau je vais faire quelque chose.

Je peux utiliser cette boucle sur tout les types d'énumération comme les listes (que nous n'avons pas encore vu) mais aussi les tableaux sans pour autant avoir la main mise sur la manière dont l'itération va évoluer. De plus, cette boucle ⚠️**ne garantit pas l'ordre**⚠️ dans laquelle les éléments vont être itérés.

### Concernant les boucles while et do while

Elles s'écrivent de la manière suivante 👇👇 :

Ce bout de code affiche les nombres de 0 à 100.

While :

```
var i = 0;
while(i <= 100){
Console.WriteLine(i);
i++;
}
```

Do-While

```
var i = 0;
do {
Console.WriteLine(i);
i++;
}while(i <= 100)
```

La seule différence entre ces deux boucles est que dans la boucle `do while` 🚨 **va forcément exécuter au moins une fois le code entre accolades.** 🚨