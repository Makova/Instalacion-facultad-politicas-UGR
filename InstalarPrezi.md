Instalación
===========

**1-** Descargar `Adobe Air` la versión [Adobe AIR 2.6 runtime downloads](http://airdownload.adobe.com/air/lin/download/2.6/AdobeAIRInstaller.bin) y su `SDK` 

Dentro de la carpeta `opt`  crear la carpeta `airapps` el SDK se descomprimí y se pega en `/opt` también, renombrando la carpeta como `adobe-air-sdk`.  Cabe recordar que todo esto debe hacerse como root.

**2-** Descargar el archivo [Air de Prezi Desktop](http://www.mediafire.com/download/2e4v9hw3hv3qgz9/PreziDesktop_3.042.air)
**3-** Una vez descargado, lo debes descomprimir y copiarlo todo en `/opt/airapps/prezi-desktop` quizás debas crear la carpeta `prezi-desktop`.

**4-** Luego para ejecutarlo puedes crear un lanzador, copiando el siguienmte comando:

```
/opt/adobe-air-sdk/bin/adl -nodebug /opt/airapps/prezi-desktop/META-INF/AIR/application.xml /opt/airapps/prezi-desktop

```
