*Lo que aprendí sobre Backend Development*

Lo primero que me aclaró el video fue lo del lenguaje: hay mil opciones (Java, C#, Python, Go, PHP...) pero lo que realmente importa es tener bien sólidos los fundamentos, o sea variables, funciones, objetos y clases. Sin eso, cualquier lenguaje que elijas va a ser difícil. Otro tema que me pareció clave y que no se puede ignorar es el protocolo HTTP, porque es literalmente la base de cómo funciona la web: métodos, códigos de estado, cookies, todo eso.

Después entendí por qué existen los frameworks: básicamente para no estar reinventando la rueda cada vez. Algunos como Express o Flask te dan libertad total, y otros como Django o Laravel ya vienen con una estructura definida. En cuanto a cómo diseñar APIs, lo más común sigue siendo REST con JSON, pero también existen GraphQL, gRPC y WebSockets dependiendo de lo que necesites, por ejemplo si quieres algo en tiempo real como un chat.

En la parte de datos, me quedé con que SQL es indispensable, y en especial PostgreSQL porque es muy usado y es open source. También vi que los ORMs son útiles para hacer consultas sin escribir SQL puro todo el tiempo. Y para casos donde los datos son más flexibles, NoSQL con MongoDB es una buena opción.

Algo que me pareció muy importante fue el tema de calidad y seguridad. El testing es fundamental para no romper lo que ya funciona cuando haces cambios. Y para seguridad, dos cosas concretas: estudiar el OWASP Top 10 para conocer los ataques más comunes, y usar JWT para manejar la autenticación de usuarios.

Para el despliegue, si estás empezando puedes usar Render o Railway que son más sencillos, y cuando ya tengas más experiencia saltar a AWS o Google Cloud. Lo que sí me dejó claro el video es que Docker hay que aprenderlo sí o sí, porque te permite meter tu código en contenedores y que funcione igual en cualquier entorno.

Y para cuando quiera ir a un nivel más avanzado, el video menciona microservicios, colas de mensajes con RabbitMQ o Kafka, y funciones serverless.

Mi conclusión personal: no hay que intentar aprender todo esto al mismo tiempo. Lo mejor es elegir un framework, ponerse a construir cosas reales, y de ahí ir incorporando herramientas según lo vaya necesitando el proyecto.