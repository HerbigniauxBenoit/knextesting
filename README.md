# knextesting
Pour générer un projet avec knex.js voici les étapes à suivre :
	Tout d’abord nous devons générer notre fichier package.json avec la commande suivante : « npm init ». Cela va nous permettre de pour packager notre solution. 
	
Puis nous devons installer le package de knex.js, express body-parser & les modules de base de données souhaiter avec la commande « npm install --save express body-parser knex bookshelf mysql ». TO DO, regarder à quoi servent les package knex.js, express body-parser (courte explication).

On génère ensuite un fichier « ./knexfile.js » avec la commande « knex init ». Ce fichier nous permet de configurer les environnements de travail et leurs bases de données associer. Après avoir créé nos tables dans le un dossier et créé un fichier de migration on peut lancer la migration avec la commande « knex migrate:latest --env production »
