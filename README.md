<h2>Bienvenue dans la partie "front-end" de l'application ProxiBanque</h2>


<h4>Installation</h4>


Avant de pouvoir utiliser cette application, veuillez suivre les instructions pour installer la partie "back-end", qui s'occupe de la persistance des données en BDD, disponibles à cette adresse : https://github.com/Khantain/proxibanquev4

Veuillez ensuite télécharger node.js en version LTS (s'il n'est pas déjà installé sur votre ordinateur) à cette adresse: https://nodejs.org/fr/
La version disponible au 16 janvier 2019 est la 10.15.0.

Une fois l'ainstallation de node.js terminée, veuillez entrer dans l'invite de commande Windows :
-Sur windows 10, taper "cmd" dans la barre de recherche windows située en bas à gauche du Bureau et cliquer sur "Invite de commande"
-Sur windows 8 et antérieur, ouvrir le menu Démarrer et rechercher "cmd" pour obtenir l'invite de commande.

Entrer la commande suivante : npm install -g ng-cli, afin d'installer Angular CLI qui lancera l'application Proxibanque.

Vérifier que node.js et Angular CLI sont bien installés à l'aide des deux commandes suivantes :

npm -v (qui renverra la version du gestionnaire de packages de node.js)
ng --version (qui renverra notamment la version d'Angular CLI)

Ensuite veuillez copier le fichier "proxibanquev4_angular.war" dans le dossier webapps de votre dossier apache-tomcat-8.5.xx. un eofis la copie terminée, veuillez double cliquer sur le fichier "startup.bat" du dossier bin dans apache-tomcat-8.5.xx


<h4>Utilisation</h4>

Veuillez ensuite entrer l'adresse http://localhost:4200 dans votre navigateur (nous recommandons le navigateur Chrome de Google
téléchargeable à cette adresse si besoin : https://www.google.com/chrome/ )

Si vous utilisez les données de base  de la partie back-end, vous pourrez directement participer au sondage Proxibanque en cours en postant un commentaire positif ou négatif. Pour poster un commentaire positif, il vous faudra vous identifier auprès de Proxibanque soit en communiquant un identifiant à 8 chiffres (il existe deux clients par défaut avec les identifiants 12345678 et 00459486) soit en commniquant nom, prénom + email et/ou numéro de téléphone.

Vous pouvez également poster un commentaire négatif en laissant un commentaire.

Bonne navigation.
