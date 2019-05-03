# Nichoir
Nichoir à mésange connecté

Voici le projet réalisé au lycée Blaise Pascal de Clermont Ferrand, avec la participation de différents groupes d'élèves de Sciences de l'Ingénieur.


## Préparer le Raspberry
### Installer Raspbian
http://info.blaisepascal.fr/rpi-installation-de-raspbian

### Installer un serveur Web
http://info.blaisepascal.fr/rpi-installer-un-serveur-web

A ce stade la structure du dossier du site doit être de la forme :
`nichoir/
  static/
  template/
  nichoir.wsgi
`
### Télécharger les modules de graphiques
https://www.rgraph.net/
http://dygraphs.com/

Placer les contenus des téléchargements dans deux sous dossiers de `static/` nommés `dygraphs/` et `RGraph/`.
