# Mostrar_Alumno

**ID:** *05*

**Breve descripción:** El usuario podrá mostrar uno o varios alumnos.

**Actores principales:** Usuario (Profesor).

**Actores Secundarios:** Alumnos.

**Precondiciones:**

 1. El usuario / usuarios a mostrar ya tiene que estar añadidos al sistema.
 2. Se debe pulsar la tecla indicada en el menú para acceder a *Mostrar_Alumno*

**Flujo principal:**

 1. El caso de uso empieza cuando se accede en el menú a la opción: *Mostrar_Alumno*.
 2. Nos dará la opción de mostrar todos los alumnos.
 3. Tendremos la opción de mostrar un alumno por su DNI o apellido.
 4. Podremos mostar alumnos por su grupo.
 5. Podremos mostrar a los alumnos por: nombre, dni y curso más alto.

**Postcondiciones:**

 * Se mostrará por el terminal (por defecto).
 * Se podrá seleccionar adicionalmente mostrar mediante fichero (markdown).
 * Si mostramos los alumnos por nombre, estarán ordenados alfabeticamente.
 * Si los mostramos por curso más alto, nos dará la opción de: Ascendete o descendente.
 * El líder de grupo saldrá diferenciado respecto a los demás.

**Flujos alternativos:**

 1. Si no existe el alumno o se ha introducido el DNI / Apellido de manera incorrecta el sistema dará error.
 2. Si introducimos algún parámetro mal, nos dará error y no nos dejará seguir.
