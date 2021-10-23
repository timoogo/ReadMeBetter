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

<img src"https://ibb.co/MsFGpSj" alt="screenshot d'une note d'anglais"/>
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

<img src="https://ibb.co/gtnT5TX">

Cela me permet de séparer les exercices sur une seule page, sans avoir a faire plusieurs fichiers.
Les mots en gras (comme sur le screenshot) sont des mots de vocabulaires que j'ai considéré comme important durant la séance.

Dans le cas où je me suis trompé durant un exercice, je vais barrer ma ~~réponse~~ et **mettre en gras la bonne réponse**. 

Cela me permet de formatter mon esprit quand je relis mes notes, et à terme, je retiens plus facilement. 
## [Les inconvéniants](#les-inconvniants)
### Le temps
Il faut vraiment du temps po

### [Listes](#Liste) 
Il est possible de faire des listes intéractives 
- [x] Item 1
- [ ] Item 2
