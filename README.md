Gracias por visulizar mi codigo, en esta oportunidad les presento codigo de LiteAlura un proyecto acaademico de la plataforma Alura Latam,
que se las recomiendo, proyecto desarrollado en Java que permite buscar libros, listar libros y autores.

en el contenido tendremos una interfas de consolo que nos mostrara la siguiente informaciones:

-Menu que nos permitira realizar ciertas consultas, como por ejemplo:

*Título de libros.
*Autores: Muestra todos los autores que han sido registrados en la base de datos.

-Requisitos
 *Java 17.
 *Spring Boot 3.2.4.
 *PostgreSQL.
 *Maven.

Ejecuta la aplicación:

./mvnw spring-boot:run
Uso
Buscar un libro:
Ejecuta la aplicación y selecciona la opción 1.
Ingresa el título del libro que deseas buscar.
Busqueda de libro por ttulo

Listar libros:
Selecciona la opción 2 para listar todos los libros registrados.
Lista libros cargados

Listar autores:
Selecciona la opción 3 para listar todos los autores registrados.
Lista autores cargados

Listar autores vivos en un determinado año:
Selecciona la opción 4 y especifica el año.
Lista autores por ao

Top 10 libros más descargados:

Selecciona la opción 6 para ver los 10 libros más descargados.
Libro más descargado y menos descargado:

Selecciona la opción 7 para ver el libro más descargado y el menos descargado.
Libro ms y menos descargado

Descripción de las Funcionalidades
1. Buscar libro por título
La persona usuaria debe ingresar el nombre del libro que desea buscar. Por ejemplo, si se busca "Pride" (Orgullo), la aplicación debe ir a la API de Gutendex, buscar la información sobre este libro y registrarlo en la base de datos. Si el libro ya está en la base de datos, no se insertará nuevamente.

2. Listar libros registrados
Muestra todos los libros que han sido registrados en la base de datos. Por ejemplo, libros como "Don Quixote" (Don Quijote), "Emma", "Pride and Prejudice" (Orgullo y Prejuicio), entre otros.

3. Listar autores registrados
Muestra todos los autores que han sido registrados en la base de datos. Por ejemplo, autores como Jane Austen y William Shakespeare.

4. Listar autores vivos en un determinado año
Permite listar los autores que estaban vivos en un año específico. Por ejemplo, en el año 1600, autores como Cervantes y Shakespeare estaban vivos.

5. Listar libros por idioma
Permite listar los libros por su idioma (ES, EN, FR, PT). Por ejemplo, si se busca por ES, se mostrarán los libros en español.

Opciones de idioma

6. Top 10 libros más descargados
Muestra los 10 libros más descargados de la base de datos.

7. Libro más descargado y menos descargado
Muestra el libro más descargado y el menos descargado de la base de datos.

API
La aplicación utiliza la API de Gutendex para obtener información sobre los libros. Más información sobre la API está disponible en Gutendex API.

Contribución
Si tienes ideas adicionales o mejoras, no dudes en contactarme. La creatividad es esencial para el desarrollo de software.
