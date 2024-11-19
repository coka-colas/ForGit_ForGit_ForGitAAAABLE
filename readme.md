______________________________________________________________________________________
Partie 1 :

1.
	4. La commande "git init" crée un dossier caché .git à la racine du projet
		--> Initialized empty Git repository in C:/.../ForGit_ForGit_ForGitAAAABLE/.git/
	5. git add va faire passer tous les fichiers de notre projet dans la phase locale de "staging area" tandis que git commit va actualiser notre repo local
	6. Il est important de rédiger les messages de commit pour comprendre qu'est ce qui a été changé depuis la dernière fois, monter le numéro de version… etc.

2.
	1. git add
	3. Chaque ligne représente une mise à jour du repo
	5. git diff sert à afficher les modifications qui ont été faites dans les fichiers, en écriture

3.
	2. Il est utile d'avoir un fichier .gitignore pour être sûr de ne pas ajouter un fichier critique au repo, mais de quand même l'avoir à disposition s'il est utile au projet

______________________________________________________________________________________
Partie 2 :

1.
	4. Un dépôt public est accessible à tout le monde, un dépôt privé uniquement par nous
2.
	1. Cette commande sert à faire le lien entre les 2 repo, le local et le distant
	2. L'option -u établit une connexion entre une branche locale et une branche distante.

______________________________________________________________________________________
Partie 3 :

1.
	1. Pour des soucis de stabilité du code, il est recommandé de merge les branch dans le main uniquement quand on est certain de la compatibilité
	4. C'est la commande "git branch" qui permet de lister les branches

2.
	2. Il est important de bien documenter une PR pour comprendre pourquoi elle a été demandée, ce qui aura été changé, et le bien fondé de cette requête

______________________________________________________________________________________
Partie 4 :

1. Il est parfois préférable d'utiliser GitHub Flow, notamment lorsqu'il n'y a qu'une seule version active du projet. Il est également meilleur pour du déploiement continu, en monobranche

2. Les branches hotfix dans Git Flow servent à corriger rapidement des bugs critiques directement en production

______________________________________________________________________________________

Partie 5 :
1.
	1. "git clone" copie tout le dépôt distant pour en créer un nouveau localement, "git pull" récupère et fusionne les repo
	
2.
	2. Il s'agit de bien documenter le conflit pour ne pas avoir à revenir dessus par la suite.

______________________________________________________________________________________
Partie 6 :

1.
	3. "merge" combine deux branches en créant un commit de fusion, "rebase" applique les commits d'une branche sur une autre

2.
	2. Pour appliquer un commit d'une branche à une autre sans fusionner toutes les modifs

______________________________________________________________________________________
Partie 7 :

1.
	1. Les submodules permettent de gérer des dépendances externes tout en gardant la gestion indépendante du code

2.
	1. git submodule update --init --recursive
