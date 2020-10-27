### Concernant les différents types de variables

Nous avons vu quatre types de variables dans le cours.

- Les `int` qui sont des nombres entiers.
- Les `string` qui sont des chaines de caractères (des phrases, des mots).
- Les `boolean` (ou `bool`) qui ont la valeur `true` ou `false` (vrai ou faux).
- Les `float` qui sont des nombres décimaux.

Mais ils en existent plein d'autres comme vous pouvez le voir dans [la liste que l'on retrouve sur la documentation officielle de Microsoft à cette adresse.](https://docs.microsoft.com/fr-fr/dotnet/csharp/language-reference/builtin-types/built-in-types)

En consultant cette documentation, vous vous rendrez peut être compte que beaucoup de types ont l'air à première vue de refléter les mêmes informations. Par exemple, `decimal`, `double` et `float`, ont l'air de représenter des chiffres à virgule.

Ce n'est qu'en cliquant sur un des types mentionné ci dessus que l'on arrive sur un tableau récapitulatif qui nous éclaire d'avantage.

![https://udemy-image-web-upload.s3.amazonaws.com:443/redactor/raw/2020-10-01_20-34-53-d2c4270cd2d09d0632910a5b3266f0ea.JPG](https://udemy-image-web-upload.s3.amazonaws.com:443/redactor/raw/2020-10-01_20-34-53-d2c4270cd2d09d0632910a5b3266f0ea.JPG)

En réalité, les caractéristiques de ces trois types différents. N'étant pas codé sur le même nombre d'octet (taille) ils ne peuvent pas représenter les mêmes nombres comme en atteste la plage. par exemple un `float` va jusqu'à 1.5 * 10 puissance -45 alors qu'un `double` pourra aller à une puissance de -324. Donc, savoir si l'on doit plutôt utiliser l'un ou l'autre n'est surtout que question de **performances**.

Il est vraiment très rare d'être confronté à ces problématiques. Donc, dans le cadre de la formation ne vous questionnez pas trop sur le type à utiliser. Si vous êtes capable déjà de correctement utiliser les 4 types que nous avons vu, c'est l'essentiel.