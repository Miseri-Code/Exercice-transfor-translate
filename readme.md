## Exercice sur transform transistion

# consigne de base : 
1. Exercice 1 :
Créez 1 bloc de 150px sur 100px de couleur violet.
Au passage de la souris, le bloc doit augmenter de taille, de 150px il doit s'agrandir jusqu'à
500px vers la droite.
2. Exercice 2 :
Créez un bloc contenant du texte sans dimension déterminée au départ.
Au passage de la souris :
 La div doit avoir une largeur de 300px, une hauteur de 100px
 Un fond bleu clair
 Avoir une rotation de 7 degrés à droite.
 La couleur doit s'afficher en 5 secondes.
3. Exercice 3 :
Reprenez le bloc de l'exercice 2 et au passage de la souris, la hauteur doit augmenter
progressivement de 150px (en 2s).
4. Exercice 4 :
Écrire une page HTML5 contenant :
 Un titre h1, un titre h2,
 Faire en sorte que le titre h2 effectue une rotation avec zoom lors du survol par le
curseur de la souris.

# Problèmes rencontré lors de la correction : 

J'ai reussi à clarifer pas mal de choses en revenant dessus et en faisant des test.
Mais il reste l'ex3 que je ne comprend pas. Et puis ça permet de faire un test github pour la suite.

ex 2 : Dans la correction, la transition de scale n'est pas prise en compte. 
J'ai compri ce qui n'allait pas. En gros ma syntaxe fontionnais et pas la "votre" (qui est la bonne) car sur la mienne, il considérait le second temps (10s) comme étant le temps de "all";
et sur la votre il faut utiliser "transform" et non "scale" pour que ça fonctionne. Ca me rendais très perplexe de voir que ma syntaxe (dont je n'arrive plus à retrouver la source) fonctionnais, et pas celle de w3school (la votre).


ex3 : Je ne comprend pas pourquoi "height" n'est pas pris en compte par la transition...

