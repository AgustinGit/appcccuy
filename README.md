# appcccuy
Mobile App CCcUY

Pre-requisitos:

Instalar GIT: https://git-scm.com/
Instalar NODE: https://nodejs.org/es/

Documentacion:

Arrancando con el ambiente de desarrollo: 

Paso 1:

 Bajar directorio de trabajo: ubicarnos a la altura del directorio que desemos para guardar el proyecto (en mi caso: /home/asilva/GIT/ )ejecutar en consola, -si se trabaja desde windows con GIT es la consola que viene con instalacion de GIT (mini bash)-

Comando: "git clone https://github.com/AgustinGit/appcccuy.git"

Esto nos baja el directorio del proyecto con las configuraciones del proyecto GIT.

Nota: para conocer en que rama del versionado estamos parados ejecutar dentro de dicha carpeta el comando: "git status"

Paso 2:

Contexto; Ionic y Meteor:

El proyecto base que tomamos dice ser un proyecto "clon" de WhatsApp, utilizando tecnologias como Angular, Ionic Framework (Cliente) y Meteor (Backend). Probablemente hallan varias cosas desarrolladas que no vamos a utilizar y probablemente recortemos.

a-Configurando Ionic-Cordova

Luego de instalar Node podremos ejecutar el comando para instalar ionic y cordova:

npm install -g ionic cordova

Cordova (https://cordova.apache.org/) es una coleccion de librerias que permiten a las app hibridas hechas con Ionic iteractuar con plataformas nativas como IOS, Android, Windows Phone, etc.. en criollo: es lo que vincula la función "javascript" con el código nativo
de "hacer una cosa" en cada plataforma, por ejemplo sacar una foto, obtener geo-referencia, etc. (https://cordova.apache.org/docs/en/latest/guide/support/index.html)

Errores conocidos:

Cualquier error de node que diga algo asi como "npm ERR! Error: EACCES: permission denied" se debe a que necesita permisos de administrador porque probablemente mueva archivos o cree archivos, en el caso de linux o mac debemos correr el comando con sudo, windows bastara con abrir la consola en modo administrador y volver a correr el comando.

b-Crear proyecto Ionic, nuestro proyecto ya tiene 

ionic start cccuyapp --v2

