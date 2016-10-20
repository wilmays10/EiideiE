# EiideiE
página para mostrar contenidos desarrollados por el Equipo Interdisciplinario e Interinstitucional de Innovaciones Educativas.

Para comenzar a usar el sistema, crearemos un entorno virtual. Seguir los siguientes pasos:

$sudo pip install virtualenvwrapper

Luego de instalado el paquete, creamos un directorio para los entornos virtuales:

$cd ~
$mkdir envs

Después, en nuestro ~/.bashrc ponemos:
export WORKON_HOME=~/envs/
source /usr/local/bin/virtualenvwrapper.sh

Estamos en condiciones de crear el entorno virtual:

$mkvirtualenv EIIIE

En cualquier momento que quiera salir del entorno, simplemente

$deactivate
