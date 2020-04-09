Formation Edition numérique

# TEI (6ème partie): Exercice

Simon Gabay
Metz, Vendredi 6 mars 2020

---
## Exercices

Encodez le document ```TEI_6_texte.md.txt```. Pour l'instant, considérez que le passage commençant par
"1691. — Où et comment ces Mémoires commencés…" est un paragraphe normal. Pour encoder le document,
vous pouvez utiliser les éléments suivants:

1. ```<persName>``` pour les noms de personnes
2. ```<placeName>``` pour les noms de lieux
3. ```<p>``` pour les paragraphes
4. ```<head>``` pour les chapeaux/titres
5. ```<date>``` pour les dates, avec un ```@when="YYYY-MM-DD"```, ```@from="YYYY-MM-DD"``` et/ou @to="YYYY-MM-DD".

Vous avez fini? Reprenez le paragraphe commençant par "1691. — Où et comment ces Mémoires commencés…" Plutôt que ```<p>```, vous pouvez utiliser les éléments ```<list>``` et ```<item>```. Ajoutez les métadonnées. Pour les notes de bas de page, vous pouvez les mettre dans une baliser ```<note>```, et la déplacer à l'endroit où se trouve l'appel de note (que l'on peut donc effacer).

