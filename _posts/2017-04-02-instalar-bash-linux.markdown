---
layout: post
title: "Cómo tener Bash de Linux en Windows10"
date: 2017-04-02
excerpt: "Cuando se quieres aprender Bash desde Windows."
tags: [Linux, Bash, windows, instalacion]
comments: false
---

Antes de nada advertir que disponer de BAsh Linux en Windows10 no es lo mismo que
tener una distribución GNU/Linux corriendo en Windows. Por mucho que se diga
o se quiera hacer creer, dista mucho de la realidad.

Después de esto, comenzamos.

### Instalar Linux Bash para Windows 10

Lo primero es activar o unirse al programa *Insider Build* para tener acceso a funciones de pre-lanzamiento. Abrimos *Configuración de actualizaciones* y vamos a *Opciones Avanzadas*  Siguiendo las instrucciones no unimos al programa *Insider Build* . Se requiere que inicie sesión con la cuenta de Microsoft y reinciar el sistema.

Una vez reiniciado el sistema, volver a *Advanced Windows Update* y elegir la actualización de pre-lanzamiento y seleccionar la opción *Rápido o como yo, Aplazado*

<figure>
    <img src="{{site.url}}/assets/images/bash-windows10/Bash0.png">
</figure>
A continuación ir a Configuración del desarrollador y elegir Modo desarrollador.

<figure>
    <img src="{{site.url}}/assets/images/bash-windows10/Bash5.png">
</figure>

Una vez hecho esto, abra "activar y desactivar las características de Windows" y seleccione Subsistema de Windows para Linux (beta).

<figure>
    <img src="{{site.url}}/assets/images/bash-windows10/Bash1.png">
</figure>

Seguramente después del reinicio, en Windows es algo de lo mas normal, tener que reiniciar el sistema :D
Pues escribimos bash en la barra de búsqueda y nos aparecerá la terminal, como esta:

<figure>
	<img src="{{site.url}}/assets/images/bash-windows10/Bash3.png">
</figure>

* sólo tenemos que seguir las instrucciones para descargar e instalar todo lo necesario, ademśa de crear un usuario y contraseña.
Después de esto ya tendrá una terminal Bash de Ubuntu funcionado totalmente y ejecutar comandos como estos:

<figure>
	<img src="{{site.url}}/assets/images/bash-windows10/Bash4.png">
</figure>

Una vez realizado todos los pasos cada vez que abra `bash` desde el menú incio de Windows 10 estará disponible para ejecutar los comandos.

Lo próximo va a ser instalar básicamente una distribución que este soportada para poder funcionar dentro de Windows 10. Tendremos que descargar un archivo en compresión `.tar` en el directorio personal WSL y cambiar el `rootfs` actual con el elegido que hayamos descargado.
De esta manera al abrir `bash` podremos cambiar facilmente de una distribución a otra, ejecutando la distribución elegida en vez de Ubuntu.

* Vamos a ello.

### Instala un subsistema Windows para Linux Distribucion Switcher


