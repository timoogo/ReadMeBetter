# Les bases à savoir pour écrire de la doc de qualité
___
## Metadonnées
Author: `Timothée Gaultier` <br/>
Date: <time>2021-10-18<time><br/>
Tags: #prise-de-note  <br/>
	   
## Avant de commencer cet article...
Type: #h2/beforeStarting
Cet article a pour but d'aider l'amérioration de ses prises de notes, qu'elles soient pour écrire de la documentation pour vos projets de développement, ou plus simplement pour écrire vos cours, ou encore ce qu'il se passe dans votre tête.  Mon objectif aujourd'hui est donc de vous convaincre d'arrêter d'utiliser autre chose que du markdown pour prendre des notes.

[[Table des matières]]


## Markdown c'est quoi ?
#h2/whatIsMarkdown

Le markdown [M⬇] est un language de balisage léger  A la différence du HTML, son but et de faire en sorte que la lecture puisse se faire en faisant abstraction de diverses balises qui alourdisent la lecture. 
Il est donc assez apprécié dans les domaines scientifiques, pour faire de la documentation de projet,  de thésards, mais aussi auprès de documentalistes. Il est courement appelé `README.md` et va donc expliquer le projet dans lequel ce document est.

Vous trouverez un exemple de notes ci-dessous :

<img src="https://github.com/timoogo/ReadMeBetter/blob/559a71cdc2d5582c71eeac161edf7d70516586cb/images/Markdown-preview.png"/>
*<center>A gauche, du markdown, à droite, ce que ça donne</center>*

## Un peu d'histoire 
Type: #h2/someHistory
Eh oui, ça peu être intérressant de savoir d'où le markdown vient...
Créé en 2004 par  [John Gruber](https://fr.wikipedia.org/wiki/John_Gruber "John Gruber") et [Aaron Swartz](https://fr.wikipedia.org/wiki/Aaron_Swartz "Aaron Swartz").
Depuis 2004,  le markdown a beaucoup évolué, et maintenant, certaines équipes génèrent des **rapports dynamiques incorporant du code R**, les sorties de ce code et des commentaires
> Pour cela, il existe des extensions de fichiers permettant d'ajouter des fonctionalités, mais ce n'est pas le coeur du sujet d'aujourd'hui. Un article très intérressant sera bientôt disponible.
## Comment je l'ai découvert
Type: #h2/HowIveDiscoveredIt
Je suis actuellement un étudiant du Pôle Léonard de Vinci, à la Défense, et j'ai choisis la voie du dévelopment web. J'ai donc appris ce que je vous ai expliqué dans la section [Markdown c'est quoi ?](#h2/whatIsMarkdown)

<a href='#h2/whatIsMarkdown' id='h2/whatIsMarkdown' class='anchor' aria-hidden='true'>C'est quoi</a>

## [Les avantages](#les-avantages)
C'est bien beau mais quels sont les avantages d'écrire en Markdown ?

### La synthaxe est facile
Le format simple du Markdown  permet de gagner un temps considérable lors de la réflexion sur le formatage. Il accélère le flux de travail de tout, du développement aux tâches de gestion.

### Une référence dans le web
C'est un langage de référence pour faire de la documentation. Une majorité des projets web possèdent un `README.md`. Il sert à nous introduire au projet dans lequel il est.

### C'est cross-platform
Ca veut dire que le contenu peut être modifié comme pour un `.txt` normal, mais aussi sur des sites et des outils dédiés. Ce n'est pas un fichier lisible spécifiquement par un OS mais bien lisible par tous. 

### C'est convertible 
Quand le contenu du `.md` est défiitivement écrit, il est possible de le convertir en `.pdf` mais aussi en `.html` 
### Ca permet de se concentrer sur l'essentiel
Avec un éditeur de markdown, il y a uniquement les outils nécéssaires pour l'écriture. Pas de boutton pour mettre du *style* [**gras**, *italique* ~~barré.~~]...
On peut faire des tableaux, des listes intéractives (cf #Listes)

En parralèlle, lorsque l'on décide de juste relire, on peut afficher uniquement le mode `Aperçu`. 
Dans certaines applications, on peut cacher les sections sur lesquels on ne se concentre pas.
### Ca permet de structurer ses idées rapidement
En prennant des notes dans le désordre, il est facile de se relire, de mettre de l'importance dans le contenu en très peu de temps. Je vais illuster ce propos avec mon cours d'anglais dans la prochaine section.
Toutes mes notes sont au même endroit, je n'ai plus à chercher dans quel dossier elle est .
## [Exemple du cours d'anglais](#exemple-du-cours-d-anglais)
Cette année, nous avons des cours d'anglais où la prise de notes est vraiment utile.
Chacune de mes notes de cours d'anglais se compose de la manière suivante :


<details open>
	<summary>Plan</summary>	
	<br/>
	- [Some definitions](#some-definitions)
		<br/>
	- [Exercice 1](#exercice-1)
		<br/>
	- [Exercice 2](#exercice-2)
	<br/>
	- ...
	<br/>
	- [Exercice x]

</details>

<img src="https://github.com/timoogo/ReadMeBetter/blob/524385b543713796c7ae7d32e2b5497435f7b485/images/screencapture-stackedit-io-app-2021-10-21-09_18_45%201.png">

Cela me permet de séparer les exercices sur une seule page, sans avoir a faire plusieurs fichiers.
Les mots en gras (comme sur le screenshot) sont des mots de vocabulaires que j'ai considéré comme important durant la séance.

Dans le cas où je me suis trompé durant un exercice, je vais barrer ma ~~réponse~~ et **mettre en gras la bonne réponse**. 

Cela me permet de formatter mon esprit quand je relis mes notes, et à terme, je retiens plus facilement. 
## [Les inconvéniants](#les-inconvniants)
### Le temps
Il faut vraiment du temps pour prendre le réflexe de tout écrire en markdown. Parfois, faire quelque chose en Markdown prendra plus de temps à comprendre que de le faire avec un éditeur de texte lamda mais, une fois appris, ça reste !




## Les principales balises
Je vous propose de voir rapidement les principales balises et comment les utiliser.

### La gestion des titres 
Commençons avec la gestion des titres qui se fait avec le hashtag `(#)`. 
Un seul hashtag `(#)` correspond à un titre de niveau  un. Donc il s'agit du titre de la page. Pour faire des sous-titres, il suffit de rajouter un `(#)`.
```markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```
>A noter qu'entre les 'block d'une autre couleur,le code est affiché en markdown
### La mise en forme :
Pour mettre en forme du texte, il va falloir l'entourer.
```markdown
Du texte en **Gras**
Du texte en *italique*
Du texte ~~barré~~(celui là n'a pas d'équivalence)
```
>Du texte en **Gras** <br/>
>Du texte en _italique_ <br/>
>Du texte ~~barré~~(celui là n'a pas d'équivalence) <br/>

Il est aussi possible d'écrire avec des underscores : 
```markdown
Du texte en __Gras__
Du texte en _italique_
```
#### Liens et Images
Pour les liens et les images, il faut **des parenthèses et des crochets**
```markdown
[Texte du lien](https://lien vers le site.com/ 	

![Ceci est un exemple d’image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsP5aIAb7aBXmeVhrV85iPYhOd8YSzZV3c4cf_88V4ABc06EIqLxKwZZ9X4tOFcOaZlFY&usqp=CAU)<br/>

```
>[Texte du lien](https://lien-vers-le-site.com/) <br/>
>![Ceci est un exemple d’image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsP5aIAb7aBXmeVhrV85iPYhOd8YSzZV3c4cf_88V4ABc06EIqLxKwZZ9X4tOFcOaZlFY&usqp=CAU)<br/>

	

#### Separations 
Pour faire des séparation, il suffit de choisir l'une de ces options :
 - `***` 
 -  `---` 
 -  `_________________`
Il est important de noter que le texte qui suit une séparation sera considéré comme un titre
```markdown
Du texte avant séparation
---
Après séparation

***
Une autre séparation
______
```
###### Ce qui nous donne
Du texte avant séparation
---
Après séparation

***
Une autre séparation
______

#### Tables 
Pour les table, la synthaxe est un peu compliquée :
```markdown
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

```
La première ligne donne le titre des colonmes
```markdown
| Tables        | Are           | Cool  |
```
La deuxième spécifie l'alignement des élements précédents :
```markdown
| Texte centré        | Autre façon de centrer  | Aligné a droite  Cool  |
| --------------------|:-------------:| -----:|
```

| Texte centré        | Autre façon de centrer  | Aligné a droite  Cool  |
| --------------------|:-------------:| -----:|

Tout ce qui suit sont les données du tableau
```markdown
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
```
Ce qui nous donne :


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


#### [Listes](#Liste) 
Il est possible de faire des listes 
```markdown
- [x] Item 1
- [ ] Item 2
```
Output :
> - [x] Item 1
> - [ ] Item 2

#### Les spécialisations github 
GitHub utilise une variante du Markdown de ce qu'ils appellent [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) .
##### Les mentions
il est possible de mentionner des personnes qui ont travaillé sur le projet avec un `@` suivi de l'username
dans mon cas : @timoogo

##### le support des emojis
GitHub arrive a comprendre les emoji! :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:
[La cheetsheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
##### Les sections refermables

```html
<details>
    <summary> Le titre de la section refermable
    </summary>
    Du contenu caché
</details>
```
> Il est possible d'ajouter un attribut open a details pour qu'elle soit ouverte de base :
> ```markdown
>  <details open>

<details>
    <summary> Le titre de la section refermable
    </summary>
    Du contenu caché
</details>
#### Recommendations
- Pour démarer, [BoostNotes](https://boostnote.io/) est une application simple pour prendre des notes et les visualiser.
	
- J'ai récement découvert [ObsidianMD](https://obsidian.md/), c'est un gestionnaire de notes markdown. On retrouve ainsi les notes avec les liens internes, un point fort d’Obsidian qui peut ainsi fonctionner comme un wiki personnel. L’app suggère automatiquement les autres notes pour créer un lien, ou vous pouvez ajouter un lien et créer une note à la suite. Pour visualiser tous ces liens, on retrouve aussi la barre latérale de droite qui les liste pour la note en cours, mais également le nuage de points, une fonction spécifique de l’app. Ajoutez à cela la barre latérale de gauche pour lister les notes et vous obtenez une interface touffue, qui nécessite quelques minutes d’adaptation.

## Conclusion
Comme nous venons de le voir, il est possible de faire beaucoup de choses avec le markdown. En plus, les outils se développent et permettent de s'organiser de plus en plus. 
