# Borrar_Alumno

**ID:** *05*

**Breve descripción:** El usuario podrá mostrar uno o varios alumnos.

**Actores principales:** Usuario (Profesor).

**Actores Secundarios:** Alumnos.

**Precondiciones:**

 1. El usuario / usuarios a mostrar ya tiene que estar añadidos al sistema.
 2. Se debe pulsar la tecla indicada en el menú para acceder a *Borrar_Alumno*

**Flujo principal:**

 1. El caso de uso empieza cuando se accede en el menú a la opción: *Borrar_Alumno*.
 2. Después nos pedirá la opción de borrar por DNI o apellido al alumno.
 3. Después debemos de introducir dicho DNI o Apellido por terminal.

**Postcondiciones:**

 * Si existen dos alumnos con el mismo apellido, solo se podrá borrar por DNI.

**Flujos alternativos:**

 1. Si no existe el alumno o se ha introducido el DNI / Apellido de manera incorrecta el sistema dará error de borrado.
