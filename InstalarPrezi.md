Instalación
===========

**1-** 
Descargar `Adobe Air` 
La versión [Adobe AIR 2.6 runtime downloads](http://airdownload.adobe.com/air/lin/download/2.6/AdobeAIRInstaller.bin) es un archivo con extensión .bin de unos (15.4 MB).


**2-** 
Instalar `Adobe Air` 
Ejecuta el siguiente comando para cambiar el permiso en el archivo para que sea ejecutable:

> sudo chmod +x AdobeAIRInstaller.bin```

Ahora con el siguiente comando vamos a instalar el Adobe Air:

> sudo ./AdobeAIRInstaller.bin```

**2.1-** 
(Opcional) Si tienes problemas con Adobe Air es porque falta `gnome-keyring`, ejecuta los siguientes comandos para solucionarlo, y después vuelve a ejecutar el instalador de AdobeAir:

**Para 32 bits**

> sudo ln -s /usr/lib/i386-linux-gnu/libgnome-keyring.so.0 /usr/lib/libgnome-keyring.so.0```

> sudo ln -s /usr/lib/i386-linux-gnu/libgnome-keyring.so.0.2.0 /usr/lib/libgnome-keyring.so.0.2.0```

**Para 64 bits**

> sudo ln -s /usr/lib/x86_64-linux-gnu/libgnome-keyring.so.0 /usr/lib/libgnome-keyring.so.0```

> sudo ln -s /usr/lib/x86_64-linux-gnu/libgnome-keyring.so.0.2.0 /usr/lib/libgnome-keyring.so.0.2.0```

**3-**
Descargar la versión Prezi Desktop desde el siguiente enlace:

[Prezi-desktop](http://www.mediafire.com/?2e4v9hw3hv3qgz9)

**4-**
Instalar Prezi. 
Damos click derecho sobre el archivo descargado. Damos click izquierdo en la opción `Abrir con Adobe AIR Application Installer`. A continuación se abrirá una ventana preguntadonos si queremos instalar la aplicación, damos click izquierdo en botón ´Aceptar`. Seguimos las instrucciones del resto de las ventanas y damos click en Aceptar cuando lo requiera. Nos pedirá nuestra clave de **Root**, la introducimos para seguir con la instalación.


**5-**
Activar Prezi. 
Al finalizar la instalación requerirá un correo electrónico y un password que previamente se "habrá" creado en la página de Prezi.com. Escribe el correo y el password de tu cuenta en Prezi.com. Si no tienes una cuenta de Prezi puedes crearla desde el siguiente enlace: 
[Crear cuenta Prezi](https://prezi.com/profile/registration/?license_type=PUBLI). 
El registro es para una cuenta pública, todos los trabajos prezi que realices serán públicos.
Espera un momento que se active la aplicación. Listo, ahora puedes usar Prezi desde tu sistema Linux, y sin la necesidad de trabajar conectado a Internet.



Referencias de los siguientes enlaces:

[1](http://drunkensapo.blogspot.mx/2012/07/install-prezi-desktop-on-linux-ubuntu.html)

[2](http://cbta16-computacion.blogspot.com.es/2012/07/como-instalar-prezi-desktop-en-linux.html)

