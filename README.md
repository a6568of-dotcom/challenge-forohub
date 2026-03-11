# ForoHub

ForoHub es una API REST desarrollada con Spring Boot para la gestión de tópicos de un foro. Permite consultar, registrar, actualizar y eliminar tópicos, además de implementar persistencia de datos y seguridad.

## Funcionalidades

- Mostrar todos los tópicos
- Mostrar un tópico específico
- Registrar un nuevo tópico
- Actualizar un tópico
- Eliminar un tópico

## Tecnologías utilizadas

- Java 17
- Spring Boot 3
- Spring Web
- Spring Data JPA
- Spring Security
- Validation
- Lombok
- H2 Database
- Maven

## Estructura de la base de datos

La tabla principal utilizada en este proyecto es:

- `topicos`
  - `id`
  - `titulo`
  - `mensaje`
  - `fecha_creacion`
  - `status`
  - `autor`
  - `curso`

## Endpoints

### Listar tópicos
`GET /topicos`

### Detallar un tópico
`GET /topicos/{id}`

### Registrar un tópico
`POST /topicos`

### Actualizar un tópico
`PUT /topicos/{id}`

### Eliminar un tópico
`DELETE /topicos/{id}`

## Pruebas

Las pruebas de la API se realizaron en entorno local con navegador y consola H2.

## Estado del proyecto

En desarrollo.