## 1. **Información**

En general, la información en la base de datos está integrada y es compartida.
- Integrada significa que la base de datos puede considerarse como una unificación de varios archivos de datos, eliminando total o parcialmente cualquier redundancia, o sea que los datos no se repitan.
- Compartida significa que los elementos individuales de información en la base de datos puede compartirse entre varios usuarios distintos.

##### "Catálogo del sistema"
Funciona como diccionario de datos e incluirá todos los detalles descriptivos de la base.

## 2. **Información**

Consiste en los servidores de la base de datos: volúmenes de almacenamiento, los dispositivos de E/S, controladores de dispositivos, procesadores y memorias principales.

## 3. **Programas**

- ==Programas de aplicación==: permiten la interacción entre los usuarios y la base de datos.
- ==Programas de administración==: el sistema de administración (SGBD), maneja las solicitudes de acceso a la base de datos, la obtención y puesta al día de los datos. El SGBD está compuesto por software para procesar consultas y software para tener acceso a los datos almacenados

## 4. **Usuarios**

Hay cuatro tipos de usuarios:
### - Administrador de Bases de Datos
Es la persona que toma las decisiones estratégicas y de política con respecto a la información de la empresa.

Sus funciones son:

**La definición del esquema conceptual.**
- Identificar las entidades y la información que debe registrarse acerca de esas entidades (diseño
Lógico), identificando los diseños de las tablas que debo realizar.

**La definición del esquema interno.**
- Cómo se representará la información en la BD (diseño Físico). Se utiliza DDL (data
definition language).

**La vinculación con los usuarios.**
- El DBA se encargará de garantizar la disponibilidad de los datos que los usuarios necesiten y
ayudarlos con el esquema externo.

**La definición de las verificaciones de seguridad e integridad.**
- Respecto a los permisos que los usuarios reciben para interactuar con la base de datos (Los usuarios pueden realizar operaciones de DML *sobre sus propias tablas*, y no sobre las de otros usuarios).
- Las validaciones de los datos ingresados en las tablas, para que se encuentre dentro del marco lógico de la base de datos (Por ejemplo, un límite de edad entre los 18 a los 65 años).

**La puesta en práctica de procedimientos de respaldo y recuperación.**

- Backup lógico: la copia de seguridad con toda la información de la base de datos en un archivo .dmp (FULL EXPORT).
- Backup físico: la copia del archivo del tipo .dbf (data base file).

1. Primero hago el Backup lógico en un archivo .dmp.
2. Reviso que el backup se haya realizado correctamente.
3. Realizo un Backup físico de toda la base de datos.

**La supervisión del desempeño y responder a cambios en los requerimientos.**
- Cantidad de usuarios concurrentes.
- El uso de la memoria.

### - Analista de sistemas y programador de aplicaciones:
**Los analistas** determinan los requerimientos de los usuarios finales. 
**Los programadores** escriben los programas que utilizan la BD, para luego probar, depurar, documentar y mantener estas transacciones programadas.