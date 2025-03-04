# Consultas SQL.
## ¿ Que es SQL? 
Es un lenguaje estandar de cuarta generación que se utiliza para gestionar, definir y manipular información contenida en una base de datos relacional.
sus siglas significan " structured query language (lenguaje estructurado de consultas)"
## ¿ Que es una base de base de datos? 
Una base de datos es un cojunto de base de datos organizados entre si, almacenados sistematicamente.
## Carácteristicas más importantes
-Los dartos estan interrelacionados 
-Las redundancias son minimas
-El acceso es concurrente, con multiples usuarios.
## ¿Que es un sistema de gestión de base de datos?
Son un tipo de software muy especifico dedicado  a servir en la interfaz entre la base de datos y las aplicaciones que el usuario utliza. proporcionan herramientas necesarias para que realizar las siguientes tareas:
-Definir la estructura de los datos.
-Manipulación de los datos.
-Insertar los datos.
-Modificar los datos.
-Borrar los datos.
-Integridad, mantener la información.
## Consultar los datos existentes con seguridad.
Privacidad y seguridad, control y seguridad de la base de datos por el medio de la restricción de acceso a los usuarios permitiendo el acceso a usuarios recomendados 
## Motores de base de datos 
Algunos de los sistemas de gestión de base de datos relacionales más difundidos son:
- SQL server Microsoft
- MySQL oracle
- MariaDB,basado en MYSQL
-PosgreSQL
-Oracle Data
- SQLite
## ¿ Que es una base de datos relacional?
Un modelo de base de datos relacional es un tipo de base de datos compuesto de:
-Entidades: Es decir objetos de los cuales recoge información relevante .
-Atributos: Son las carácteristicas de las entidades, tambien llamados metadatos, como por ejemplo ( nombre, apellido, fecha de naciemiento, dirección).
-Tablas:Que son los objetos de la base de datos donde se almacenan los datos, en la mayoria de los casos una tabla representa una entidad aunque támbien puede representar una sociación de entidades. 
- Las tablas estan compuestas por filas y columnas cada fila representa una ocurrencia de una entidad por ejemplo,( un cliente que sera almacenado en la tabla clientes)
- Cada columna representa una caracteristica de una entidad por ejemplo ( nombre, apellido y fecha de nacimiento)
- Relación es la conexión que puede existir en dos entidades  por ejemplo ( un cliente puede hacer una orden o un cliente pertenece a una ciudad)
- En en primer caso la  tabla clientes se relaciona con la tabla ordenes atreves de la columna "ID" que se encuentra en ordenes y se corresponde con el "ID" de la tabla clientes.
- En el segundo caso la tabla cliente continua en la columna "ciudad id"
  ## Gestión de base de datos DML, DDL.
  - Motor de base de datos que se incorpora que permite enviar comandos SQL que puedan ser procesados por el motor del servidor entre los tipos de diferencia.
  - DML= Entre ellas tenemos
  - SELECT= Para recuperar información.
  - INSERT= Para añadir filas
  - DELETE=Para eliminar filas
  - UPDETE= Para modificar filas
  - DDL
  - Tambien tenemos sentencias  de difinición de datos.
  - CREATE = Para crear objeto.
  - DROP = Para eliminar base de datos
  - ALTER = Para objetos de base de datos. 
    
    
  
