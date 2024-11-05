# Answers of <students-firstname> <students-lastname> <github-username>

## Basics
### Task 1
un dossier cachée .git qui Permet à Git de stocker toutes les informations nécessaires pour que Git 
puisse gérer les versions de votre projet

un dossier img qui contient un fichier au format SVG appellé gitgraph.svg qui est utilisé
pour visulaliser graphiquement l’historique des commits et de la structure des branches d'un dêpot Git.

un fichier au format markdown answers.md qui est généralement utilisé pour documenter des réponses ou 
des explications dans un projet. Dansn notre cas il contient les réponses du laboratoire.

### Task 2
Un Untracked Files appelle README.md est apparu. Il est untracked vu que Git a détecté l'existence de ce 
fichier dans votre répertoire de travail, mais qu'il ne le suit pas encore (il faut le stage).

### Task 3
Le Untracked Files a été supirmé. Le README.md est devenu un Staged Files, donc Git le suit.

### Task 4
Le fichier README.md est devenu unstaged car on l'a modifié et que l'on ne la pas re-stage.

### Task 5
La chaîne de caractères est l'identifiant de commit.

HEAD est un pointeur spécial dans Git qui représente la référence actuelle du dépôt, c'est à dire qu'il 
pointe sur le commit actuel.


main est le nom de la branche principale du dépôt dans laquelle on travaille.

Après les parenthèses c'est le message du commit, en l'occurrence "ADD: README file.".

### Task 6
Apres le checkout commit sur Initial commit, les fichiers et dossiers ont été réinitialisés
à leur état de départ. 

Apres le checkout sur le dernier commit, les fichiers ont retrouvé leur état final. c'est a dire qu'ils
sont redevenus comme avant que l'on fasse le premier commit sur Initial commit.

## Gitgraph

### Task 7
1) C'est le nom de la branche utilisée pour le développement en cours

2) C'est le hash du commit, ce sont des identifiants unique pour chaque commit ce qui permet de 
les différencier.

3) C'est le message rentrer lors du commit 

4) C'est l'auteur du commit, ce qui montre qui a commit les modifications.

5) C'est la version du projet

Points numérotés sont des commits, ce qui permet de visualiser l'historique des modifications.
Commit 6 : Point de départ de la branche jaune (branche secondaire).
Commit 7 : Un commit sur la branche jaune.
Commit 8 : Commit de fusion entre la branche jaune et la branche principale (bleue).
Commit 9 : Un commit sur la branche principale après la fusion.
Commit 10 : Un autre commit sur la branche principale après le commit 9.

La ligne bleu est la branche principale qui continue tout au long de l'image.

La lign jaune est la branche secondaire qui est issue du commit 6.

La ligne grise est un ligne de fusion qui rejoint les branches jaune et bleue au niveau du commit 8, 
marquant le point où la branche jaune a été fusionnée dans la branche principale.

![Gitgraph](img/gitgraph.svg)