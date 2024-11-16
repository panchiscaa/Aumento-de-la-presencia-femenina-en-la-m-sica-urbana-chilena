# README proceso Francisca Martínez

## Proceso de selección de datos

1. **Cargar datos**: 
   - Cargue mi base de datos desde el archivo CSV. Ocupando la misma base de datos anteriormente realizada en la entrega 2, utilizando la biblioteca `pandas`. Este archivo contenía diversas métricas y datos relacionados con las artistas femeninas de música urbana chilena.
   - Para garantizar que los datos estaban correctamente estructurados y listos para el análisis, inspeccioné las primeras filas con el comando **head()**, verificando que los nombres de las columnas y las filas estuvieran alineados con las expectativas iniciales.

3. **Selección de columnas relevantes**: 
  De entre todas las columnas disponibles en el archivo, seleccioné únicamente aquellas que estaban directamente relacionadas con los objetivos de la visualización y la historia que quería contar:

- **Nombre del artista:** Era esencial para identificar a las artistas y como eje principal de todas las visualizaciones.
- **Oyentes mensuales en Spotify:** Indicador clave de la resonancia musical de cada artista en términos de consumo frecuente en una de las plataformas de streaming más importantes del mundo.
- **Seguidores en Spotify (aprox):** Refleja un nivel más profundo de conexión con el público, ya que los seguidores suelen ser personas interesadas en recibir actualizaciones y estar al tanto de nuevos lanzamientos.
- **Seguidores en Instagram (aprox):** Esta métrica proporciona una perspectiva diferente, centrada en la popularidad visual y personal de las artistas, así como en la construcción de sus marcas personales más allá de la música.

La selección de estas columnas no fue arbitraria; estas métricas se eligieron porque juntas permiten contar una historia completa sobre cómo las artistas conectan con sus audiencias desde diferentes perspectivas. Por ejemplo:

- Los oyentes mensuales muestran el impacto musical directo.
- Los seguidores en Spotify indican un compromiso sostenido.
- Los seguidores en Instagram revelan la influencia en redes sociales y su capacidad para trascender su rol como artistas.

3. Eliminación de valores faltantes:

Para evitar inconsistencias o interpretaciones erróneas, eliminé las filas que contenían valores faltantes en cualquiera de estas columnas. Esto garantizó que los datos fueran comparables y representativos en todas las visualizaciones.

4. **Procesamiento y preparación de datos**:
   - Las métricas seleccionadas no requerían transformación adicional porque ya estaban en formatos comparables. Esto permitió una transición directa hacia la etapa de visualización.

## Proceso de visualización

1. **Gráficos creados con Altair**:
- Utilicé la biblioteca Altair para diseñar tres visualizaciones distintas, todas ellas gráficos de barras, cada uno enfocado en una dimensión de la popularidad digital.
- Cada gráfico fue diseñado con el objetivo de contar una parte de la historia de la popularidad de las artistas en plataformas digitales, y se incluyeron herramientas como **tooltip** para proporcionar información adicional al usuario.

- **Visualización 1: Oyentes mensuales en Spotify por artista**
   + **Objetivo:** Mostrar qué artistas son las más escuchadas en Spotify.
   + **Detalles técnicos:** El gráfico utiliza el eje X para los nombres de las artistas y el eje Y para los oyentes mensuales, ordenados en forma descendente.
   + **Historia:** Este gráfico muestra cómo la música de cada artista resuena con su audiencia y cuál es la preferencia del público en términos de consumo recurrente.

- **Visualización 2: Seguidores en Spotify por artistas**
   + **Objetivo:** Comparar la base de seguidores de las artistas en Spotify.
   + **Detalles técnicos:** El gráfico utiliza el eje X para los nombres de las artistas y el eje Y para los Seguidores en Spoify, ordenados en forma descendente.
   + **Historia:** Este gráfico resalta el nivel de conexión y compromiso de los fans con cada artista, ya que seguir a una artista implica interés continuo en su trayectoria.

- **Visualización 3: Seguidores en Instagram por artistas** 
   + **Objetivo:** Visualizar la popularidad de las artistas en redes sociales, en este caso Instagram.
   + **Detalles técnicos:** El gráfico utiliza el eje X para los nombres de las artistas y el eje Y para los Seguidores en Instagram, ordenados en forma descendente.
   + **Historia:** Refleja cómo las artistas construyen su marca personal y cómo utilizan Instagram para mantener un vínculo cercano con sus seguidores.

2. **Exportación**:
   - Para facilitar su consulta, los gráficos fueron exportados en formato HTML, permitiendo una visualización interactiva en navegadores.
   - Además, se generaron versiones en formato PNG para ser utilizadas en la entrega del proyecto.

## Ejemplos de preguntas que responde la visualización

- ¿Qué artistas tienen el mayor número de oyentes mensuales en Spotify?
- ¿Qué artistas destacan en oyentes mensuales pero tienen pocos seguidores en Instagram? 
- ¿Qué artistas destacan en una métrica específica, pero están rezagadas en las demás?
- ¿Hay alguna artista que logre un balance entre oyentes mensuales y seguidores en ambas plataformas?

Esta exploración nos permite entender la diversidad en la popularidad y presencia digital de las principales voces femeninas de la música urbana chilena.