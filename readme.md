# COMANDO GIT 

Configura el nombre de usuario GIT
$ git config --global user.name "MarcoJanampa"

VERIFICAR USURIO GIT
$ git config --global user.name
MarcoJanampa

CONFIGURA CORREO GIT
$ git config --global user.email "marcojan163@gmail.com"
VALIDAR CORREO GIT
$ git config --global user.email
marcojan163@gmail.com

1. git init    : inicializa git en nuestro proyeccto. se ejecuta una vez en el proyecto
2. git status   : situacion del proceso de git
3. git add .    : envía los cambios de working directori a stagin area
4. git commit -m "Mi Primer Cambio"     : pasa los cambios de stagin are hacia repository 
5. git log      : te muestra todos los commits


archivo .gitignore : se listan los archivos queno se enviarán al repositor git


# BRANCH
1. Main (produccion) : el ambiente para los clientes
2. desarrollo (dev)  : hambiente de desarrollo
3. QA (Calidad de Servicio) : se pureba el desarrollo
4. UAT (Pre Produccion)     : antes de mandar a produccion

1 (desarrollo) => 2(QA) => 3(UAT)  => UAT (PRODUCCION)
