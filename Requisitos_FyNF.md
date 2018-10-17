# ANÁLISIS DE REQUISITOS.

### PRÁCTICA 2. INGENIERÍA DEL SOFTWARE. UCO.
> ####Realizado por:

> * Francisco Javier Córdoba Rey

> * Ángel Cañuelo Ortiz

> * Andrés López Cardenas


## Partes Interesadas:
Las partes interesadas son el **profesor** (va a usar el software) y **alumnos** (almacenaremos sus datos).

## Datos almacenados.

En el software introduciremos un máximo de _150_ alumnos, y para cada uno de ellos añadiremos:

* Nombre y apellidos.
* Dirección.
* DNI.
* Fecha de Nacimiento.
* Email.
* Curso más alto matriculado.
* Teléfono.

Y opcionalmente:

* Número de Equipo.
* Líder o no _(como máximo 1 por equipo)_.

## Requisitos Funcionales y Prioridad
* El usuario deberá visualizar la interfaz en el terminal. [ **1** ]
* El usuario podrá cargar la información del usuario _(cargar Backup)_. [ **3** ]
* Introducir datos de alumnos manualmente. [ **2** ]
* Borrar alumno. [ **4** ]
* Mostrar datos de alumno. [ **4** ]
* Modificar datos de alumno. [ **4** ]
* Hacer _BackUp_. [ **3** ]
* Buscar alumno. [ **4** ]

## Requistos No Funcionales y Prioridad.
* Codificado en _[C++] (http://www.cplusplus.com)._ [ **1** ]
* Fácil y sencillo de usar. [ **2** ]
* Eficiente. [ **2** ]
* Desarrollado para el Sistema Operativo: _Linux_. [ **2** ]
* Almacenamiento del _BackUp_ en binario _(.bin)_. [ **3** ]
* Podremos almacenar como máximo _150_ alumnos. [ **3** ]