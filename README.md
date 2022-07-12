# MODELADO

## INTRODUCCIÓN

Este repositorio desarrolla el laboratorio del módulo 1 del Bootcamp Backend - Modelado. En el que se va a modelar la base de datos de un portal en el que se exponen videos técnicos, categorizado por temática, autor.

## OBJETIVOS

<ol>
  <li>Realizar los diagramas del modelo de datos.
  <li>Realizar el Markdown con la explicaciónde por qué se ha realizado dicho modelado, patrones aplicados y razón.
  <li>Backup de una base de datos con datos de ejemplo.
</ol>

## SITEMAP DE LA APP

<img src="./images/sitemap.png">

## ENUNCIADO

A tener en cuenta:

<ol>
<li>Va a ser un portal orientado al mundo de la programación.
<li>El portal va a estar compuesto por cursos, cada curso está compuesto a su vez por un número de videos y artículos que lo acompañen.
<li>La página de cursos debe mostrar la lista de autores que lo hicieron.
<li>La página de un video debe mostrar el autor que lo realizó.
<li>Los videos y el contenido de cada artículo se almacenan en un storage S3 y en un headless CMS, en la base de datos sólo almacenaremos los Id's a esos recursos.
<li>Los videos se pueden clasificar por temáticas (Devops / Front End / Back End / ...)
<li>Los videos tienen autores (ponemos la restricción, un video tiene un autor), un curso puede tener varios autores.
<li>En principio los vídeos no se van a compartir entre diferentes cursos (aunque sería una amplicacíon interesante del ejercicio.
<li>Hay una opción para ver la página con la biografía del autor, esta página no va a ser muy visitada.
</ol>
