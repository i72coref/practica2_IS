# Introducir datos

**ID:** *03*

**Breve descripción:**En cualquier momento el usuario puede introducir nuevos alumnos.

**Actores principales:** Usuario (Profesor).

**Actores Secundarios:** Alumnos.

**Precondiciones:**
Cuando se introduce un alumno se deben introducir del alumno obligatoriamente el DNI, Nombre, Teléfono, E-mail corporativo, dirección, curso mas alto de matriculación, y de forma opcional el equipo y el líder, pudiendo dejar el campo en blanco.

**Flujo principal:**

1. Se pregunta cuantos alumnos de desea introducir
2. El programa pide el DNI, nombre,...,del alumno.
3. Si se ha llegado al número de alumnos que se desea introducir se sale al menú, sino se introduce otro alumno.

**Postcondiciones:**
Al finalizar se muestra un mensaje con el número de alumnos en el sistema.

**Flujos alternativos:**

* Si se deja en blanco algún campo obligatorio se muestra un error y se pide de nuevo el dato
* Si se desea introducir mas de 150 alumnos en total o ningún alumno se muestra un error, y se pide de nuevo el número de alumnos que se desea introducir.