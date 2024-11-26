hello-world

Qué es GraphQL?
Lenguaje de consulta de APIs

Podría ser una alternativa a las APIs de REST, pero no viene a reemplazarlas porque depende el contexto una puede ser major opcion que otra, incluso podrían complementarse.

Diferencias?
Uno utiliza métodos para identificar la acción, url para identificar el recurso y paremtros para modificar el recurso existente
Otro utilza queries para obtener datos de solo lectura, mutaciones para modificar recursos, subcripciones para recibir actualizaciones de datos basada en eventos

En la arquitectura REST se devuelve siempre el recurso completo
En GraphQL se devuelve el recurso especificado

Exponer la api a través de http:
para hacer eso usamos una libreria llamada apollo server que es una forma popular de implementar graphql con js
instalamos  graphql -> core functionality
            @apollo/server -> expose api a través de http
startStandaloneServer para iniciar el servidor de apollo sin otro framework de backend.

Mostrar esquema (representa la interfaz de la api, la forma que va a tener, lo que el cliente puede pedir)
Mostrar resolvers (resuelve el valor de las queries)
Levantar GraphQL con Apllo Server

Mostrar Sandbox (para realizar queries, ver documentacion)
query sencilla,
estructura respuesta,
segerencias
query nomenclatura

Graphql sobre HTTP
mostrar peticiones, son POST

---------------------------------------------------

job-board

saltar la parte de backend.
mostrar cómo graphql trabaja interiormente para otorgar los datos solicitados (crear diapositivas)