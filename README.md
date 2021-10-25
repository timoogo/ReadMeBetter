# Les bases à savoir pour écrire de la doc de qualité
___
##### Metadonnées
**Author: `Timothée Gaultier`**<br/>
Date: <time>2021-10-18<time><br/>
Tags: #prise-de-note  <br/>

	   
## [Avant de commencer cet article...](#before-starting)
Cet article a pour but d'aider l'amérioration de ses prises de notes, qu'elles soient pour écrire de la documentation pour vos projets de développement, ou plus simplement pour écrire vos cours, ou encore ce qu'il se passe dans votre tête.  Mon objectif aujourd'hui est donc de vous convaincre d'arrêter d'utiliser word, ou autre service/logiciel pour prendre des notes

- [Les bases à savoir pour écrire de la doc de qualité](#les-bases)
        * [Metadonnées](#metadonnees)
  * [Avant de commencer cet article...](#avant-de-commencer-cet-article)
  * [Markdown c'est quoi ?](#markdown-c-est-quoi)
  * [Un peu d'histoire](#un-peu-d-histoire)
  * [[Comment je l'ai découvert](#what-is-markdown)](#comment-je-l-ai-d-couvert)
  * [[Les avantages](#les-avantages)](#les-avantages-les-avantages-)
    + [[La synthaxe est facile](#easy-synthax)](#easy-synthax-)
    + [[Une référence dans le web](#web-basic)](#web-basic-)
    + [[C'est cross-platform](#cross-platform)](#cross-platform-)
    + [[C'est convertible ](#convertable)](#convertable)
    + [[Ca permet de se concentrer sur l'essentiel](#essentials)](#essentials)
    + [[Ca permet de structurer ses idées rapidement](#struc-idea)](#struc-idea)
  * [[Exemple du cours d'anglais](#exemple-du-cours-d-anglais)](#english-exemple)
  * [[Les inconvéniants](#les-inconvniants)](#les-inconveniants)
    + [[Le temps](#time)](#time)
    + [Cela peut refroidir les néophites](#scary)
  * [Les principales balises](#les-principales-balises)
    + [La gestion des titres](#la-gestion-des-titres)
    + [La mise en forme :](#la-mise-en-forme--)
    + [Les spécialisations github](#les-sp-cialisations-github)
      - [Les mentions](#les-mentions)
      - [Le support des emojis](#le-support-des-emojis)
  * [[Recommendations](#recommendations)](#-recommendations---recommendations-)
    + [Quelques liens utiles](#quelques-liens-utiles)
  * [Conclusion](#conclusion)



## Markdown c'est quoi ?
Le markdown [M⬇] est un language de balisage léger.  A la différence du HTML, son but et de faire en sorte que la lecture puisse se faire en faisant abstraction de diverses balises qui alourdisent la lecture. 
Il est donc assez apprécié dans les domaines scientifiques, pour faire de la documentation de projet,  de thésards, mais aussi auprès de documentalistes. Il est courement appelé `README.md` et va donc expliquer le projet dans lequel ce document est.

Vous trouverez un exemple de notes ci-dessous :

<img src="https://github.com/timoogo/ReadMeBetter/blob/559a71cdc2d5582c71eeac161edf7d70516586cb/images/Markdown-preview.png"/>
<center>A gauche, du markdown, à droite, ce que ça donne</center>
	

## Un peu d'histoire 
	
Eh oui, ça peu être intérressant de savoir d'où le markdown vient...
Créé en 2004 par  [John Gruber](https://fr.wikipedia.org/wiki/John_Gruber "John Gruber") et [Aaron Swartz](https://fr.wikipedia.org/wiki/Aaron_Swartz "Aaron Swartz").
Depuis 2004,  le markdown a beaucoup évolué, et maintenant, certaines équipes génèrent des **rapports dynamiques incorporant du code R**, les sorties de ce code et des commentaires
> Pour cela, il existe des extensions de fichiers permettant d'ajouter des fonctionalités, mais ce n'est pas le coeur du sujet d'aujourd'hui. <br/>
*Un article très intérressant sera bientôt disponible.*
	
## [Comment je l'ai découvert](#what-is-markdown)
%%Type: #h2/HowIveDiscoveredIt%%
Je suis actuellement un étudiant du Pôle Léonard de Vinci, à la Défense, et j'ai choisis la voie du dévelopment web. J'ai donc appris ce que je vous ai expliqué dans la section [Markdown c'est quoi ?]

<a href='#h2/whatIsMarkdown' id='h2/whatIsMarkdown' class='anchor' aria-hidden='true'>C'est quoi ?</a>

## [Les avantages](#les-avantages)
C'est bien beau mais quels sont les avantages d'écrire en Markdown ?

### [La synthaxe est facile](#easy-synthax)
Le format simple du Markdown  permet de gagner un temps considérable lors de la réflexion sur le formatage. Il accélère le flux de travail de tout, du développement aux tâches de gestion.

### [Une référence dans le web](#web-basic)
C'est un langage de référence pour faire de la documentation. Une majorité des projets web possèdent un `README.md`. Il sert à nous introduire au projet dans lequel il est.

### [C'est cross-platform](#cross-platform)
Ca veut dire que le contenu peut être modifié comme pour un `.txt` normal, mais aussi sur des sites et des outils dédiés. Ce n'est pas un fichier lisible spécifiquement par un OS mais bien lisible par tous. 

### [C'est convertible ](#convertable)
Quand le contenu du `.md` est défiitivement écrit, il est possible de le convertir en `.pdf` mais aussi en `.html` . Très pratique pour partager des comptes-rendus, ou des notes.
	
### [Ca permet de se concentrer sur l'essentiel](#essentials)
Avec un éditeur de markdown, il y a uniquement les outils nécéssaires pour l'écriture. Pas de boutton pour mettre du *style* [**gras**, *italique* ~~barré.~~]...
On peut faire des tableaux, des listes intéractives (cf #Listes)

En parralèlle, lorsque l'on décide de juste relire, on peut afficher uniquement le mode `Aperçu`. 
Dans certaines applications, on peut cacher les sections sur lesquels on ne se concentre pas. <a href="#recommendations">(cf #Recommendations) </a>
	
### [Ca permet de structurer ses idées rapidement](#struc-idea)
En prennant des notes dans le désordre, il est facile de se relire, de mettre de l'importance dans le contenu en très peu de temps. Je vais illuster ce propos avec mon cours d'anglais dans la prochaine section.
Toutes mes notes sont au même endroit, je n'ai plus à chercher dans quel dossier elle est .
## [Exemple du cours d'anglais](#exemple-du-cours-d-anglais)
Cette année, nous avons des cours d'anglais où la prise de notes est vraiment utile.
Chacune de mes notes de cours d'anglais se compose de la manière suivante :
	<br/>
<details>
	<summary style="font-size:32px">Table of content</summary>	
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
	
	<hr/>
	
Cela me permet de séparer les exercices sur une seule page, sans avoir a faire plusieurs fichiers.
Les mots en gras (comme sur le screenshot) sont des mots de vocabulaires que j'ai considéré comme important durant la séance.

Dans le cas où je me suis trompé durant un exercice, je vais barrer ma ~~réponse~~ et **mettre en gras la bonne réponse**. 

Cela me permet de formatter mon esprit quand je relis mes notes, et à terme, je retiens plus facilement. 
## [Les inconvéniants](#les-inconvniants)
	
### [Le temps](#time)
Il faut vraiment du temps pour prendre le réflexe de tout écrire en markdown. Parfois, faire quelque chose en Markdown prendra plus de temps à comprendre que de le faire avec un éditeur de texte lamda mais, une fois appris, ça reste !

### [Cela peut refroidir les néophites](#scary)
Il est vrai que cette syntaxe ne va pas forcément plaire aux néophites. En effet, il n'y a pas d'interface visuelle pour écrire du markdown facilement dans la plupart des applications. Cedendant, a la fin de cet article, je vous donne quelques liens que j'utilise fréquement lors de mes écritures en markdown <a href="#recommendations">(cf #Recommendations) </a> 

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
Pour mettre en forme du texte, il va falloir l'entourer .
En voici les principales :
	
	<details>
		<summary>Le texte en <b>gras</b></summary>
		<p>En mettant le texte entre <code>\**double étoiles\**</code>, le texte sera en <b>gras</b> </p>
		<!-- language: "markdown" -->
		<blockquote><p>En mettant le texte entre <b>**double étoiles**</b>, le texte sera en <b>gras</b> </p></blockquote>
	</details>	

<details>
	<summary>Le texte en <i>italique</i></summary>
	<p>En mettant le texte entre  <code>*étoiles*</code>, le texte sera en <i>italique</i> </p>
	<!-- language: "markdown" -->
	<blockquote><p>En mettant le texte entre <i>*double étoiles</i>, le texte sera en <i>italique</i> </p></blockquote>
</details>	

<details >
	<summary>Le texte <strike>barré</strike></summary>
	<p>En mettant le texte entre  <code>~~tilde~~</code>, le texte sera <strike>barré</strike> </p>
	<!-- language: "markdown" -->
	<blockquote>
		<p>En mettant le texte entre  <code>~~tilde~~</code>, le texte sera <strike>barré</strike> </p>
	</blockquote>
</details>	

### Les spécialisations github 
GitHub utilise une variante du Markdown de ce qu'ils appellent [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown). 
#### Les mentions
il est possible de mentionner des personnes qui ont travaillé sur le projet avec un `@` suivi de l'username
dans mon cas : @timoogo

#### Le support des emojis
GitHub arrive a comprendre les emoji! :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:
[La cheetsheet des emoji Github](https://www.webfx.com/tools/emoji-cheat-sheet/)



## [Recommendations](#recommendations)
	
- Pour démarer, [BoostNotes](https://boostnote.io/) est une application simple pour prendre des notes et les visualiser. Très simple, son interface aide à se familiariser.
	
- J'ai récement découvert [ObsidianMD](https://obsidian.md/), c'est un gestionnaire de notes markdown. On retrouve ainsi les notes avec les liens internes, un point fort d’Obsidian qui peut ainsi fonctionner comme un wiki personnel. L’app suggère automatiquement les autres notes pour créer un lien, ou je peux ajouter un lien et créer une note à la suite. Pour visualiser tous ces liens, je vais dans la barre latérale de droite qui les liste pour la note en cours, mais également le nuage de points, une fonction spécifique de l’app. La barre latérale de gauche pour lister les notes et vous obtenez une interface touffue, qui nécessite quelques minutes d’adaptation. Cette application a pour avantage qu'elle est beaucoup plus complète que BoostNotes, car elle permet de lier des notes, d'en faire des dossiers. Il est possible d'y stocker des images.
### Quelques liens utiles
- [TOC](https://ecotrust-canada.github.io/markdown-toc/), un générateur de Table des matières, très efficace. Il suffit de gérer ses titres, et le site fait le reste. :tada:
- [Table Generator](https://www.tablesgenerator.com/markdown_tables), une interface visuelle qui permet de générer des tables.
- [Markdown Here ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) Un repository Github listant toute les balises importantes, avec explication.
	
- [Delinger](https://dillinger.io/), un site pour s'essayer au markdown, et le visualiser en direct.	

## Conclusion
Comme nous venons de le voir, il est possible de faire beaucoup de choses avec le markdown. En plus, les outils se développent et permettent de s'organiser de plus en plus. 
