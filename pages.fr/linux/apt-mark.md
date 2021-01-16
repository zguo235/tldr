# apt-mark

> Utilitaire permettant de modifier l'état des paquets installés.

- Marquer un paquet comme étant automatiquement install :

`sudo apt-mark auto {{package_name}}`

- Maintenir un paquet à sa version actuelle et empêcher les mises à jou :

`sudo apt-mark hold {{package_name}}`

- Permettre une nouvelle mise à jour d'un paque :

`sudo apt-mark unhold {{package_name}}`

- Afficher les paquets installés manuellemen :

`apt-mark showmanual`

- Afficher les paquets détenus qui ne sont pas mis à jou :

`apt-mark showhold`
