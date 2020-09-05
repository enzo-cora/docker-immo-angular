# Tester l'App web immobilière avec Docker-compose 
L'application à été réalisée avec Nodejs / Angular / Nginx et nécéssite Docker pour être lancée.

## Lancer l'application: 
> docker-compose up 
### Se connecter en tant qu'admin : 
* mail : admin@gmail.com
* password : admin

## Le docker-compose :
Dans le but de laisser transparaitre le contenu des images(pour qui veut), leur construction se fait localement (elles ne sont donc pas téléchargées depuis mon Docker Hub) 

### 4 micros-services : 4 images , 4 containers
* Site Web 
* Api Rest 
* Reverse Proxy 
* Base de données 

### Configuration par defaut : 
*PORT par défaut : 80 
*HOTE par défaut : localhost
Les configurations peuvent être changées dans le fichier : 

### Changer la configuration : 
>.env






