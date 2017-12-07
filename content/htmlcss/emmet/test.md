+++
title = "test"
weight = 29
+++

The following steps are here to help you initialize your new website. If you don't know Hugo at all, we strongly suggest you to train by following this [great documentation for beginners](https://gohugo.io/overview/quickstart/).

## Create your project

Hugo provides a `new` command to create a new website.

```
hugo new site <new_project>
```

Emmet permet d'écrire du code html et css de façon simple et rapide.

Vous pouvez commencer par aller voir le site officiel : [emmet.io](https://emmet.io/).

## Une vidéo vaut mieux qu'un long discours

Hugo provides a `new` command to create a new website.

```
hugo new site <new_project>
```

{{< youtube ZEf9cRoTmzQ >}}

Make a list menu with 12 links (“#”), with link text that increments by one with each link. For example link01, link02, link03.


{{% hiddentext %}}
```
ul>(li>a[href="#"]{link$$})*12
```
{{% /hiddentext %}}