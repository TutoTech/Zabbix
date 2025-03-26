Ce script permet d'installer et de configurer Zabbix 7.0 sur un serveur Debian 12. Il suit les étapes officielles de la documentation de Zabbix pour garantir une installation fiable. Le script inclut les étapes suivantes :
Définition des variables : Il configure des variables telles que le mot de passe pour la base de données Zabbix, le nom du serveur pour Nginx, et le port d'écoute pour Nginx.
Affichage des messages colorés : Le script définit des codes pour afficher des messages d'information, de succès et d'erreur avec des couleurs distinctes.
Mise à jour des paquets : Avant l'installation, il met à jour les paquets système pour s'assurer que le serveur est à jour.
Installation du référentiel Zabbix : Il télécharge et installe le référentiel officiel Zabbix pour Debian 12 à partir de leur dépôt.
Installation des paquets Zabbix : Une fois le référentiel installé, il procède à l'installation de Zabbix et de ses dépendances nécessaires.
Configuration de Zabbix : Après l'installation, le script configure Zabbix selon les paramètres définis par l'utilisateur, notamment la base de données et le serveur Nginx.
Gestion des erreurs : En cas d'échec d'une étape, le script affiche un message d'erreur et s'arrête.
