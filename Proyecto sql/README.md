# Proyecto : Analisis Libros sql.

## Objetivos del proyecto

Se tiene una base de datos de uno de los servicios que compiten en este mercado. Contiene datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros. Esta información se utilizará para generar una propuesta de valor para un nuevo producto.

## Descripción de los datos

Descripción de los datos
books:

Contiene datos sobre libros:

- book_id — identificación del libro
- author_id — identificación del autor o autora
- title — título
- num_pages — número de páginas
- publication_date — fecha de la publicación
- publisher_id — identificación de la editorial

authors:

Contiene datos sobre autores:

- author_id — identificación del autor o autora
- author — el autor o la autora

publishers:

Contiene datos sobre editoriales:

- publisher_id — identificación de la editorial
- publisher — la editorial

ratings:

Contiene datos sobre las calificaciones de usuarios:

- rating_id — identificación de la calificación
- book_id — identificación del libro
- username — el nombre del usuario que revisó el libro
- rating — calificación

reviews:

Contiene datos sobre las reseñas de los y las clientes:

- review_id — identificación de la reseña
- book_id — identificación del libro
- username — el nombre del usuario que revisó el libro
- text — el texto de la reseña

- review_id — identificación de la reseña
- book_id — identificación del libro
- username — el nombre del usuario que revisó el libro
- text — el texto de la reseña
