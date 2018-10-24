# Modificar_Alumno

**ID:** *06*

**Breve descripción:**
El sistema permite la modificación de los datos del alumno.

**Actores principales:** Usuario.

**Actores Secundarios:** Alumnos.

**Precondiciones:**

1. Debe existir al menos un alumno cargado en el sistema para poder modificarlo.

2. Para acceder a esta opción el usuario debe introducir el número correspondiente a la opción *modificar* que aparezca en el menú.

3. Es necesario hacer una búqueda previa del alumno a modificar.

**Flujo principal:**

1. El caso de uso comienza cuando el usuario introduce la opción indicada en el menú que le permite modificar los datos del alumno.

2. El sistema debe permitir modificar o no cada campo del alumno.

**Postcondiciones:**

* El sistema muestra los datos del alumno por pantalla.
* El sistema debe permitir con una opción de Si o No en cada campo modificar o no los datos del alumno.

**Flujos alternativos:**

1.a En caso de no existir un alumno cargado, el sistema debe mandar un mensaje indicando que no hay cargado ningún dato.

2.a Si introduce un número fuera del rango establecido para seleccionar, debe aparecer un mensaje de error y se debe permitir volver a introducir un número.
