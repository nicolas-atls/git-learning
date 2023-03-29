# Introduction à Git/GitLab.com

## Qu'est-ce que Git

Auteur : Linus Torvalds
Date de création : 2005

Alors que Linus Torvalds travaille sur le noyau Linux avec d'autres développeurs, il négocie l'accès au service propriétaire BitKeeper appartenant à BitMover. Par la suite, un développeur (Andrew Tridgell) crée son propre protocole par-dessus BitKeeper sans utiliser la couche propriétaire, ce qui provoque une controverse. Linus Torvalds prend donc la décision suivante : créer un système robuste et distribué de versionning pour permettre de travailler sur des projets de grande envergure. Aujourd'hui, Git est devenu l'un des systèmes de contrôle de version les plus populaires et largement utilisés dans le monde du développement logiciel.

Des plateformes telles que GitHub, GitLab et Bitbucket ont été créées pour héberger des dépôts Git et offrir des outils supplémentaires pour la gestion de projets, le suivi des problèmes et la révision du code.

## Présentation de gitlab.com

GitLab.com est une plateforme de développement collaboratif basée sur Git. Elle propose non seulement un hébergement gratuit de dépôts Git, mais également une suite complète d'outils pour faciliter la gestion de projets, le suivi des problèmes, la révision du code, l'intégration continue et la livraison continue (CI/CD), ainsi que d'autres fonctionnalités avancées.

### Fonctionnalités de GitLab
Voici quelques-unes des fonctionnalités clés offertes par GitLab :

 - Gestion de projets : GitLab permet de créer des projets et d'organiser le travail en groupes. Les projets peuvent être privés, internes ou publics, offrant ainsi différentes options de confidentialité.
 - Suivi des problèmes (issues) : GitLab offre un système de suivi des problèmes pour aider les développeurs à identifier, classer et résoudre les bugs et les améliorations.
 - Révision du code (Code Review) : Les demandes de fusion (Merge Requests) permettent aux développeurs de collaborer sur des modifications de code et d'effectuer des revues de code avant d'intégrer les changements dans la branche principale.
 - Intégration continue et livraison continue (CI/CD) : GitLab dispose d'un système d'intégration continue et de livraison continue (CI/CD) intégré, permettant aux développeurs de construire, tester et déployer automatiquement leur code à chaque changement.
 - Gestion des déploiements : GitLab facilite le déploiement de votre application sur différentes plateformes et environnements, tels que les serveurs, les conteneurs et les clouds.
 - Wiki et documentation : GitLab offre un wiki intégré pour documenter les projets, les procédures et les meilleures pratiques, facilitant ainsi la communication et la collaboration au sein de l'équipe.
 - Intégrations : GitLab propose des intégrations avec de nombreux autres outils et services, tels que Jira, Slack, Trello, Jenkins et bien d'autres, permettant ainsi d'améliorer la productivité et l'efficacité de votre équipe.
 - Contrôle d'accès : GitLab offre un système de contrôle d'accès granulaire, permettant de gérer les permissions des utilisateurs et de contrôler l'accès aux projets, branches et autres ressources.

### GitLab Community Edition et GitLab Enterprise Edition
GitLab propose deux éditions principales : la Community Edition (CE) et l'Enterprise Edition (EE). La CE est une version open-source et gratuite de GitLab qui offre la plupart des fonctionnalités de base. La EE, quant à elle, est une version payante qui comprend des fonctionnalités supplémentaires et avancées, telles que le support premium, la haute disponibilité, la gestion du cycle de vie DevOps, et bien d'autres, conçues pour répondre aux besoins des entreprises de toutes tailles.

### GitLab.com vs GitLab Self-Hosted
GitLab.com est la version hébergée de GitLab, où les utilisateurs peuvent créer gratuitement des comptes et commencer à utiliser la plateforme sans avoir à installer et configurer leur propre serveur. GitLab.com offre des plans gratuits et payants, avec différentes options de fonctionnalités et de stockage en fonction des besoins de l'utilisateur.

GitLab Self-Hosted, quant à lui, est la version de GitLab que vous pouvez installer et gérer sur votre propre infrastructure. Cela offre plus de contrôle et de personnalisation pour les entreprises qui souhaitent gérer leur propre instance de GitLab. La version auto-hébergée de GitLab est disponible en Community Edition (CE) et Enterprise Edition (EE).

## Pourquoi utiliser un outil comme Git ?

Il est important de comprendre les avantages d'utiliser un outil de contrôle de version tel que Git pour gérer et maintenir des projets de développement logiciel. Voici quelques raisons pour lesquelles Git est largement utilisé dans l'industrie du développement logiciel :
 - Collaboration : Git facilite la collaboration entre les membres de l'équipe en permettant à chacun de travailler sur des copies locales du code. Les développeurs peuvent ainsi travailler simultanément sur différentes fonctionnalités ou corriger des problèmes sans entraver le travail des autres.
 - Traçabilité : Git conserve l'historique complet de toutes les modifications apportées au code. Ceci est essentiel pour comprendre quand, comment et pourquoi un changement a été effectué, ainsi que pour identifier les auteurs de ces modifications.
 - Sécurité : Les mécanismes de contrôle d'accès de Git permettent de protéger le code en limitant l'accès aux seuls membres autorisés de l'équipe. Les modifications apportées au code peuvent être vérifiées et validées avant d'être intégrées, garantissant ainsi la qualité du code.
 - Gestion des versions : Git permet de créer des branches pour gérer différentes versions du code, facilitant ainsi le développement parallèle et la gestion des versions. Les branches permettent de travailler sur des fonctionnalités, des correctifs ou des expérimentations sans perturber la branche principale (main). Une fois qu'une fonctionnalité ou un correctif est terminé, il peut être fusionné avec la branche principale.
 - Résolution des conflits : Lorsque plusieurs développeurs travaillent sur un même fichier, des conflits peuvent survenir. Git offre des outils pour détecter et résoudre ces conflits, facilitant ainsi la fusion de différentes modifications.
 - Réversibilité : Grâce à l'historique des modifications conservé par Git, il est possible de revenir à une version précédente du code en cas de problèmes ou d'erreurs. Cette fonctionnalité est cruciale pour rétablir rapidement un état fonctionnel de l'application.
 - Productivité : L'utilisation de Git permet d'automatiser certaines tâches et processus, tels que les tests, les déploiements et les intégrations, ce qui augmente la productivité des développeurs et réduit les erreurs humaines.

Il facilite la collaboration, améliore la traçabilité et la sécurité, simplifie la gestion des versions et des conflits, et augmente la productivité et l'adaptabilité. Ces avantages font de Git un élément essentiel du processus de développement logiciel moderne et un choix populaire pour les équipes de toutes tailles et de tous secteurs.

Cette technologie n'est pas dédiée aux développeurs, mais l'usage est majoritairement dans ces métiers-là.
À titre d'exemple, sachez qu'un développeur s'est déjà amusé à versionner le code civil francais:
https://github.com/steeve/france.code-civil

## Les commandes indispensable :
 - status: Permet de voir l'ensemble des fichiers qui ont été modifiés, souvent utilisé au moment de commit.
 - add: La commande permet de passer un fichier modifié en mode "staged", c'est un ensemble de modifications associé à un message de contexte.
 - commit: La commande de commit permet d'ajouter le message à l'ensemble des modifications qui ont été effectuées.
 - push: Cette commande permet d'envoyer l'ensemble des modifications qui n'ont pas été mises à jour.
 - fetch: Cette commande permet de synchroniser l'état de l'origin vis-à-vis de votre local.
 - checkout: Cette commande vous permet de créer/changer de branche.
 - pull: Cette commande vous permet de récupérer les modifications qui ont été ajoutées depuis la dernière fois que vous avez synchronisé votre code.


## Les commandes avancées:
 - reset: Cette commande vous permet, lorsque vous avez `add` des fichiers et que vous voulez les remettre en unstaged file(s).
 - revert: Cette commande permettra de faire un nouveau commit qui aura pour objectif d'annuler un ancien commit. À noter qu'il est possible de faire différemment.
 - rebase: La commande permet de réappliquer l'ensemble des commits d'une branche à une autre. Attention, en cas de conflit, répéter cette commande peut être vraiment pénible.
 - merge: La commande permet de prendre l'état d'une branche, de compresser la somme de nouveaux commits en un seul et de l'appliquer à la nouvelle branche.
 - cherry-pick: Cette commande permet de récupérer un commit particulier (via son sha1) et de l'appliquer sur la branche en cours.
 - stash: Permet de prendre toutes les modifications non commitées, et de les mettre de côté pour les faire revenir plus tard.

## La différence entre rebase et merge
Il y a souvent une ambiguïté dans la compréhension des deux commandes merge/rebase:

Git Merge:
Le git merge crée un nouveau commit qui fusionne deux branches. Il préserve l'historique linéaire des deux branches en les combinant en un seul commit de fusion. En conséquence, l'historique de la branche contiendra des points de fusion où les deux branches ont été combinées, ce qui peut faciliter la compréhension de l'historique de développement et la résolution des conflits.

Git Rebase:
Le git rebase réécrit l'historique des commits en changeant la base d'une branche et en appliquant les commits de cette branche un par un sur la branche de base. Contrairement au git merge, cela crée un historique linéaire.

Dans la gestion de projet, nous utilisons souvent les deux :
 - rebase : Lorsque j'ai besoin de faire revenir la branche principale sur ma branche de développement afin de la mettre à jour.
 - merge : Lorsque je passe ma branche sur la branche principale, on utilise souvent (squash+merge), ce qui permet de n'avoir qu'un commit de l'ensemble de la fonctionnalité en historique.

### Merge
```text
            (ma-branche)---o---o---o---o---o---o 
            |                                  |
o---o---o---o (main)-------o---o---o---o---o---o
```

### Rebase
```text
            (ma-branche)---o---o---o---o---o---o 
            |              |   |   |   |   |   |
o---o---o---o (main)-------o---o---o---o---o---o
```

============================================================


# Cas pratique :

## Création d'un compte gitlab.com
  - Créer un compte
  - Créer une clé SSH
  - Ajouter sa clé SSH
  - Configurer son fichier ~/.ssh/config
  - Configuration éventuelle de votre ~/.gitconfig


## Création d'une clé SSH
Cette commande permet de créer une clé SSH qui facilite la connexion à distance :
```bash
ssh-keygen -t rsa -b 4096
```

Il est fortement recommandé d'ajouter une passphrase qui vous sera demandée à chaque interaction avec cette clé.
Sachez qu'il existe d'autres types d'authentification, notamment le GPG.


## Ajout d'une clé SSH sur gitlab.com

Pour ajouter la clé, il faudra maintenant aller dans votre compte > préférences > SSH KEY.

Dans le premier bloc, vous pouvez y copier le fichier `.pub`. Si vous avez laissé le chemin par défaut ou que c'était votre première clé SSH, celle-ci devrait se trouver sur le chemin suivant :
```bash
cat ~/.ssh/id_rsa.pub
```


## Création d'un dépôt (individuel)
Veuillez cliquer sur "New Project" [+ création de groupe]> "Blank project", et remplir toutes les informations qui vous semblent nécessaires.
Pensez à décocher l'option README.md (Initialize repository with a README), car le créer manuellement sera la première étape et cela modifiera les commandes de configuration du projet.


## Clone du repository

Maintenant que vous avez créé le projet dans l'interface, vous devriez voir un ensemble de commandes :

### 1. Configuration globale de Git
```bash
git config --global user.name "Username"
git config --global user.email "user@mail.com"
```

### 2. Créer un nouveau dépôt
```bash
git clone git@gitlab.com:your-group/your-project.git
cd your-project
git switch -c main
```

### 3. Ajout du fichier README.md
```bash
git add README.md
git commit -m "add README"
git push -u origin main
```

### 4. Depuis un projet qui existe déjà
```bash
cd existing_folder
git init --initial-branch=main
git remote add origin git@gitlab.com:your-group/your-project.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

### 5. Push an existing Git repository
```bash
cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.com:your-group/your-project.git
git push -u origin --all
git push -u origin --tags
```

Dans un premier temps vous pouvez suivre le point 1, afin de configurer votre identité sur gitlab.com.
Ensuite, utilisez la méthode 4, car c'est la plus complète et celle qui pourra vous permettre d'avoir du versioning :
 - dans un projet déjà existant
 - dans un dossier sur lequel vous n'aviez pas prévu initialement de versioning
 - en local, sans même avoir besoin de remote (pas forcément une bonne idée, mais ça se fait dans certains cas)


## Ajout du fichier README.md (Markdown)

Maintenant que nous avons le projet en local, nous allons ajouter un fichier README.md. L'avantage de ce fichier, c'est qu'il sert de page de présentation pour le projet.
Il est au format Markdown. Je vous laisserai vous renseigner plus en détail si vous ne connaissez pas ce format, mais il est très simple. Dans notre cas, vous pourrez juste utiliser des dièses pour faire des titres et des sous-titres, ça suffira. Écrivez ce qui vous passe par la tête pour présenter votre projet.

Une fois le fichier sauvegardé, faites la commande suivante :
```bash
git status
```

Pour voir les modifications réelles, vous pouvez faire la commande suivante :
```bash
git diff # possible de faire aussi : git diff README.md
```

Vous devriez voir votre fichier README.md.

Vous pouvez maintenant l'ajouter aux staged files (en attente de message de commit).
```bash
git add README.md
```

Si vous faites à nouveau la commande `git status`, vous devriez voir que le fichier est maintenant dans les staged files, écrit en vert (pour ma configuration de couleur du terminal).

Maintenant il faut y ajouter un message avec le commande suivante :
```bash
git commit -m "Describe the project on the README.md"
```

PS : à ce stade, il peut être intéressant d'installer la commande tig (mémotechnique c'est l'inverse de git) pour suivre la liste de commits que vous avez effectués. Vous devriez voir votre commit et pouvoir accéder à la liste de modifications du fichier.
```bash
brew install tig    # OSX
apt-get install tig # debian/ubuntu
# apk add ...
```
Une fois installé, il faudra juste taper tig dans le dossier qui contient le projet git.

Maintenant que le commit est effectué, vous pouvez le pousser sur le remote qui porte le nom origin et la branche par défaut qui est main. Avec la commande suivante :
```bash
git push origin main
```
Vous devriez maintenant pouvoir voir ce que vous avez écrit en description de votre projet directement en allant regarder sur gitlab.com.


## Comment collaborer

Jusqu'à maintenant, c'est bien : vous savez initialiser un projet et ajouter des fichiers dedans. Mais comment organise-t-on la collaboration ?

Pour ce faire, il y a les branches. Actuellement, vous êtes tous les deux sur la branche main. Sachez que vous pouvez en créer de nouvelles avec la commande suivante :
```bash
git checkout -b ma-nouvelle-branche # on créer une nouvelle branche avec l'option -b
```
```text
            (ma-nouvelle-branche)
            |
o---o---o---o (main)
```


Afin de changer de branche il faudra utiliser la commande suivante
```bash
git checkout main                # on revient sur la branche principale
git checkout ma-nouvelle-branche # on retourne sur ma-nouvelle-branche
```

Vous travaillez chacun sur votre branche de façon indépendante puis vous envoyer votre code sur votre provider git.
```bash
git add path/to/file1 otherpath/to/file2 # Ajout des fichiers modifier
git commit -m "votre message"            # Ajout du message qui représente l'ensemble des modifications
git push origin ma-nouvelle-branche
```
```text
                                 votre message
                                    ↓
            (ma-nouvelle-branche)---o 
            |
o---o---o---o (main)
```

A ce moment là, il faudra aller sur gitlab.com (ou github.com), pour créer une MR (ou PR sur github) en direction de la branche main.
Vous pourrez alors regarder l'ensemble des modifications, mettre les liens d'informations nécessaire pour aider a la compréhension du contexte.
Intéragir en laissant un message, ou en pointant une ligne de code en particulier.
Une fois que la MR à été approuve, vous pouvez la merge. Et tout ça depuis les interfaces.

Voici ce qu'il s'est passer sur le remote git:
```text
                                 votre message
                                    ↓
            (ma-nouvelle-branche)---o 
            |                       |
o---o---o---o (main)----------------o

```

Sauf que si vous vous déplacer sur votre branche main (`git checkout main`), vous verrez ceci :
```text
                                 votre message
                                    ↓
            (ma-nouvelle-branche)---o 
            |
o---o---o---o (main)
```
Car votre local n'est pas au courant que le code à été merge, pour le mettre à jour utiliser la commande suivante:
```bash
git pull # personnellement j'utilise toujours les précisions du nom du remote et de la branche (git pull origin main)
git checkout -b une-autre-feature # On peut repartir sur une nouvelle feature avec le code à jour
# ...
```

### Exemple:
Lorsque vous travaillez a plusieurs sur un même projet c'est pour la majeur parti du temps "chacun sa branche". Les interventions sur la branche de quelqu'un sont rare, on préfèrera passer par le système de review et mettre des commentaires pour que l'auteur du code modifie lui même, car il aura une meilleure visibilité sur l'ensemble du contexte.

Exemple:
```bash
git checkout -b add-user-unsubscribe-endpoint
# [...] l'utilisateur créer modifie et supprime des fichiers
git status
# [...] list all updated files
git add # [...] seulement quelques fichier d'une étape préparatoire
git commit -m "add unsubscribe on the user entity"
git add # [...] les autres modifications qui sont en lien avec l'ajout du endpoint d'api
git commit -m "add unsubscribe api endpoint"
# Cette exemple permet aussi de mettre en avant le fait que vous n'ayez pas à effectuer un commit pour un push.
git push origin add-user-unsubscribe-endpoint
```

Maintenant que l'user à push, sur gitlab.com lorsque vous allez dans votre projet vous devriez voir une MR (merge request) [sur github.com ça s'apppel des PR (Pull Request), mais c'est la même chose], il faudra alors créer cette MR (ou plutot la validé), en lui disant que vous voulez l'envoyer sur la branche `main` (la branche de référence du projet).

A ce moment vous allez voir une MR en attente de review, le processus qui permet au développeurs d'effectué un controle qualité, et de s'assurer que ça respecte bien la feature initilaement demandé, ou que ça corrige bien le bug qui à été report.

Une fois que la review a été faite, soit vous avez des commentaires a corrigé, il faudra les corriger les resolves et les re-push.
Ou alors ça a été validé sans commentaire et vous pouvez maintenant merge le code sur la branche `main`.

Les collaborateurs sur le projet pourront alors récupérer le code qui aura été mis à jour:
```bash
git checkout main    # le collaborateur doit revenir sur la branche de référence
git fetch --all      # permet de mettre a jour les références entre le remote et le local (si de nouvelles branches sont créer par d'autres sur le remote le local ne le sait pas)
git pull origin main # permet de récupérer le code qui a été merge sur main
git checkout ma-branche-avant-pull # l'utilisateur revient sur le code qu'il avait laisser avant le feature
git rebase main      # permettra a l'utilisateur de rebase la branche qui vient d'être merge sur sa feature en cours
```

Je tiens à préciser que la gestion des MR peut être configurée de manière très précise, par exemple :

 - On peut mettre en place une pipeline, un ensemble de tests automatiques qui assurent la qualité et la conformité du code.
 - On peut mettre en place des sécurités, la MR ne peut pas être fusionnée tant qu'un certain nombre de personnes n'ont pas approuvé la MR.
 - On peut configurer la façon dont Git fusionne les branches. Personnellement, je préfère "squash" avant le commit, ce qui signifie que l'ensemble des commits d'un développeur sur une fonctionnalité sont compactés en un seul commit.


### Faisons maintenant un cas pratique sur [ce repository](https://gitlab.com/ffs-formation/git-learning):

1. Il vous faudra utiliser la commande suivante pour le cloner (méthode 2), car le dépôt existe déjà.
2. Créez chacun votre branche (astuce : généralement, on insère le numéro de ticket dans le nom de la branche).
3. Ajoutez chacun un fichier du nom que vous voulez, mais pas le même nom (on verra ça ensuite ;)).
4. Le premier à avoir fini crée sa MR/PR.
5. Le deuxième devra alors relire le code du premier.
6. Merger le code du premier.
7. Les développeurs devront se mettre à jour :
  7.a Changer de branche pour aller sur la branche principale (si fonctionnalité en cours).
  7.b Récupérer le dépôt distant (ils devraient voir apparaître le nom de la branche du premier qui a été ajoutée au dépôt distant lors de la poussée).
  7.c Récupérer le code (l'étape b n'est pas obligatoire dans notre cas précis).
  7.d Revenir sur sa branche individuelle (si feature en cours).
  7.e Rebase la branche principale sur sa branche (si feature en cours).
8. Le deuxième termine son code.
9. Le deuxième peut ouvrir sa MR/PR.
10. Le premier peut review la MR.
11. Le deuxième peut merge son code.
12. Tout le monde se met à jour.

### Reprenons l'exemple précédent, mais avec un conflit

1. Il vous faudra utiliser la commande suivante pour le cloner (méthode 2), car le dépôt existe déjà.
2. Créez chacun votre branche (astuce : généralement, on insère le numéro de ticket dans le nom de la branche).
3. Ajoutez chacun un fichier du nom que vous voulez, mais pas le même nom (on verra ça ensuite ;)).
4. Le premier à avoir fini crée sa MR/PR.
5. Le deuxième devra alors relire le code du premier.
6. Merger le code du premier.
7. Les développeurs devront se mettre à jour :
  7.a Changer de branche pour aller sur la branche principale (si fonctionnalité en cours).
  7.b Récupérer le dépôt distant (ils devraient voir apparaître le nom de la branche du premier qui a été ajoutée au dépôt distant lors de la poussée).
  7.c Récupérer le code (l'étape b n'est pas obligatoire dans notre cas précis).
  7.d Revenir sur sa branche individuelle (si feature en cours).
  7.e Rebase la branche principale sur sa branche (si feature en cours).
  7.f Résoudre les conflits
8. Le deuxième termine son code.
9. Le deuxième peut ouvrir sa MR/PR.
10. Le premier peut review la MR.
11. Le deuxième peut merge son code.
12. Tout le monde se met à jour.


La ligne qu'il faudra modifier