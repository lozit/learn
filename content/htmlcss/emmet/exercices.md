+++
title = "Exercices"
weight = 4
+++

[Article original](http://wrmf.ca/posts/emmet-lab-exercise/) par [Kevin McMillan](http://wrmf.ca/)

En utilisant la [documentation officielle d'Emmet](https://docs.emmet.io/) et en particulier [l'Antisèche](https://docs.emmet.io/cheat-sheet/), réalisez les tâches suivantes :

1. Faites une liste de menu de 12 liens ("#"). Le texte du lien doit s'incrémenter pour chaque lien. Par exemple : lien01, lien02, lien03 etc.
{{< hiddentext rep1 html >}}
ul>(li>a[href="#"]{lien$$})*12
{{< /hiddentext >}}

2. Enrichissez la liste précédente : chaque lien doit aussi contenir une balise span avec les classes necessaires pour [Font Awesome](http://fontawesome.io) :  class="fa fa-"
{{< hiddentext rep2 html >}}
ul>(li>a[href=”#”]>span.fa.fa-+{link$$})*12
{{< /hiddentext >}}

3. Enrichissez la liste précédente : chaque lien doit être contenu dans une nouvelle class "visuallyhidden".
{{< hiddentext rep3 html >}}
ul>(li>a[href=”#”]>span.fa.fa-+span.visuallyhidden>{link$$})*12
{{< /hiddentext >}}

4. Faites trois div à la suite avec comme class "clearfix" et "row". Chaque div doit contenir 4 articles. Chaque article doit avoir un h1 avec 3 mots de lorem ipsum, un h2 avec deux mots de lorem ipsum et un p avec 17 motes de lorem ipsum.
{{< hiddentext rep4 html >}}
(div.clearfix.row.row$>(article>h1>lorem3^h2>lorem2^p>lorem17)*4)*3
{{< /hiddentext >}}

5. Faites une table avec :
    - une légende qui dit "Horaire de bus"
    - un en-tête avec trois colonnes
    - quatre lignes avec trois colonnes
{{< hiddentext rep5 html >}}
table>caption{Bus Schedule}+(tr>td*3)*4
{{< /hiddentext >}}

{{< emmet html >}}
&lt;!-- VOUS POUVEZ TESTER ICI VOTRE CODE EMMET--&gt;
{{< /emmet >}}