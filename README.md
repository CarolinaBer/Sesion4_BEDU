# Sesión4_BEDU: Fundamentos de MongoDB.
En esta sesión establecimos una conección a la base de datos no relacional MongoDB la cual utiliza el **modelo orientado a documentos**.Además de esto algunas de sus características son:
- Documentos de esquema libre.
- Las colecciones contienen documentos.
- Más localidad por lo que son necesarios menos JOIN. 
- Sin embargo se tiene más redundancia y por tanto más desnormalización.
- Con ello la lectura de datos es más rápida pero la agregación de datos se alenta.

En esta caso, las BD orientadas a documentos siguen el formato JSON y BSON utilizando el modelo **llave-valor** equivalente al valor de una columna de una BD relacional.
Mongo DB Compass hace uso de la orientación llave-valor e utiliza BSON (JSON como compilador).

Para utilizar Mongo DB Compass se realizó la creación de un Cluster en MongoDB Atlas utilizando como Cloud provider: AWS y EU como región. 
En esta sesión los retos fueron:
### :pushpin: Reto 1. Colecciones, Documentos y Proyecciones.
Usando la base de datos `sample_mflix`, proyecta los datos que se solicitan.

- Fecha, nombre y texto de cada comentario.
- Título, elenco y año de cada película.
- Nombre y contraseña de cada usuario.
