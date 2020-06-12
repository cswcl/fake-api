# Fake API

Ejercicio de programación para postular a [CSW Consultores Ambientales](https://csw.cl/)

Este repositorio contiene las instrucciones del ejercicio y los datos para realizarlo.

## Ejercicio

1. Programe un pequeño servidor web con Nodejs que exponga una página que muestre en un mapa los datos obtenidos de este repositorio.

Para el mapa se recomienda usar la biblioteca [Leaflet](https://leafletjs.com/), pero se puede usar otra si se prefiere.

Los datos se encuentran expuestos en este mismo repositorio via github pages:

  - [GeoJson](http://cswcl.github.io/fake-api/monumentos_historicos_extracto.geojson)
  - [CSV](http://cswcl.github.io/fake-api/monumentos_historicos_extracto.csv)

Los datos se deben obtener al momento de cargar la página mediante una petición a github.io, no se considerará válido si se cargan localmente.

Se deben correlacionar los datos del GeoJson con los del CSV mediante el `id` de manera que el mapa muestre el nombre de los monumentos.

2. Despliegue el servidor para que sea accesible vía web.

Es posible usar algún servicio gratuito como [Heroku](https://heroku.com/) o bien el que se prefiera.

3. Una vez desplegado el software, contactar a CSW via [GetOnBoard](https://www.getonbrd.cl/) para indicarnos:
  - enlace donde se encuentra desplegado el software
  - enlace al repositorio git de la solución (debe ser de acceso público)
