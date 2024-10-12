# **README Valentina Rojas**

1. **Exploración inicial**
Para esta entrega, trabajamos con una base de datos que contiene información sobre las 100 canciones más escuchadas mensualmente en Chile a través de Spotify, desde enero de 2020 hasta octubre de 2024. Los datos fueron obtenidos directamente de los rankings mensuales de Spotify. El propósito del proyecto es analizar las tendencias en el consumo de música en Chile, observar la persistencia de ciertas canciones en el ranking y detectar los picos de popularidad de distintos artistas.

**Proceso**
- 1. **Carga de datos:** Comencé importando los archivos CSV que contenían los datos del ranking mensual, con variables como el número de la canción en el ranking, el nombre del artista, el título de la canción, el peak en el ranking y las reproducciones totales.
Exploración: Revisé las columnas para verificar la estructura y consistencia de los datos, identificar valores faltantes y comprobar si había duplicados o registros anómalos.

- 2. **Eliminación de variables no relevantes**
Al revisar el dataset, identifiqué algunas variables que no eran necesarias para el análisis de popularidad de las canciones, por lo que fueron eliminadas para simplificar la base de datos. Entre las variables eliminadas se encontraban:

         - Link de la canción es Spotify
          - Compañía productora: Posición de la canción en un ranking anterior

Estas eliminaciones permitieron reducir el tamaño de la base de datos y centrarnos en las variables más importantes para el análisis.

- 3. **Normalización de datos**
Detecté varias inconsistencias en los nombres de los artistas y las canciones. Algunas canciones aparecían varias veces bajo diferentes nombres debido a colaboraciones, versiones o errores tipográficos. Para unificar los datos:
Corregí nombres de artistas y canciones, asegurando la consistencia a lo largo de los rankings mensuales.
Formateé las fechas y los nombres de canciones, unificando el formato de escritura para evitar duplicados no deseados.

4. **Creación de nuevas variables**
Para esta entrega, por temas de tiempo no tuve la disponibilidad de crear nuevas variables, aunque sí tengo muy presente que para la próxima entrega quiero integrar variables como si el artista es chileno o no, si la canción es una colaboración,  el género del artista y el género musical al que pertenece la canción, para así profundizar más en el análisis. 

5. **Eliminación de duplicados**
Durante el proceso no fue necesario eliminar datos duplicados. 

6. **Fuentes de Datos Utilizadas**
Spotify Charts: Utilizado para obtener la lista de las 100 canciones más escuchadas mensualmente en Chile desde 2020 hasta 2024.
Justificación: Spotify es una de las plataformas más importantes para la distribución de música en Chile, y su ranking mensual refleja de manera directa las preferencias de los usuarios en el país.

7. **Preguntas para Análisis**
Algunas preguntas que guiarán nuestro análisis son:
¿Cuáles son las canciones que han permanecido más tiempo en el ranking y cómo se comparan sus reproducciones acumuladas?
¿Cuáles son los artistas que aparecen con mayor frecuencia en el ranking?
¿Qué canciones han alcanzado el peak más alto y qué factores podrían haber influido en su popularidad?
¿Existen patrones estacionales en el consumo de música, por ejemplo, canciones más populares en verano o invierno?
¿Cómo ha evolucionado el ranking en términos de géneros musicales predominantes?
