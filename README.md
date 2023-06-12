# Proyecto de Base de Datos de Películas

Este proyecto consiste en el diseño y modelado de una base de datos para almacenar información relacionada con películas. El objetivo principal es proporcionar una estructura eficiente y organizada para gestionar los datos de películas, directores, productores, escritores, géneros y elenco principal.

## Estructura de la Base de Datos

La base de datos se ha modelado utilizando el enfoque de Modelo Entidad-Relación. A continuación, se describen las principales entidades y relaciones presentes en el diseño:

- **Tabla "movie"**: Esta tabla contiene información detallada sobre las 50 mejores películas. Cada película se identifica de manera única y se almacenan atributos como título, año de lanzamiento, duración, sinopsis, entre otros.

- **Tabla "director"**: Almacena información sobre los directores de las películas. Un director puede dirigir múltiples películas, pero cada película tiene un único director principal.

- **Tabla "productor"**: Contiene información acerca de los productores generales de las películas. Un productor puede estar asociado con múltiples películas, pero cada película tiene un único productor principal.

- **Tabla "escritor"**: Registra datos sobre los escritores de las películas. Un escritor puede escribir varias películas, pero cada película tiene un único escritor principal.

- **Tabla "género"**: Almacena los géneros a los que pertenecen las películas. Una película puede tener múltiples géneros, y un género puede estar asociado con varias películas.

- **Tabla "cast"**: Registra el elenco principal de cada película. Cada grupo de cast corresponde a una única película, y cada película tiene un único grupo de cast distinto.

## Uso de la Base de Datos

Para utilizar esta base de datos, se proporcionarán instrucciones detalladas sobre cómo importar el esquema y cargar los datos iniciales. Además, se ofrecerán consultas de ejemplo que permitirán realizar diversas operaciones, como buscar películas por género, obtener información del director o productor de una película específica, y consultar el elenco principal de una película.

## Contribuciones

Las contribuciones a este proyecto son bienvenidas. Si desea contribuir, siga los siguientes pasos:

1. Realice un fork del repositorio.
2. Cree una rama nueva para trabajar en su mejora o corrección.
3. Implemente los cambios y realice las pruebas necesarias.
4. Envíe una solicitud de extracción con una descripción clara de los cambios realizados.

## Contacto

Si tiene alguna pregunta o sugerencia relacionada con este proyecto, no dude en ponerse en contacto conmigo a través de la sección de problemas (Issues) del repositorio.

¡Gracias por su interés en este proyecto! Esperamos que sea de utilidad para entender el modelo relacional de base de datos SQL.
