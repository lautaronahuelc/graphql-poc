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

client

https://github.com/graphql-by-example/job-board/commit/c3ec082d19b83e0734e7e37372afe02673a60c59#diff-31fc4989ae06728b65bd6601c18e115c0f5f4cd6471245716388c7984ffe85f8R19

https://github.com/graphql-by-example/job-board/commit/77c26835e978a6ccffee8c86e8141ccfae95a702#diff-10aa56eb9308731334a7125d59cc8433dd8c91a9838250da04c13087e2b58fd7R8

https://github.com/graphql-by-example/job-board/commit/a6ce562fd882a9ae5fe595ff313b8a67125f2e22

query arguments
query variables

Mutations

alice@facegle.io
alice123

como se definen en el schema
como se define en el resolver
mostrar ejemplo en apollo server
como pasar muchos parametros
https://github.com/graphql-by-example/job-board/commit/73fed9aedbb977adc57c739a56d388cfa26b5f1d
mutation en React
https://github.com/graphql-by-example/job-board/commit/5af87a31b91db9e537b5879a62262953737bbcb6

apollo client
graphql-request está bien para ayudarnos con algunas peticiones ligeras pero para ocaciones donde necesitemos más features, tenemos apollo client (por ejemplo el caching y useQuery hook para obtener el loading, error y data ya manejados)

