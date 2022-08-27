## 1. Explique en qué consisten los siguientes conceptos: 
#### a. Data Werehouse.
Un data Werehouse es donde se almacenan los datos, específicamente donde se almacenan los datos que se utilizan en una aplicación estos pueden ser físicos como servidores, computadoras o más recientemente hay servicios en la nube. Los datos almacenados acá pueden ser procesados, leídos o modificados.
#### b. Data Lake.
Un data lake es donde los datos se almacenan sin procesar y sin filtros. Normalmente son grandes cantidades de datos a la espera de ser procesados o ordenados. Pueden ser datos estructurados o no.
#### c. Data Mart
Es un data werehouses enfocado en un área o tema específicos. Son simples de diseñar, construir y manejar. 
## 2. ¿De qué forma se benefician las aplicaciones del uso de Columnar Storage? Explique
Organiza cada columna en un bloque físico, permitiendo una mayor funcionalidad de entrada y salida para leída de datos, siendo por esto mejor para data werehousing
Además de se beneficia de una mejor compresión de los datos, Cada columna es empacada en su propio bloque, cada bloque físico contiene los mismos datos. Por eso se ocupa menos espacio para guardar información.

## 3. ¿En que consiste Streaming y batch processing?
##### El procesamiento de datos en Streaming
Consiste en el análisis de los datos en manera continua mientras están en “movimiento” y en tiempo real. Se procesan los datos que están entrando en ese momento en específico.
##### El procesamiento de datos Batch
Consiste en el procesamiento de grandes cantidades de información por partes, los datos son repetitivos, normalmente se procesan los datos sin parar y en orden secuencial. Es ideal cuando se puede procesar los datos en gran escala y no es vital que sea en tiempo real.


## 4. ¿En que consiste datos estructurados, semi estructurados y no estructurados?
##### Datos Estructurados.
Son aquellos que se encuentra procesados y ordenados. Se encuentran normalmente bien definidos en filas y columnas. Son más fáciles de gestionar porque ya se encuentran ordenados y filtrados.
Ejemplo una hoja de Excel.
##### Datos Semi Estructurados.
Son aquellos que están medianamente ordenados, no tienen un esquema fijo, tienen etiquetas para el manejo de los mismos.
Ejemplo XML
##### Datos No-Estructurados
Son datos que al no tener orden no se les puede asignar fila o columna, son los mas difíciles de trabajar por esto mismo.
Ejemplo Imágenes.

