# Actividad-Practica-I---Bases-de-Datos-

-- Diseño de Consultas avanzadas SQL 

Esta actividad tiene como objetivo el diseño y la implementación de consultas SQL avanzadas a partir de un modelo relacional correspondiente a una base de datos de biblioteca. Inicialmente, se trabajó con un esquema de base de datos que incluye entidades como usuarios, libros, préstamos, reservas y categorías. A partir de esta estructura, se desarrollaron diferentes tipos de consultas que abarcan el uso de subconsultas, operadores de conjunto, expresiones condicionales, funciones de agregación, así como distintas formas de combinación de tablas mediante JOIN (INNER, LEFT y RIGHT).

Las subconsultas permitieron obtener información específica a partir de condiciones anidadas, mientras que los operadores de conjunto facilitaron la comparación entre distintos conjuntos de datos, como los libros reservados frente a los prestados. Por su parte, las expresiones condicionales se utilizaron para clasificar información, como el estado de disponibilidad de los libros o la actividad de los usuarios.

Asimismo, se implementaron consultas con funciones de agregación junto con las cláusulas GROUP BY y HAVING, lo cual permitió realizar análisis sobre los datos, como identificar categorías con mayor cantidad de libros o usuarios con múltiples reservas. El uso de JOINs fue fundamental para relacionar las distintas tablas y obtener información más completa y significativa.

Adicionalmente, se emplearon funciones especializadas para el manejo de cadenas de texto y funciones de fecha para calcular intervalos de tiempo, así como para identificar préstamos pendientes de devolución. Todo este proceso se llevó a cabo utilizando un gestor de base de datos, en este caso pgAdmin 4 con PostgreSQL, lo que permitió ejecutar y validar cada una de las consultas desarrolladas.

Durante el desarrollo del presente trabajo, fue necesario realizar pequeños ajustes al código SQL suministrado inicialmente por la universidad. Estas modificaciones se llevaron a cabo con el propósito de garantizar la correcta ejecución de las consultas dentro del entorno de pruebas utilizado, el cual fue pgAdmin 4 con el sistema de gestión de bases de datos PostgreSQL.

Dado que el script original estaba orientado a otro motor de base de datos, como MySQL, se identificaron algunas diferencias en la sintaxis que requerían adaptación. Entre estos cambios se incluyó el uso de funciones específicas para el manejo de fechas, la concatenación de cadenas y la implementación de ciertos operadores propios de PostgreSQL.

Es importante resaltar que dichas modificaciones no alteran la lógica ni la finalidad de las consultas planteadas, sino que corresponden únicamente a ajustes técnicos necesarios para asegurar la compatibilidad con el gestor de base de datos utilizado. De esta manera, se logró ejecutar correctamente todas las consultas, validando su funcionamiento y obteniendo los resultados esperados.

La adaptación del código permitió no solo cumplir con los requerimientos del ejercicio, sino también comprender las diferencias existentes entre distintos sistemas gestores de bases de datos, fortaleciendo así el aprendizaje práctico en el uso del lenguaje SQL en diversos entornos.

> Camila Andrea Oquendo Quintero
