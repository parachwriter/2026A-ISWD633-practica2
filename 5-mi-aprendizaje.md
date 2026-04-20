#### Antes de esta práctica tenía una idea más teórica de Docker, principalmente sabía crear contenedores pero no entendía bien cómo se conectaban entre sí ni cómo se configuraban de forma correcta.

#### Después de realizar la práctica entendí mejor:
- cómo usar variables de entorno para configurar servicios reales (mysql, wordpress)
- cómo funcionan las redes y por qué son necesarias para que los contenedores se comuniquen
- la importancia de separar servicios (base de datos y aplicación)
- el concepto de persistencia de datos (muy importante en entornos reales)

#### En cuanto a problemas, no tuve errores críticos, pero sí me ayudó a entender mejor que:
- si no se configuran bien las variables, los contenedores no se conectan
- los puertos pueden causar conflictos si ya están en uso

---

#### Docker Secrets (datos confidenciales)
------------------------------------
##### Docker Secrets sirve para manejar información sensible como:
- contraseñas
- tokens
- claves API

##### A diferencia de las variables de entorno, los secrets:
- no quedan visibles fácilmente
- se almacenan de forma segura dentro de Docker
- solo los servicios autorizados pueden acceder

se usan principalmente en Docker Swarm
