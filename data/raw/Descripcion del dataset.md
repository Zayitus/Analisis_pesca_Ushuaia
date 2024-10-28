Descripción preliminar de los datasets Utilizados:

1. **Desembarques**:
   - **Cantidad de instancias**: 451 registros.
   - **Características**: 15 columnas. Algunas tienen datos no nulos, y varias contienen valores nulos. Las columnas parecen estar mal estructuradas con nombres genéricos como "Unnamed", lo que sugiere que necesitarán limpieza.
   - **Tipos de datos**: Mezcla de objetos (texto) y números decimales (float64).
   - **Comentarios adicionales**: La estructura del dataset sugiere que proviene de un archivo donde las cabeceras no se leyeron correctamente, por lo que será necesario reorganizar y limpiar las columnas.

2. **Desembarques_especies**:
   - **Cantidad de instancias**: 7 registros.
   - **Características**: 1 columna.
   - **Tipos de datos**: Todos los datos son de tipo texto (object).
   - **Comentarios adicionales**: El dataset contiene datos resumidos de especies desembarcadas.

3. **Desembarques_flota**:
   - **Cantidad de instancias**: 451 registros.
   - **Características**: 35 columnas, algunas con nombres no definidos ("Unnamed").
   - **Tipos de datos**: Mezcla de objetos (texto) y números decimales (float64).
   - **Comentarios adicionales**: Similar al primer dataset, requiere limpieza para identificar correctamente las variables.

4. **Meteorología**:
   - **Cantidad de instancias**: 7 registros.
   - **Características**: 1 columna.
   - **Tipos de datos**: Texto.
   - **Comentarios adicionales**: El dataset contiene datos meteorológicos resumidos, posiblemente relacionados con temperaturas y precipitaciones.

