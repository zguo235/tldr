# apt-cache

> Outil de recherche de paquets Debian et Ubuntu.

- Recherche un paquet dans vos sources actuelle :

`apt-cache search {{query}}`

- Affiche des informations sur un paque :

`apt-cache show {{package}}`

- Indique si un paquet est installé et à jou :

`apt-cache policy {{package}}`

- Affiche les dépendances d'un paque :

`apt-cache depends {{package}}`

- Affiche les paquets qui dépendent d'un paquet particulie :

`apt-cache rdepends {{package}}`
