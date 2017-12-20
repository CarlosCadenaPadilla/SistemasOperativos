# SistemasOperativos
Panel de Monitoreo de Intel Galileo
===================

Este proyecto consiste en graficar los procesos del sistema de tarjeta Intel Galileo basado en Node.js que permite verificar la temperatura, el estado de la memoria (libre, en caché, en búfer, total ...), la carga de la CPU y las tareas principales con su PID.

Esta es una aplicación web muy útil para verificar el estado no solo de un Intel Galileo sino también de una computadora con Linux.


# PANTALLAZO
![Monitoring Panel](http://i1.wp.com/geekytheory.com/wp-content/uploads/2013/12/panel-monitorizacion-raspberry-pi-node-js.png "Raspberry Pi Monitoring Panel")

# COMO INSTALARLO

**PASO 1:**
~~~
$ apt-get update && sudo apt-get upgrade
~~~
**PASO 2:**
~~~
$ apt-get install nodejs npm git
~~~
**PASO 3:**
~~~
$ git clone https://github.com/CarlosCadenaPadilla/SistemasOperativos.git
~~~
**PASO 4:**
~~~
$ cd SistemasOperativos
~~~
**PASO 5:**
~~~
$ npm install
~~~
Si todo esta bien, ir al paso 6. Si muestra algun error se debe realizar lo siguiente:
~~~
npm config set registry http://registry.npmjs.org/
~~~
~~~
npm install
~~~
**PASO 6:**
~~~
$ nodejs server.js
~~~
**PASO 7:**

Ejecute un navegador de internet en la Intel Galileo y inicielo escuchando en el puerto 8000. por ejemplo: [http://192.168.1.100:8000](http://192.168.1.100:8000)



