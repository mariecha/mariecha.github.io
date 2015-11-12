CMS COURS 3


Création du répertoire "sites":

- aller dans systèmes de fichiers -> home -> clique droit -> ouvrir le terminal


Ecriture dans le terminal : 

entrer : sudo mkdir sites
entrer le mot de passe

entrer : sudo chmod 777 sites



Installation de Jekyll : 

entrer : apt-get (vous ouvrez un fichier d'aide, avec la définition de apt-get et son utilisation).
entrer : sudo apt-get install jekyll
Vous souhaitez continuer l'installation, entrer "o" et taper sur entrée.

entrer : jekyll -v
Vous vérifiiez alors que jekyll est bien installé, il vous affichera également la version du logiciel installé.



Lancement de Jekyll : 

entrer : jekyll (vous ouvrez un fichier d'aide et de commandes)


Création d'une page :

créer une page index.html dans le répertoire "sites"

entrer : jekyll build index.html
aller dans votre répertoire "sites", on verrez qu'il a créé "_site" -> puis il génère "index.html"

vous pouvez faire un "jekyll serve -w" -->  le "-w" sert à afficher les changements apporté au fichier



Mise à jour de Jekyll : 

//


Github  - création d'un compte et d'un référentiel
Retourner sur votre ordinateur, ouvrir un navigateur web
créer un compte utilisateur sur le site github.com
aller sur le site : https://pages.github.com et suivre les instructions pour réaliser la procédure 


Sur le site github : créer un nouveau référentiel nommé nom d'utilisateur.github.io

Cloner le dépôt : 
entrer : git clone https://github.com/nom d'utilisateur/nom d'utilisateur.github.io


Créer un fichier "index.html" :
entrer : cd nom d'utilisateur.github.io
entrer : écho "bonjour tout le monde"> index.html


Poussez : 
entrer : git add .
entrer : git commit -m "description de la modification"
entrer : origin master -u git push


