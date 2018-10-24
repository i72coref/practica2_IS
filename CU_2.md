# Cargar Backup

**ID:** *02*

**Breve descripción:**
En cualquier momento se podrá realizar una copia de los alumnos guardados en el sistema, este backup será en un fichero de texto.

**Actores principales:** Usuario (Profesor).

**Actores Secundarios:** Alumnos.

**Precondiciones:**
Para poder cargar un backup el usuario tiene que tener un backup con el formato correcto, en un fichero binario.

**Flujo principal:**

1. El programa pide el nombre del backup. 
2. Se busca el fichero especificado.
3. Se cargan los datos del fichero en memoria.

**Postcondiciones:**
Se muestra un mensaje informando que el proceso se ha realizado con éxito.


**Flujos alternativos:**
En caso de no encontrar el fichero especificado saltará un error, y después se pedirá de nuevo el nombre del backup.