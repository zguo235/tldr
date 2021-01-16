# apt-get

> Utilitaire de gestion des paquets Debian et Ubuntu.
> Recherche des paquets en utilisant `apt-cache`.

- Mise à jour de la liste des paquets et des versions disponibles (il est recommandé de l'exécuter avant les autres commandes `apt-get` :

`apt-get update`

- Installation d'un paquet, ou mise à jour avec la dernière version disponibl :

`apt-get install {{package}}`

- Suppression d'un paque :

`apt-get remove {{package}}`

- Suppression d'un paquet et de ses fichiers de configuratio :

`apt-get purge {{package}}`

- Mise à jour de tous les paquets installés vers les dernières versions disponible :

`apt-get upgrade`

- Nettoyage du dépôt local - supprime les fichiers de paquets (.deb) des téléchargements interrompus qui ne peuvent plus être téléchargé :

`apt-get autoclean`

- Suppression de tous les paquets qui ne sont plus nécessaire :

`apt-get autoremove`

- Mise à jour des paquets installés (comme la commande  `upgrade`), mais avec suppression des paquets obsolètes et installation des paquets supplémentaires pour répondre aux nouvelles dépendance :

`apt-get dist-upgrade`
