# README Francisca Martínez

A mi me toco hacer la preparación y limpieza de datos 2 un nuestro proyecto llamada: **Presencia femenina actual en la industria urbana chilena**

Para la entrega 1 comenzamos con una lista de mujeres que forman parte de la industria de la música chilena urbana. Teniendo información clave (en pdf y en CVS) de cada una. Esta infromación contemplaba un resumen de la artista en:

- Spotify
- Youtube
- Instagram
- Tiktok
- De su audiencia

Toda esta información fue recolectada gracias a la página web Chartmetric (donde se puede descargar el archivo en CVS) y recopilamos infoomación de las siguientes artistas:

1. Paloma Mami
2. Princesa Alba
3. Akriila
4. Soulfia
5. Loyaltty
6. Akatumami
7. Kuina
8. Flor de Rap
9. Anita Tijoux
10. Tomasa del Real
11. Blue Mary
12. Lizz
13. KYA
14. Shirel
15. Aura BAE
16. Fran Maira
17. Amikiraa

# Proceso y decisiones

### 1. Importación y exploración inicial

- **Carga de Datos:** Comencé importando el archivo CSV que contenía información relacionada con la presencia de artistas femeninas en la música urbana chilena. La base incluía datos sobre artistas, colaboraciones y métricas relacionadas con el impacto en la industria musical.

- **Exploración:** Realicé una revisión inicial de las columnas y filas para entender la estructura de los datos, buscar valores duplicados y determinar si había valores faltantes o inconsistencias en la base de datos.

### 2. Eliminación de Variables No Relevantes

Durante la exploración, identifiqué algunas variables que no eran relevantes para el análisis de la presencia femenina en la música urbana y su relación con las colaboraciones. Estas variables fueron eliminadas para simplificar el dataset y asegurar que los datos fueran útiles para el análisis de la hipótesis del proyecto. Esta variables eliminadas fueron:

- País
- Ciudad actual
- Rango de Artista en CM
- Rango de Género Principal
- Rango de Géneros Secundarios
- Rango de Compromiso
- Rango de Base de Fans
- Nombre del Rango por País
- Rango de Seguidores en Spotify
- Popularidad en Spotify
- Alcance Total de PlaylistS en Spotify
- Relación Alcance de PlaylistS con Seguidores en Spotify
- Relación Oyentes-Seguidores en Spotify
- Tasa de Conversión de Fans en Spotify
- Fans en Deezer
- Rango de Fans en deezer
- Rango de Seguidores en Instagram
- Vistas en Youtube
- Número de Suscriptores en Youtube
- Vistas Diarias de Videos en Youtube
- Vistas Mensuales de Videos en Youtube
- Seguidores en Tiktok
- Rango de Seguidores en Twitch
- Streams en Pandora
- Rango de Streams en Pandora
- Oyentes Mensuales en Pandora
- Rango de Oyentes Mensuales en Pandora
- Estaciones de Artistas en Pandora
- Rango de Estaciones de Artistas en Pandora
- Likes del Artista en Line Music
- Rango de Likes del Artista en Line Music
- Likes en Line Music
- Rango de Likes en Line Music
- Vistas de Video en Line Music
- Rango de Vistas de Videos en Line Music
- Fans en Melon
- Rango de Fans en Melon
- Me Gustas en Melón
- Rango de Me gustas en Melón
- Likes de Videos en Melón
- Vistas de Videos en Melón
- Rango de Vistas de Videos en Melón

### 3. Normalización de Datos

En algunos casos, los nombres de los artistas o las colaboraciones estaban escritos de forma inconsistente o con errores tipográficos. Estos valores fueron corregidos para unificar los nombres y facilitar su análisis.

Además, se normalizaron los valores relacionados con las plataformas de distribución para que tuvieran un formato estándar y fueran más fáciles de comparar.

### 4. Creación de nuevas variables

Para abrodar mayor la hipotesis del estudio, añadi nuevas variables que indicaban el nombre de las y los artistas con lo que han realizado colaboraciones. Lo que permite realizar un análisis más detallado del impacto de las colaboraciones en la visibilidad de las artistas femeninas. Además estos datos nos ayudaran a realizar los mapas de conecciones entre artistas que propusimos en la entrega 1. 

Quedando finalmente con la siguentes variables:

- Nombre de la artista
- Año debut
- Oyentes mensuales en Spotify
- Seguidores en Spotify (aprox.)
- Seguidores en Instagram (aprox.)
- Artistas femeninas con las que ha colaborado
- Artistas masculinos con los que han colaborado
- Temáticas de las canciones (en general)
- Subgénero (de la música ubana al que pertence)
Top 3 canciones más escuchadas en Spotify (nombre de la canción + artistas presentes + número de oyentes)

### 5. Eliminación de Duplicados
Se eliminaron registros duplicados de colaboraciones o métricas repetidas para evitar que los datos se contaran más de una vez, lo que podría haber distorsionado el análisis.

## Fuentes de Datos Utilizadas

**Chartmetric:** Utilizado para obtener datos sobre el rendimiento de las colaboraciones y la popularidad de las artistas femeninas en plataformas digitales.

- **Justificación:** Chartmetric es una herramienta clave para medir el impacto de las colaboraciones y la visibilidad de los artistas en las principales plataformas de streaming y redes sociales.

**Genius:** Utilizado para analizar las canciones de las artistas y determinar las temáticas generales de sus letras y el subgénero en el que se enmarcan.

- **Justificación:** Genius es una plataforma que proporciona las letras de las canciones, lo que permite hacer un análisis cualitativo de las temáticas tratadas por las artistas, así como clasificar sus canciones dentro de subgéneros específicos del urbano chileno.

**Spotify:** Utilizado para obtener datos sobre las colaboraciones y el alcance de las artistas femeninas en la música urbana.

- **Justificación:** Esta plataforma tiene una de las bases de usuarios más grandes a nivel mundial y es uno de los principales medios de distribución de música urbana en Chile.

**Redes Sociales (Instagram):** Datos de seguidores y menciones de artistas femeninas en Chile.

- Justificación: Las redes sociales son fundamentales para entender la visibilidad y el engagement de las artistas con sus audiencias.

# Preguntas

1. ¿Cúal es la relación entre el año de debut y el número de oyentes mensuales en Spotify?

2. ¿Qué artistas femeninas han colaborado más frecuentemente con asrtistas masculinos?

3. ¿Cúales son las temáticas más comunes en las caciones de las artistas femeninas y cómo se distribuye por subgénero?

4. ¿Cómo han evolucionado el número de seguidores en Instagram de las artistas desde su año de debut?

5. ¿Cúantos álbums han publicado las artistas femeninas en relación con sus oyentes mensuales en Spotify?

