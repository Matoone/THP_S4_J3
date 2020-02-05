# Des app Rails avec BDD et Model
Crée une nouvelle application Rails. Tu vas maintenant générer un nouveau model Album dont les attributs seront les suivants :

title qui porte le titre de l'album et est de type string.
artist qui porte nom de l'artiste et est de type string.
Ensuite tu vas faire un second model Track avec les attributs :

title qui porte le titre de la chanson et est de type string.
album qui porte le titre de l'album et est de type string.
artist qui porte le nom de l'artiste et est de type string.
duration qui porte la durée de la chanson (en millisecondes) et est de type integer.
size qui porte la taille (en octets) de la chanson et est de type integer.
price qui porte le prix de la chanson et est de type float.
Pense bien à passer les migrations et n'hésite pas à tester le bon fonctionnement des 2 models en console.


Maintenant que ta BDD est prête, tu vas répondre aux questions ci-dessous :

a) Niveau facile
Quel est le nombre total d'objets Album contenus dans la base (sans regarder les id bien sûr) ?
Qui est l'auteur de la chanson "White Room" ?
Quelle chanson dure exactement 188133 milliseconds ?
Quel groupe a sorti l'album "Use Your Illusion II" ?
b) Niveau Moyen
Combien y a t'il d'albums dont le titre contient "Great" ? (indice)
Supprime tous les albums dont le nom contient "music".
Combien y a t'il d'albums écrits par AC/DC ?
Combien de chanson durent exactement 158589 millisecondes ?
c) Niveau Difficile
Pour ces questions, tu vas devoir effectuer des boucles dans la console Rails. C'est peu commun mais c'est faisable, tout comme dans IRB.

puts en console tous les titres de AC/DC.
puts en console tous les titres de l'album "Let There Be Rock".
Calcule le prix total de cet album ainsi que sa durée totale.
Calcule le coût de l'intégralité de la discographie de "Deep Purple".
Modifie (via une boucle) tous les titres de "Eric Clapton" afin qu'ils soient affichés avec "Britney Spears" en artist.
* ...

Réponses:

- 347 albums
- Eric Clapton
- Perfect de Alanis Morissette
- Guns N Roses

- 13
- 2 albums d'AC/DC
- 0

- prix total: 7.92
- duree totale: 2453259 ms
- cout total Deep Purple : 90.0899999999999 




