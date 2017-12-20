+++
title = "Selecteurs"
weight = 30
+++

Pour plus de détails, voir l'article suivant :
[Les 30 Sélecteurs CSS à Absolument Connaître](https://code.tutsplus.com/fr/tutorials/the-30-css-selectors-you-must-memorize--net-16048)

Pour s'entrainer sur les sélecteurs :
[CSS Dinner](http://flukeout.github.io/)

| Les&nbsp;sélecteurs  |  |
| ------  | -------------------------------- |
| .class  | Tous les éléments qui ont une .class |
| #id | Tous les éléments qui ont un #id (normalement un seul) |
| *  | Tous les éléments |
| div  | Toutes les balises div |
| div p | Toutes les balises p à l'intérieur d'une autre balise div, sans être forcément un enfant direct |
| div, p  | Toutes les balises div et toutes les balises p |
| div > p  | Toutes les balises p qui sont enfants directs d'une balise div |
| div + p | Toutes les balises p placées juste après une div (au même niveau) |
| div ~ p  | Selects all &lt;p&gt; elements that follow, and are siblings of, &lt;div&gt; elements |

<p data-height="265" data-theme-id="0" data-slug-hash="BJNveJ" data-default-tab="html,result" data-user="afpa-designerweb" data-embed-version="2" data-pen-title="div + p" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/afpa-designerweb/pen/BJNveJ/">div + p</a> by AFPA - Webdesigner (<a href="https://codepen.io/afpa-designerweb">@afpa-designerweb</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

| Les&nbsp;attributs  |  |
| ------  | -------------------------------- |
| [attribute]  | xxxxxxx |
| [attribute=value]  | xxxxxxx |
| [attribute~=value]  | xxxxxxx |
| [attribute\|=value]  | xxxxxxx |
| [attribute^=value]  | xxxxxxx |
| [attribute$=value]  | xxxxxxx |
| [attribute*=value]  | xxxxxxx |


| Pseudo-classes  |  |
| ------  | -------------------------------- |
| a:link | xxxxxxx |
| a:visited | xxxxxxx |
| a:hover | xxxxxxx |
| a:active | xxxxxxx |
| p::after | xxxxxxx |
| p::before | xxxxxxx |
| input:checked | xxxxxxx |
| input:disabled | xxxxxxx |
| p:empty | xxxxxxx |
| input:enabled | xxxxxxx |
| p:first-child | xxxxxxx |
| p::first-letter | xxxxxxx |
| p::first-line | xxxxxxx |
| p:first-of-type | xxxxxxx |
| input:focus | xxxxxxx |
| input:in-range | xxxxxxx |
| input:invalid | xxxxxxx |
| p:lang(language) | xxxxxxx |
| p:last-child | xxxxxxx |
| p:last-of-type | xxxxxxx |
| :not(p) | xxxxxxx |
| p:nth-child(2) | xxxxxxx |
| p:nth-last-child(2) | xxxxxxx |
| p:nth-last-of-type(2) | xxxxxxx |
| p:nth-of-type(2) | xxxxxxx |
| p:only-of-type | xxxxxxx |
| p:only-child | xxxxxxx |
| input:optional | xxxxxxx |
| input:out-of-range | xxxxxxx |
| input:read-only | xxxxxxx |
| input:read-write | xxxxxxx |
| input:required | xxxxxxx |
| :root | xxxxxxx |
| ::selection | xxxxxxx |
| #id:target | xxxxxxx |
| input:valid | xxxxxxx |