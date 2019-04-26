 ### Adding an existing project to github using the command line
https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line

### Prérequis
- [Git](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git)
- [NodeJS](https://nodejs.org/en/download/)
- [MongoDB](https://docs.mongodb.com/manual/administration/install-community/)

### Étapes

Cloner l'application :
```
$ git clone https://github.com/IkramTi/ReactJSMongoDBAuthentication.git
```
Se mettre dans le dossier de l'application :
```
$ cd PFA2017
```
Installer les dépendances de l'application :
```
$ npm install
$ npm install bower -g
$ cd public
$ bower install
```
Créer une variable d'environnement pour mongodb:

- Ajouter la variable d'environnement qui pointe vers : C:\Program Files\MongoDB\Server\3.6\bin dans mon cas

Démarrer MongoDB quelque part :

- Go to C drive and create a folder db in the path C:\data\db
- Enter la ligne de commande:  C:\Program Files\MongoDB\Server\3.6\bin>mongod

```
$ mkdir db
$ mongod --dbpath db
```
Démarrer l'application :
```
$ node index.js
```
