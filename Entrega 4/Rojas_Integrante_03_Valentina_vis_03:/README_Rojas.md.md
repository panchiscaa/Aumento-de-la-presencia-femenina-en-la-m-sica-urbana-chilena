README VALE

# Proyecto:**"Colaboraciones que abren camino: el rol femenino en la música urbana"**

## Descripción General
Este proyecto analiza la presencia femenina en el Top 100 mensual de Spotify Chile entre 2020 y 2024, centrándose en el género urbano. La visualización busca destacar la participación de artistas femeninas tanto en temas solistas como en colaboraciones, en comparación con artistas masculinos.

Esta visualización nació a partir de un análisis de datos sobre las 100 canciones más escuchadas en Spotify Chile, mensualmente, desde enero 2020 hasta octubre 2024, en el que destacaron las cifras de artistas femeninas dentro del género urbano. De este ranking, se buscó la presencia de 17 artistas femeninas urbanas, seleccionadas como las más populares del género, el ranking de más de 5000 canciones se encontró la presencia en 52 ocasiones , en donde 35 de ellas fue a través de colaboraciones con hombres.

---

## Proceso de Selección de Datos

### Fuente de Datos:
Se utilizó una base de datos en formato CSV que contiene información sobre las 100 canciones más escuchadas en Spotify Chile desde enero de 2020 hasta octubre de 2024. Las variables que esto incluía son:

- **Mes y Año:** Mes y año correspondientes al momento en que la canción se encontraba en el ranking.  
- **#:** Posición de la canción en el ranking mensual (1-100).  
- **Artista:** Nombre del artista o grupo que interpreta la canción.  
- **Canción:** Título de la canción.  
- **Clasificación Ranking:** Mejor posición alcanzada por la canción en algún ranking mensual dentro del periodo.  
- **Semanas Ranking:** Número de semanas que la canción ha permanecido en el ranking de las 100 más escuchadas.  
- **Reproducciones:** Cantidad total de reproducciones de la canción en el mes correspondiente.


### Procesamiento de Datos:
1. **Filtrado:**
   - Se seleccionaron solo las canciones de 17 cantantes femeninas de género urbano para centrar el análisis en este nicho musical.
2. **Clasificación:**
   - Las canciones se clasificaron según el género del/de los intérprete(s): femenino, masculino o mixto.
3. **Columnas Adicionales:**
   - Se añadieron columnas para identificar si las canciones eran solistas femeninas o colaboraciones femeninas.
4. **Eliminación de Datos Redundantes:**
   -Se eliminaron las posiciones de la canción en el ranking mensual (1-100).
   -Nombre del artista o grupo que interpreta la canción.
   -Título de la canción.  
   -Mejor posición alcanzada por la canción en algún ranking mensual dentro del periodo.  
   -Número de semanas que la canción ha permanecido en el ranking de las 100 más escuchadas.  
   -Cantidad total de reproducciones de la canción en el mes correspondiente.

### Selección de la base:
Esta base fue elegida porque proporciona un panorama claro del desempeño musical mensual y permite responder preguntas clave sobre la evolución de la presencia femenina en un ámbito dominado por hombres.

---

## Proceso de Visualización

### Pasos Realizados:

#### Selección del Gráfico:
Se utilizó un gráfico de barras apiladas para mostrar la cantidad de canciones de artistas femeninas en el Top 100 por mes, diferenciando entre temas solistas y colaboraciones. Esta elección permite observar tendencias temporales y comparar con claridad los distintos tipos de participación.

#### Preparación de los Datos:
- Los datos procesados se agregaron por mes, contabilizando canciones según el tipo de participación.
- Se calcularon cuantas canciones por mes, eran en formato solista o colaboración.

#### Visualización:
- **Ejes:**
  - **X:** Meses (eje temporal).
  - **Y:** Número de canciones.
- **Colores:**
  - Verde para colaboraciones.
  - Morado para canciones solistas femeninas.
- **Leyendas y Títulos:** Se incluyeron para facilitar la interpretación del gráfico.

### Herramientas Utilizadas:
- **Excel** Para limpieza y agregación de datos. 
- **Altair** Para crear y personalizar la visualización.
-**Google Colab** Para ejecutar los códigos.

### Decisiones Tomadas:
- Añadir los meses en que no había presencia femenina, para también visualizarlo.
- Diferenciar colaboraciones de temas solistas para entender mejor las dinámicas de participación femenina.

---

## Ejemplos de Preguntas que Responde la Visualización
1. ¿Cuántas canciones de artistas femeninas urbanas han entrado al Top 100 mensualmente entre 2020 y 2024?
2. ¿Cuál es la proporción de colaboraciones frente a temas solistas entre las artistas femeninas?
3. ¿Existen meses donde no hubo representación femenina en el ranking?
4. ¿Cómo se compara la presencia femenina con la masculina en el género urbano en el Top 100?
5. ¿Cuál es la tendencia general de la presencia femenina en el género urbano a lo largo de los años?

---

## Reflexión y Aporte del Proyecto
Este análisis no solo presenta datos sobre la música urbana chilena, sino que también aporta una mirada crítica sobre la brecha de género en la industria musical. Las visualizaciones ayudan a evidenciar un progreso incipiente pero significativo hacia una mayor inclusión de las mujeres, inspirando reflexiones sobre el futuro del género.
