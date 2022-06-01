# Evaluación técnica Frontend para Web developers

Bienvenid@ a la prueba técnica que hemos diseñado para los postulantes al cargo de desarrollador frontend web.

#### Importante: ####
*Una vez desarrollada la prueba por favor subir tu código a un repositorio remoto (Github, Gitlab, Bitbucket, etc), y enviarnos el enlace al correo jsalazar@links.com.ec donde deben incluirse todas las instrucciones para que podamos ejecutar tu trabajo de manera local y hacer las respectivas revisiones.*

#### Requerimientos técnicos: ####
**El sitio debe estar desarrollado en React V17 o superior con Redux 4.0.5, TypeScript**

En caso de preguntas dirigete a: *jsalazar@links.com.ec*, usando el asunto [Frontend-Web-Test]

Buena suerte!

#### Enunciado

Un viajero desea recorrer países de Sudamérica brincando de frontera en frontera, para esto el viajero que viaja en carro tiene disponible la información que devuelve el servicio REST siguiente:
https://restcountries.com/v2/regionalbloc/usan, cuyo servicio devuelve información valiosa de todos los países de Sudamérica, incluyendo los países con los que tiene frontera cada país.

La aplicación web al iniciarse deberá visualizar una lista con los nombres de todos los países de la región según el servicio REST consultado. Cuando el viajero de clic en el nombre de cualquiera de los países en la lista se debe mostrar en un área al costado de la lista datos del país clickeado o seleccionado: nombre del país, población, código telefónico, área que ocupa y el nombre de todos los países con los que hace frontera, estos nombres de los países con los que tiene frontera deben ser clickeables.

Cuando el viajero de clic en alguno de los países que hace frontera entonces en el lista inicial de nombres de países debe quedar elegido el nuevo país seleccionado y se debe mostrar entonces la misma información pero del nuevo país seleccionado. De esta forma dando clic en los países que hacen frontera el viajero podrá brincar de país en país.

Ruta: el viajero desea que al brincar de país en país se actualice la información de la ruta que va siguiendo, por ejemplo: si el viajero brinca de Colombia a Ecuador la ruta debería indicar Colombia/Ecuador y si de Ecuador el viajero brinca a Perú entonces la ruta debe quedar así Colombia/Ecuador/Perú y así sucesivamente ir actualizando la ruta con cada brinco de país que realice.

Área recorrida: Similar a lo que ocurre con la ruta se debe visualizar el área recorrida, el área recorrida es la suma de las áreas de los países por los que va pasando el viajero y se debe ir actualizando con cada salto de un país hacia otro.

Usted dispone de 04:00h para llevar a cabo esta prueba. Tiene total libertad para realizar búsquedas en Google de ser necesario.

#### Consideraciones
Se evaluará la escritura de un código limpio, reutilizable, manejo de errores, buen manejo de la librería en conjunto con Redux, además del funcionamiento del sitio.
