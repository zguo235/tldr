# apt-file

> Recherche de fichiers dans les paquets apt, y compris ceux qui ne sont pas encore installés.

- Mise à jour la base de données des métadonnée :

`sudo apt update`

- Recherche des paquets qui contiennent le fichier ou le chemin d'accès spécifi :

`apt-file search {{part/of/filename}}`

- Énumère le contenu d'un paquet spécifiqu :

`apt-file list {{package_name}}`
