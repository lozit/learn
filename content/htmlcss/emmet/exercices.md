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

2. Faites une liste de menu de 12 liens. Chaque lien doit être contenu dans un span contenant les classes necessaires pour [Font Awesome](http://fontawesome.io) :  class="fa fa-"
{{< hiddentext rep2 html >}}
ul>(li>a[href=”#”]>span.fa.fa-+{link$$})*12
{{< /hiddentext >}}

3. Make a list menu with with 12 links, but “prewired” with spans and classes for Font Awesome and with the visuallyhidden class.
{{< hiddentext rep3 html >}}
ul>(li>a[href=”#”]>span.fa.fa-+span.visuallyhidden>{link$$})*12
{{< /hiddentext >}}

4. Make three rows of DIVs with classes of clearfix and row. Each row will have 4 articles inside. Each article will have an h1 with 3 words of lorem ipsum, an h2 with 2 words of lorem ipsum, and a p with 17 words of lorem ipsum.
{{< hiddentext rep4 html >}}
(div.clearfix.row.row$>
(article>h1>lorem3^h2>lorem2^p>lorem17)*3)*4
{{< /hiddentext >}}

5. Make a table with :
   - a caption that says “Bus Schedule”
   - one header row with three cells
   - four rows with three cells
{{< hiddentext rep5 html >}}
table>caption{Bus Schedule}+(tr>td*3)*4(header>nav.menu-main>ul>(li>a[href=”#”]{link$$})*12)+((div.clearfix.row.row$>(article>h1>lorem3^h2>lorem2^p>lorem17)*3)*4)+(table>caption{Bus Schedule}+(tr>td*3)*4)
{{< /hiddentext >}}

{{< emmet html >}}
&lt;!-- VOUS POUVEZ TESTER ICI VOTRE CODE EMMET--&gt;
{{< /emmet >}}