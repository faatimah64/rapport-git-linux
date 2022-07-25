---
title: |
  ![](./img/Logo.png){width=2in}  
  "Projet de DevOp's"
subtitle: "Overview"
date: \today{}
lang: fr-FR
urlcolor: blue
geometry: "left=2.5cm,right=2.5cm,top=3cm,bottom=3cm"
documentclass: article

---
# Redaction rapport
## Les commandes de lunix

**1. La Commande pwd **
Cette commande permet d’afficher l’emplacement ou on se situe actuellement dans la hiérarchie FHS.
  ![](./img/pwd.png){width=2in}  
**2. La Commande cd **
Cette commande permet de changer de répertoire courant et de se situer sur un autre
  ![](./img/cd.png){width=2in}  

**3. La Commande ls **
Permet de lister les fichiers disponibles dans un répertoire, si appelé sans arguments, ls liste les fichiers du répertoire courant.
  ![](./img/ls.png){width=2in}  

**4. La Commande mkdir**
Cette commande permet de créer un répertoire.
"mkdir nom du repertoir"
  ![](./img/mkdir.png){width=2in} 
  on voit le fichier "essaie" 

**5. La Commande rmdir**
Cette commande permet de supprimer un répertoire.
"rmdir nom du repertoir"

  ![](./img/rmdir.png){width=2in}  
  on voit plus le repertoir "essaie" 

**6. La Commande touch**
Cette commande permet de changer la date du dernier accès ou modification d’un fichier, mais permet également de créer un fichier vide.
utilisation: touch nom du fichier.extension 
  on voit le fichier "essaie" 

**7. La Commande cp**
Cette commande permet de copier un repertoir ou un fichier.

**8. La Commande rm**
Cette commande permet de supprimer un fichier ou un répertoire. Cette commande est à utiliser avec précaution car avec l’option -f ou -rf, cette commande peut endommager voir supprimer tout votre système de fichiers de manière irréversible.


**9. La Commande mv**

Cette commande sert à renommer ou déplacer un fichier ou un répertoire.
Dans l’exemple suivant, on va créer un fichier nommé “fichier3”, et à l’aide de la commande mv, on va le renommer en “fichier4” et le déplacer dans le répertoire “/home” en une seule fois.

**10. La Commande cat**
Cette commande permet d’afficher le contenu d’un fichier.
  ![](./img/cat.png){width=2in}  


**12. La Commande more**
La commande more permet de visualiser le contenu d’un fichier page à page. Utilisez la touche entrée ou espace pour avancer l’affichage du contenu de votre fichier.
  ![](./img/more.png){width=2in}  


**13. La Commande head**
La commande head permet d’afficher le début d’un fichier (par défaut, les 10 premières lignes). Pour démontrer son fonctionnement, j’ai créé un fichier nommé fichier2 avec un contenu de 20 lignes.
  ![](./img/head.png){width=2in}  


**14. La Commande tail**
La commande tail permet d’afficher la fin d’un fichier (par défaut, les 10 dernière lignes)
  ![](./img/tail.png){width=2in}  

## LES Commandes de bases  de  git

**1.Git config**
L’une des commandes git les plus utilisées est git config. On l’utilise pour configurer les préférences de l’utilisateur : son mail, l’algorithme utilisé pour diff, le nom d’utilisateur et le format de fichier etc. Par exemple, la commande suivante peut être utilisée pour définir le mail d’un utilisateur:
  ![c](./img/config.png){width=2in}  

** Git init**
 Cette commande est utilisée pour créer un nouveau dépôt GIT
   ![](./img/init.png){width=2in}  

**Git add**
  ![](./img/add.png){width=2in}  

  La commande git add peut être utilisée pour ajouter des fichiers à l’index. Par exemple, la commande suivante ajoutera un fichier nommé temp.txt dans le répertoire local de l’index
**git clone**
  ![](./img/clone.png){width=2in}  

	La commande git clone est utilisée pour la vérification des dépôts. Si le dépôt se trouve sur un serveur distant, utilisez:
** Git commit**
  ![](./img/commit.png){width=2in}  
  ![](./img/commit2.png){width=2in}  

	La commande git commit permet de valider les modifications apportées au HEAD. Notez que tout commit ne se fera pas dans le dépôt distant.

** Git status**
  ![](./img/status.png){width=2in}  

	La commande git status affiche la liste des fichiers modifiés ainsi que les fichiers qui doivent encore être ajoutés ou validés. 

**Git push**
	Git push est une autre commandes GIT de base. Un simple push envoie les modifications locales apportées à la branche principale associée 
  ![](./img/push.png){width=2in}  

**Git checkout
  ![](./img/checkout.png){width=2in}  

	La commande git checkout peut être utilisée pour créer des branches ou pour basculer entre elles. Par exemple nous allons créer une branche:

**Git remote**
  ![](./img/remote.png){width=2in}  

	Cette commande remote permet à un utilisateur de se connecter à un dépôt distant. La commande suivante répertorie les dépôts distants actuellement configurés:

**git branch**
  ![](./img/branch.png){width=2in}  

	La commande git branch peut être utilisée pour répertorier, créer ou supprimer des branches. Pour répertorier toutes les branches présentes dans le dépôt, utilisez:

**Git pull**
	Pour fusionner toutes les modifications présentes sur le dépôt distant dans le répertoire de travail local, la commande pull est utilisée. Usage:
  ![](./img/pull.png){width=2in}  


**Git merge**
	La commande git merge est utilisée pour fusionner une branche dans la branche active. Usage:
  ![](./img/merge.png){width=2in}  

**Git log**
	L’ exécution de cette commande génère le log d’une branche.
  ![](./img/log.png){width=2in}  

Git reset
	Pour réinitialiser l’index et le répertoire de travail à l’état du dernier commit
  (j'evite de l'utiliser)

Git rm
•	Git rm peut être utilisé pour supprimer des fichiers de l’index et du répertoire de travail. Usage:
  (j'evite de l'utiliser pour ne pas supprimer des choses importante)

**Git stash**
	L’une des moins connues, git stash aide à enregistrer les changements qui ne doivent pas être commit immédiatement. C’est un commit temporaire. Usage:
  ![](./img/stash.png){width=2in}  





