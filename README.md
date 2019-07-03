# Workshop UX Design

## Installation de PlayOnLinux (consignes en cours)

1. Cliquez sur ce lien <https://www.playonlinux.com/fr/download.html>
2. "Version de développement" Clonez ce repôt :
```
git clone https://github.com/PlayOnLinux/POL-POM-4
```
3. En dessous, "Paquets"
   * cliquez sur **Ubuntu**
   * Choississez votre dépôt (en l'occurrence Xenial sinon tapez les commandes du dépôt correspond)
   Pour le dépôt **Xenial**, tapez les commandes suivantes :
```
wget -q "http://deb.playonlinux.com/public.gpg" -O- | sudo apt-key add -
sudo wget http://deb.playonlinux.com/playonlinux_xenial.list -O /etc/apt/sources.list.d/playonlinux.list
sudo apt-get update
sudo apt-get install playonlinux
```

Workshop réalisé par Cassandra Caestecker et encadré par BeCode Charleroi. Ce cours pratique a pour but d'initier les apprenants aux logiciels de créations, de retouche et de prototypage afin de leur faire découvrir l'importance du design dans le domaine du développement web.
