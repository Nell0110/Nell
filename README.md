# Nell
Quel est le résultat de la commande suivante :

$ git status



PS C:\Users\ntechel> git status
warning: could not open directory 'Application Data/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Local Settings/': Permission denied
warning: could not open directory 'Menu Démarrer/': Permission denied
warning: could not open directory 'Mes documents/': Permission denied
warning: could not open directory 'Modèles/': Permission denied
warning: could not open directory 'Recent/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
warning: could not open directory 'Voisinage d'impression/': Permission denied
warning: could not open directory 'Voisinage réseau/': Permission denied
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   change-me
(en rouge)
---------------

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   change-me
        deleted:    delete-me
(en vert)

--------------------------------------

la commande find pour rechercher les répertoires (-type d) dont le chemin contient un motif */.*, puis les exclut (-prune) et imprime le reste des chemins.
la commande sed pour effectuer des substitutions dans les résultats de find.
 "| " recherche le motif suivi d'un caractère autre qu'un espace, et le remplace par "|-- " suivi de ce caractère.

En bref, cette commande `find` explore tous les répertoires, sauf ceux dont les chemins contiennent le motif `*/.*`, puis elle affiche les chemins qui ont été trouvés. Ensuite, `sed` intervient pour transformer la sortie de `find` en une représentation visuelle de l'arborescence des répertoires. Elle utilise des lignes verticales "|", avec des marqueurs "--" pour les sous-répertoires, offrant ainsi une vision claire de la structure du système de fichiers.

---------------------------------------

Quel est le résultat de la commande suivante :

$ git status -uall
La commande git status -uall affiche l'état des fichiers dans votre dépôt Git, y compris les fichiers non suivis et non suivis.

----------------------------------------

Précisez quel est le résultat de son exécution ?


PS C:\Users\ntechel> git branch dev
PS C:\Users\ntechel> git branch
  dev
* main

-----------------------------------------

Quel est le résultat de chacune de ces deux commandes ?


D       delete-me
PS C:\Users\ntechel>  git stash
Saved working directory and index state WIP on dev: 390da05 initial
PS C:\Users\ntechel> git checkout dev
Already on 'dev'

-----------------------------------------

Quel est le résultat de la commande :

$ git status -uall

La commande git status -uall affiche l'état des fichiers dans votre dépôt Git, y compris les fichiers non suivis 

-------------------------------------------

