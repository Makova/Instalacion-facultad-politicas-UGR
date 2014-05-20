Respositorios non-free y backports Mozilla
==========================================

Instalar repositorios non-free y backports de Debian Wheezy para actualizar navegador Iceweasel
Abrir una terminal y editar el sources.list:

```
sudo nano /etc/apt/sources.list

```
Y pegar los siguientes repositorios:

```
deb http://ftp.es.debian.org/debian/ wheezy main contrib non-free
deb-src http://ftp.es.debian.org/debian/ wheezy main contrib non-free

deb http://security.debian.org/ wheezy/updates main contrib non-free
deb-src http://security.debian.org/ wheezy/updates main contrib non-free

# wheezy-updates, previously known as 'volatile'
deb http://ftp.es.debian.org/debian/ wheezy-updates main contrib non-free
deb http://mozilla.debian.net/ wheezy-backports iceweasel-release
deb-src http://mozilla.debian.net/ wheezy-backports iceweasel-release
deb-src http://ftp.es.debian.org/debian/ wheezy-updates main contrib non-free

```

Añadir llave Launchpad para repositorio Mozilla:

```
sudo apt-get install pkg-mozilla-archive-keyring

```

Actualizamos:

```
sudo apt-get update && sudo apt-get dist-upgrade

```
