+++
title = "Exercices"
weight = 4
+++

Using the official Emmet [documentation](https://docs.emmet.io/) and (especially) [cheatsheet](https://docs.emmet.io/cheat-sheet/), do the following tasks:

1. Make a list menu with 12 links (“#”), with link text that increments by one with each link. For example link01, link02, link03.
{{< hiddentext rep1 html >}}
ul>(li>a[href="#"]{link$$})*12
{{< /hiddentext >}}

2. Make a list menu with with 12 links, but “prewired” with spans and classes for Font Awesome.
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