# Project : online shopping website

Documentation complete du projet :  
-Sujet : Projet_3-SiteBoutiqueElectronique.pdf  
-Diagramme UML du site  
-Rapport site web.pdf

Thème bootstrap venant de https://bootswatch.com/

Première installation (nécessite PHP, symfony et composer d'installés) :  
> git clone https://github.com/ArmandH94/Projet_eCommerce  
> cd Projet_eCommerce  
> composer install  

Si la connexion à bdd ne fonctionne pas :  
>Modifier le fichier .env avec les bons parametres de connexion

Mise à jour avec la derniere version :  
> git pull origin master

Mise à jour de la base de données après modification du code :  
> symfony console make:migration  
> symfony console doctrine:migrations:migrate

Importation base de données :  
phpmyadmin > Importation > ecommerce.sql  

Des images ainsi que le rapport du projet sont disponibles sur GitHub

