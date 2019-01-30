---
layout: post
title:  "Welcomyifiue to Jekyll!"
date:   2018-11-14 15:21:35 +0300
categories: jekyll update
---
Les titres

# Voici un titre de niveau important
## Là, c'est un titre un peu moins important
### Et ici, on a un titre encore moins important

On peut aller de un “#” jusqu’à 6 : “######”.
Le formatage du texte

*texte en italique*
**texte en gras**
`texte encadré`

Pour colorer un texte, on doit utiliser la syntaxe HTML.

 <span style="color: red">Texte en rouge</span>

Les tableaux

Voici un exemple de tableau :

| Titre 1       |     Titre 2     |        Titre 3 |
| :------------ | :-------------: | -------------: |
| Colonne       |     Colonne     |        Colonne |
| Alignée à     |   Alignée au    |      Alignée à |
| Gauche        |     Centre      |         Droite |

Résultat en fonction des “paramètres” de votre site :
Titre 1 	Titre 2 	Titre 3
Colonne 	Colonne 	Colonne
Alignée à 	Alignée au 	Alignée à
Gauche 	Centre 	Droite

Il peut être fastidieux de gérer un tableau à la main, en rajoutant soi-même les caractères pour qu’il soit équilibré. Il est préférable d’utiliser des logiciels comme Atom.
Les listes

Pour des listes non numérotées,

- Premier élément
- Deuxième élément
- etc.

Pour des listes numérotées,

1. Premier élément
2. Deuxième élément
3. etc.

Les images

On considère ici que les images sont rangées dans un dossier “assets”.

Pour ajouter une image :

![Texte à afficher si l'image ne s'affiche pas](./assets/nom_image.png)

Dans Jekyll, on remplace le point par : {{ site.url }} ce qui donne :

{{ site.url }}/assets/nom_image.png

{{ site.url }} est traduit par Jekyll pour comprendre qu’il faut “utiliser les images de ce site”, et non aller chercher ailleurs sur internet il le remplace donc par le l’adresse qui a été configurée.
Les liens url

Pour ajouter un lien vers une autre page (que ce soit vers un autre site internet ou vers une autre page du même site internet) on utilise des crochets. Par exemple pour mettre un lien vers la page http://google.com, on écrira :

[Cliquez ici pour accéder à Google.com](http://google.com)

On peut mettre une bulle d’information quand la souris survole le lien :

Si on veut s’affranchir de spécifier le titre du lien qui sera affiché à cliquer :

<http://google.com>

Pour aller plus loin :

https://docs.framasoft.org/fr/grav/markdown.html



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
