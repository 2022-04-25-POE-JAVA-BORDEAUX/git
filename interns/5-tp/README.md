# Travaux pratiques : travail collaboratif avec Git et Github
## Consignes
## PARTIE 1

#### Formation des groupes

- Groupe de 3 personnes
- Dans chaque groupe
  - 1 Owner : créateur et responsable du dépôt Git
  - 2 developers : développeurs extérieurs qui participent au projet

#### Rôle du owner

- Tâches du owner
  1. Créer un dépôt github nommé tp-git avec les fichiers
     - README.md contenant les instructions pour récupérer le projet en local
     - .gitignore
     
  2. Inviter les 2 développeurs qui doivent collaborer dans ce projet et le formateur dont l'adresse e-mail est contact@tshimini.fr

     - Settings > General > Access > Collaborators > add people

     **Illustration**

  ![Catpure ecran](./../img/access.png)

  3. Désigner développeur 1 et développeur 2 (nécessaire pour attribuer les tâches à chacun)

  4. Créer 2 issues

     1. Première issue nommée **feat/morning_menu** et assigner le développeur 1

     2. Deuxième issue nommée **feat/lunch_menu** et assigner le développeur 2

        Vous pouvez rajouter les **Labels** de votre choix parmi la liste proposée

        **Illustration**

        ![issue](D:\freelance\formations\coderbase\poe_fullstack_java_bordeaux\interns\img\issue_1.png)

     ![issue2](D:\freelance\formations\coderbase\poe_fullstack_java_bordeaux\interns\img\issue_2.png)

  5. En local

     1. Récupérer le dépôt distant
     2. Créer une branche nommée **main** 
     3. Pusher

  6. Accepter, publier ou rejeter les pull requests des développeurs

     - En cas de rejet, dire aux développeurs la raison du refus en utilisant les outils mis à disposition sur github
     - Gérer les conflits lors des merge request sur la branche main

  7. Après avoir effectué les merge request sur la branche main

     1. Créer une branche nommée **feat/prices**
     2. Ajouter les prix aux produits présents dans les fichiers menu.txt
     3. Pusher la branche feat/prices
     4. Faire le merge request de cette branche dans la branche main

  8. Prévenir vos collaborateurs de l'ajout des prix

#### Rôle du premier développeur

1. Accepter l'invitation reçue 
2. Récupérer le projet en local
3. Créer une nouvelle branche dont le nom est identique à celle de l'issue à laquelle vous avez été assignée
4. Créer un dossier morning
5. Créer un fichier nommé menu.txt qui doit contenir un ou plusieurs viennoiseries, boissons de votre choix 
6. Commiter et pusher vers le dépôt distant
7. Faire une demande de pull request :
   1. En mettant le développeur 2 en tant que  **Reviewers** pour la revue du code
   2. Assigner le owner dans **Assignees**
   3. Ajouter un petit commentaire pour expliquer votre travail
8. Après avoir été prévenu de l'ajout des prix sur les fichiers menu.txt
   1. Récupérer tous les changements effectués sur le dépôt distant en local
   2. S'il y a des conflits, les gérer en communiquant avec vos collaborateurs

#### Rôle du second développeur

1. Accepter l'invitation reçue 
2. Récupérer le projet en local
3. Créer une nouvelle branche dont le nom est identique à celle de l'issue à laquelle vous avez été assignée
4. Créer un dossier lunch
5. Créer un fichier nommé menu.txt qui doit contenir un ou plusieurs menus avec entrées, plats, boissons ou desserts de son choix avec les tarifs pour chaque 
6. Commiter et pusher vers le dépôt distant
7. Faire une demande de pull request : 
   1. En mettant le développeur 1 en tant que  **Reviewers** pour la revue du code
   2. Assigner le owner dans **Assignees**
   3. Ajouter un petit commentaire pour expliquer votre travail
8. Après avoir été prévenu de l'ajout des prix sur les fichiers menu.txt

   1. Récupérer tous les changements effectués sur le dépôt distant en local
   2. S'il y a des conflits, les gérer en communiquant avec vos collaborateurs