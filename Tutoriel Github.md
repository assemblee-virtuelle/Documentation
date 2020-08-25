# Mode d'emploi Github

Fraichement contributeur, contributrice ? 
Tout d'abord nous vous souhaitons la bienvenue :) 
Afin de suivre au plus près les avancées des projets de l'Assemblée Virtuelle et de participer à la vie de notre communauté, quoi de mieux que de vous familiariser avec les outils prévus à cet effet ! 
Voici un tutoriel qui vous permettra de rentrer dans l'aventure sans trop de difficultés.

À l'origine, Github est une plateforme basée sur un cloud, permettant le développement de projets logiciels, elle facilite la collaboration de développeurs sur un même code, qui sera stocké et évoluera selon les modifications que chacun lui apportera. 
Github devient alors un outil pertinent de gestion de projets open source comme les nôtres, car il permet à tout adhérent de s'y impliquer et de suivre les évolutions apportées en temps et en heure. 
**Pour aller plus loin**: En fait, github est une interface pour [GIT](https://git-scm.com/docs/gittutorial) qui s'éxécute uniquement en ligne de commande (pour les développeurs donc !).

## Comment s'y inscrire ?

C'est très simple ! 
1. Se rendre sur la plateforme [Github](https://github.com/) et cliquer sur "sign up for Github".
2. Entrez vos informations personnelles (adresse mail, mot de passe, nom d'utilisateur).
3. Se faire inviter par le contributeur actif avec lequel vous êtes en contact, en lui fournissant votre adresse mail ou votre nom d'utilisateur. 
4. Le tour est joué ! Vous n'avez plus qu'à vous connecter.

## Quelques commandes indispensables pour suivre les différents projets de l'AV/des CDLT

Lorsque vous arrivez sur la page d'accueil, vous trouverez un accès aux différents projets/dépôts ("repositories") et équipes ("teams") que vous venez de rejoindre. 

![](https://pad.lescommuns.org/uploads/upload_5813a5b0ea46fa97c5d060746e4ca82e.png)

Si vous cliquez par exemple sur un projet/repository, vous accédez à une page comme ci-dessous : 

![](https://pad.lescommuns.org/uploads/upload_ff3d1a92a681008c33b14acc432411fe.png)

* La **_rubrique Code_** correspond donc à tous les documents écrits venant alimenter le projet en question. Vous pouvez ajouter un nouveau fichier en        cliquant sur "add file". Deux options se présentent à vous : 
  - Cliquez sur "create new file" pour éditer un nouveau document directement sur la plateforme.
  - Cliquez sur "upload file" pour ajouter un document dont vous disposez déjà.
Avant de cliquer sur "commit changes" afin d'ajouter votre nouveau fichier ou de modifier un fichier déjà existant, assurez-vous de cocher la deuxième option (voir image ci-dessous). Cette dernière vous permettra de suggérer une fusion de vos apports au "tronc commun" du projet, ce qui plaçera donc votre fichier dans la rubrique "**Pull requests**". Les contributeurs que vous aurez choisi d'assigner (cf "Rubrique Issues" ci-dessous) pourront donc apporter leurs modifications, laisser des commentaires, pour enfin décider d'intégrer ou non votre fichier au sein du projet. 

![](https://pad.lescommuns.org/uploads/upload_f45c6389f4044aa9f5c8cc2fe0283a62.png)


**_Attention_** : Github utilise un language de balisage appelé Markdown, dont il faut connaitre certains raccourcis afin d'apporter la syntaxe nécessaire à votre fichier (gras, italique...). **Lorsque que vous créez un nouveau fichier, veillez à ajouter ".md" à la suite du titre**. ==> Voici le lien vers un [tutoriel rapide pour rédiger en Markdown ](https://guides.github.com/features/mastering-markdown/) proposé par Github.


* La **_rubrique Issues_** permet à tous les contributeurs de soumettre leurs propositions/idées qui pourraient être intéressantes pour nourrir le projet. Libre à vous d'en créer une nouvelle en cliquant sur "new issue", et de la commenter si vous souhaitez y apporter des précisions. 

Sur la droite de l'écran (seulement lorsque vous êtes identifiés comme membre / contributeur du projet), vous trouverez les options suivantes : 
  - "Assignees" vous permet d'attribuer cette issue aux personnes concernées.
  - "Labels" vous permet d'assigner les étiquettes concernées par votre issue (par exemple, si vous souhaitez signaler quelconque dysfonctionnement sur le site de l'AV, vous pouvez ajouter le label "bug").
  - "Projects" vous permet de faire passer votre issue au sein de l'outil de gestion du projet lorsque celle-ci est jugée pertinente. Vous pouvez préciser si elle est à faire, en cours, à valider, ou finie. 
  
![](https://pad.lescommuns.org/uploads/upload_63d8413d1ff5b43588a16bf3f179013a.png)


* La **_rubrique Projets_** est directement liée aux issues, telle qu'elle correspond à la mise en application des propositions. En effet, les contributeurs actifs créent un projet, et choisissent d'y ajouter ou pas les propositions formulées dans les issues. Lorsque vous cliquez sur un projet, la page suivante apparait : 

![](https://pad.lescommuns.org/uploads/upload_3515d43fadf06ebd5de079c45065f9f3.png)

Vous trouverez par exemple les les colonnes suivantes : To do/à faire ; In progress/en cours ; Done/Finie sous condition d'être validée. À vous de déplacer les cartes en fonction des avancées de votre issue. 
Les "+" en haut de chaque colonne vous permettent d'ajouter de nouvelles issues. 


* La **_rubrique Pull requests_** vous permet de retrouver tous les documents en cours d'édition, qui n'ont pas encore été fusionnés avec le "tronc commun" (la master branch) du projet, et qui sont donc encore soumis aux modifications des personnes assignées en tant que "reviewers". Lorsque vous accédez à une "pull request", vous trouverez une page telle que la suivante.
  - "Conversations" correspond à une timeline de l'ensemble des modifications et commentaires apportés à ce fichier.
  - "Commits" correspond aux différentes versions de ce document (en allant de la plus ancienne à la plus récente). 
  - "Files changed" vous permet de visualiser l'ensemble des modifications apportées à votre document. Ce qui est surligné en rouge correspond à ce qui a été remplacé par ce qui est surligné en vert. 

![](https://pad.lescommuns.org/uploads/upload_e1e31f5ae1dc55c697b698b631e6ded2.png)

**Si vous êtes l'éditeur du document et que vous souhaitez le modifier** : cliquez sur la dernière version présente, puis sur les trois petits points en haut à droite du document, et enfin sur "edit file".
![](https://pad.lescommuns.org/uploads/upload_a406622076f20f910c71bc6653ae608f.png)

**Si vous êtes "reviewer" du document et que vous souhaitez le commenter** : Dans la rubrique "files changed", cliquez sur "review changes", rédigez votre commentaire tout en vous assurant de cocher "comment" puis cliquez sur "submit request". Votre commentaire apparaitra dans la rubrique "conversations" et pourra alors être traité par l'éditeur du document. 
![](https://pad.lescommuns.org/uploads/upload_9a74b6ff89117f64f37c628b55f1410d.png)

Si vous considérez que votre document est complet, et que l'ensemble des "reviewers" sont satisfaits de sa version finale, vous pouvez cliquez sur "merge pull request" puis sur "confirm merge" ce qui vous permettra de fusionner votre fichier avec le projet, que vous retrouverez donc dans la **_rubrique Code_**. 
