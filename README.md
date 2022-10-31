# Actividad-2.1
Implementación de un ADT de estructura de datos lineales 

Tec de Monterrey
Act 2.1 - Implementación en equipo de un ADT de estructura de datos lineales
¿Qué tengo que hacer?
En este repositorio encontrarás el archivo "list.h" que deberás modificar para el desarrollo de esta actividad. Deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:

// =========================================================
// File: list.h
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
Diseña e implementa, de forma forma individual, siguiendo la especificación de la interfaz para un ADT que represente una estructura de datos lineal:

Dependiendo del ADT de estructura de datos lineal deberán implementar las operaciones CRUD (Create, Read (buscar), Update, Delete) elementos en la estructura de datos. Algunas operaciones no aplican para ciertas estructura de datos.

insert_at (create)	Descripción	Agrega un elemento en *index* (0 <= *index* <= *size*). El elemento que estaba en esa posición se desplaza hacia la derecha.
Entrada	*val*, valor a ser insertado y la posición, *index*, en que se insertará.
Salida	Estructura de datos valida mostrando la inserción del elemento. Si la posición es inválida, deberá arrojar una excepción.
Precondición	Una estructura válida.
Postcondición	Estructura modificada.
get (read)	Descripción	Regresa el elemento que está en la posición indicada por *index* (0 <= *index* < *size*).
Entrada	La posición, *index*, del elemento requerido.
Salida	Elemento que se encuentra en la posición indicada. Si la posición es inválida, deberá arrojar una excepción.
Precondición	Una estructura válida.
Postcondición	Nada.

indexOf	Descripción	Regresa la posición en que se encuentra el elemento *val*.
Entrada	El elemento a buscar.
Salida	La posición del elemento buscado. Si el elemento no se encuentra, regresa -1.
Precondición	Estructura de datos válida
Postcondición	Nada
remove_at (del)	Descripción	Elimina el elemento que se encuentra en *index* (0 <= *index* < *size*).
Entrada	La posición, *index*, del elemento a eliminar.
Salida	Elemento que se encuentra en la posición indicada. Si la posición es inválida, deberá arrojar una excepción.
Precondición	Estructura de datos válida
Postcondición	Estructura de datos debidamente actualizada

Todas las funcionalidades deberán de estar correctamente alineadas y documentadas.  Recuerda que todas las funcionalidades deberán pasar exitosamente todas las pruebas. Como parte de la documentación deberá incluirse la complejidad de cada una de ellas.

Para probar tu implementación, ejecuta el comando:

make
Este comando compilará tu código y generará una serie de archivos de pruebas llamados "runTest#", donde # será un número de prueba. Para ejecutar prueba, solo deberás ejecutar el archivos correcto. Por ejemplo, si quiere revisar si mi código cumple con la prueba número 3, deberías ejecutar:

./runTest3
¿Bajo qué criterios se evalúa mi evidencia?
80% - Para cada una de las funcionalidades se evaluará:

Excelente (80%) - pasa correctamente todos los casos de prueba.
Muy Bien (60%) - pasa correctamente el 75% de los casos de prueba.
Bien (40%) - pasa correctamente el 50% de los casos de prueba.
Insuficiente (20%) - pasa correctamente menos del 50% de los casos de prueba.
10% - El código deberá seguir los lineamientos estipulados en el estándar de codificación: liga_estándar_codificación

10% - Se respetan los nombres de las funciones en la aplicación.

¿Dónde la entrego?
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (git push).
