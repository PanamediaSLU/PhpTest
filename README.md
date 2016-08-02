# Php developer test
Prueba para los developers PHP que quieren unirse al equipo.

## Introducción
Hola! Esto es un pequeño test para ayudarnos a saber lo bien que piensas como developer.

## Como empezar

Te hemos preparado un máquina vagrant, por lo tanto necesitas tener vagrant instalado.

Haz un clone del proyecto, ejecuta vagrant up y listo, preocúpate de la prueba.

Para ejecutar los tests, haz un ssh a la máquina vagrant, cd /vagrant, y ./test.sh NombreDelTest

## Que hay que hacer

Necesitamos comprobar el país de origen de un usuario, si éste proviene de Alemania, lo redirigimos a una url(no importa el destino).

Hay muchas apis disponibles en interneºt de geolocalización de ips, utiliza composer para cargar la dependencia.

Tienes que tener en cuenta que hoy utilizamos una api, pero mañana podemos utilizar otra. Por lo tanto, el código ha de estar preparado para estos cambios.
Puedes introducir cualquier patrón de diseño que necesites, value objects, y por favor, crea los tests necesarios para que cubran todo el proceso.

Tómate el tiempo necesario para realizar la prueba, no hay prisa, lo queremos hacer bien.

## Dudas

Puedes abrir una issue en este repositorio.

## Como enviar tu solución

Haz un pull request al repositorio.