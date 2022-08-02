## *GitHub*

## 1 Présentation
### 1.1 GitHub

*Plateforme colleborative* Pour dev, plus grand espace de stockage de travaux collaborative dans le monde! GitHub en lui-même n'est plus qu'un reseau social comme FB. Vous construisez un profil, vous y deposez des projets à partager et vous vous connectez avec d'autre utilisateurs en suivant leurs comptes. Meme si la plupart des utilisateurs y deposent des projects de programmes ou de code, rien ne vous empeche d'y placer des textes ouo tout type de fichier à présenter dans vos repertoires de projets.

### 1,2 Git
Git est un *logiciel de controle de version*, ce qui signifie qu'il gere les modifications d'un projet sans écraser n'importe quelle partie du projet.


## 2 Git et GitHub
### 2.1 Vocabulaire
**ligne de commande**: En gros : le programme de l'ordinateur que nous utilisons pour entrer des commandes Git. Dans le monde UNIX, on dit qu'on travaille en "ligne de commande" pour désigner le fait d'interagir avec un système informatique en entrant des lignes d'instruction textuelles dans un terminal, et non à l'aide d'une interface graphique.
Les commandes tapées dans le terminal sont interprétées par un shell.
Journal du Net <https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/>

**Depot**: Un repertoire ou de l'espace de stockage ou vos projets peuvent vivre; les utilisateurs de GitHub raccourcissent en "repo" pour "repository". Il peut etre un espace de stockage sur GitHub ou un autre hebergeur en ligne. A l'intérieur d'un depot, vous pouvez conserver des fichiers de codes, des fichiers txt des images.


**Controle de version**: Fondamentalement, l'objectif pour lequel Git a ete concu. Quand vous avez un fichier Word, vous l'écrasez à chaque fois que vous sauvegardez plusieurs versions. Avec Git, vous n'est plus obligé de faire ça. Git conserve des "instantanes" de chaque point dans l'historique d'un projet, de sorte que vous ne pouvez jamais le perdre ou l'ecraser.

**Commit**: C'est la commande qui donne à git toute puissance. Quand vous committez, vous prenez un instantané, une photo de votre depot à ce stade vous donnant point de controle que vous pouvez ensuite réévaluer ou tout simplememennt restaurer votre projet à cette version. Il est nécessaire de rappeler que le nom de vos commits doivent-être parlant afin de savoir à quel stade du projet celui-ci a été fait.

**Branche**: Comment plusieurs personnes travaillant sur un projet en meme temps sans que Git ne s'embrouille? Habituellement, elle se débranchent du projet principal avec leur propres versions complètes, des modifications qu'elles on chacune produites de leur cote.
Apres avoir termine, il est temps de fusionner cette branche pour la ramener vers la branche master, le repertoire principal du projet;




### 2.2 Commandes specifique Git

**git init**: Initialise un nouveau depot git jusqu'a ce que  vous executiez les commandes Git qui suivent.

**git config** Raccourci de configuration, ceci est tout particulièrement utile quand vous paramétrez Git pour la premiere fois indentifiant et mot d'utilisateur.

**git help**: oublie une commande? pour afficher les 21 commande de git;

**git status**: Verifie le status de votre repo. Voir les fichiers et quelle sont les modifications à commiter et sur lquelle branche ou repo vous etes en train de travailler.

**git add**: Ceci n'ajoute pas des fichiers dans votre repo, Au lieu de cela, cela porte de nouveaux fichiers à l'attestation de Git. Apres avoir ajoute des fichiers, ils dont inclus dans les instantanes du depot Git.

**git commit**: La commande la plus importante de Git. Aprres avoir effectue toute sorte de modification vous entrez ca afin de prendre un instantane du depot. le mettre en memoire.On ecrit ca sous la forme de git commit -u 'votre message'. Le -m indique que la section suivante de la commande devrait etre lu comme un message.

**git branche**:Vous travaillez avec plusieurs collaborateurs et vous voulez produire des modification de votre cote? cette commande vous permet de construire une nouvelle branche, ou une chronologie de commits, des modifications et des ajouts de fichiers qui sont completement les votres. votre titre va apres la commande.Si vous vouliez creer une nouvelle branche appellee 'yacin' vous saisiriez git branche yacine.

**git checkout**: C'est une commande de navigation qui vous permet de vous deplacer vers le repertoire que vous voulez verifier. Vous pouvez utiliser cette commande sous la forme de git checkout master pour regarder la branche master, ou git checkout yacine poour regarder une autre branche.

**git merge**: Lorsque vous avez fini de travailler sur une branche, vous pouvez fusionner vos modifications vers la branche master, qui est visible pour tous les collaborateur. git merge yacine prendrait toutes les modifications que vous avez apportées à la branche yacine et les ajoutera à la branche master.

**git push**: Si vous travaillez sur votre ordinateur en local et vous voulez que vos commits soient visibles aussi en ligne sur GitHub, vous pushez les modifications vers GitHub avec cette commande.

**git pull**: Si vous travaillez en local et que vous voulez la version la plus a jour de votre repo pour travaillez dessus, vous pullez les modifications provenant de GitHub avec cette commande.

**git clone**: Permet de dupliquer, cloner un existant sur GitHub pour l'avoir en local.
La commande git clone doit etre suivit de url de repo correspondant qui copie depuis GitHub direct.