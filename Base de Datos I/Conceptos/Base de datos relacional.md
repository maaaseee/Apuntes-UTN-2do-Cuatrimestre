> Una Base de datos relacional es aquella cuyos usuarios la perciben como un conjunto de tablas. Se visualiza con un diseño de tabla de doble entrada.
### Propiedades de las tablas relacionales:

-  **Cada entrada de la tabla representa un ítem de datos, no hay grupos repetitivos.** Ej.: significa que ninguna tabla tendrá dos columnas con los mismos datos.
- **Son homogéneas por columna.** Todos los ítems de una columna son de la misma clase. En cada intersección de fila y columna sólo hay un valor.
- **Cada columna tiene su propio nombre, único en esa tabla.**
- **Todas las filas son distintas**; no se permiten filas duplicadas.
- **Las tablas tienen una clave primaria única para esa tabla.** La clave primaria es un identificador único para la tabla. Puede ser una PK simple, si está representada por sólo una columna, o compuesta, si la PK está representada por más de una columna. **[[Primary Key (PK)]]**
- **Las filas y columnas pueden considerarse en cualquier secuencia y momento.** No están ordenadas.
### Tipos de relaciones:

- #### Relaciones base o reales 
> Son aquellas relaciones con nombre. Son las tablas o entidades.

- #### Vistas (relaciones virtuales) 
> Es una relación derivada con nombre, representada dentro del sistema mediante su definición en términos de otras relaciones con nombre. No posee datos almacenados propios, separables y distinguibles.

- #### Instantáneas (snapshot) 
> También es una relación derivada con nombre, pero son reales; están representadas no sólo por su definición en términos de otras relaciones con nombre sino también por sus datos propios almacenados. Son utilizadas para realizar reportes de un momento específico en el tiempo, por ejemplo, si necesitamos un reporte de la base de datos a un cierto horario especificado.

- #### Resultado de consultas 
> Pueden o no tener nombre. No tienen existencia persistente.

- #### Relaciones temporales
> Es una relación con nombre que se destruye, por ejemplo, al terminar una sesión activa.