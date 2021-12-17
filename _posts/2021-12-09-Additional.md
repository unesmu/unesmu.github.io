---
layout: post
title: Quotebank's explanation of the rise femonationalism
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
thumbnail: /assets/img/all_quotes_polarization.png 
tags: []
comments: true
---

Le topic analysis réalisé dans la partie [What do people talk about?](https://unesmu.github.io/2021-12-12-RQ3/) issue d'un travail de clustering visant à synthétiser l'ensemble des citations traitant de proche ou de loin au droit des femmes.

On s'intéresse alors à extraire parmi l'ensemble de ces citations celles qui se rapportent au femonationalisme et donc qui utilisent spéciallement les mots clés de muslim, women, hijab et d'opression tels qu'apparaissent dans la suivante citation.

Le femonationalisme est un phénomène qui a pris de l'ampleur et qui a poussé Sara R. Farris à publier un livre en 2017 sur le féminisme et le droit des femmes.
![femo_livre](https://raw.githubusercontent.com/unesmu/unesmu.github.io/master/assets/img/title_book.JPG)
![femo_livre](https://raw.githubusercontent.com/unesmu/unesmu.github.io/master/assets/img/in_the_name_book.jpg)

On observe en effet, un pic du nombre de citations en 2017 se référant au concept de femonationalism, notamment de par la notoriété de son livre.
![femo_timeline](https://raw.githubusercontent.com/unesmu/unesmu.github.io/master/assets/img/femo_timeline.JPG)

De nombreuse citations durant cette période sont à connotation négative. Elles apparaissent au milieu de l'année 2017, en bleu foncé sur l'histogramme suivant:
![femo_histplot](https://raw.githubusercontent.com/unesmu/unesmu.github.io/master/assets/img/femo_histplot.JPG)

Nous avons réussi a isoler, grâce à Vader les mots clés négatis les plus fréquents de ces citations. Les citations à connotation négatives traitent de la terreur des femmes et de leur opression. Sur l'ensemble des citations liées au femonationalisme au cours de la mi-année 2017, le mot **_persecution_** a été mentionné 24 fois, **_murder_** 21 fois, **_innocent_** 21 fois et **_slaughter_** 20 fois.

Nous pourrions rapprocher cette observation à l'affaire Trump ayant eu lieu en Décembre 2017.

Toutefois, l'explication la plus censée reste la montée en puissance du femonationalisme car les termes utilisés se référant à l'opression et à la terreur se mèlent au vocabulaire islamophobe fréquemment employés aussi bien aux U.S. qu'ailleurs par les parties politiques extremistes et racistes.
Ces parties cherchent généralement à susciter la peur en employant un tel vocabulaire que Vader a pu jugé négatif (muslim (541 fois), muslims (48 fois)).
