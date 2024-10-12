
# **Ficha Técnica Valentina Rojas** 

1. **Características de los Datos**

La base de datos recoge información mensual sobre las 100 canciones más escuchadas en Chile en la plataforma Spotify, desde enero de 2020 hasta octubre de 2024. Las canciones están clasificadas por su posición en el ranking mensual, y se incluyen variables como el artista, el título de la canción, la mejor posición alcanzada, el número de semanas en el ranking y el total de reproducciones. Esta base de datos permite realizar un análisis detallado de las tendencias musicales y la popularidad de canciones y artistas a lo largo de los últimos 5 años en el país. 

2. **Alcance Metodológico**

Los datos provienen de los rankings mensuales publicados por Spotify en Chile y obtenidos a través de Spotify Charts, reflejando las 100 canciones más populares de cada mes en función de la cantidad de reproducciones. La recopilación abarca el periodo de enero 2020 a octubre 2024. Se incluyen variables tanto numéricas como categóricas para analizar la evolución de las canciones, los artistas, y las tendencias de consumo de música en el país. El análisis puede abarcar patrones anuales, la persistencia de canciones en el ranking, así como la relación entre la posición en el ranking y el total de reproducciones.

3. **Variables incorporadas y su descripción**

- **Mes y año:** Mes y año correspondientes al momento en que la canción se encontraba en el ranking.
- **#:** Posición de la canción en el ranking mensual (1-100).
- **Artista:** Nombre del artista o grupo que interpreta la canción.
- **Canción:** Título de la canción.
- **Clasificación ranking:** Mejor posición alcanzada por la canción en algún ranking mensual dentro del periodo.
- **Semanas ranking:** Número de semanas que la canción ha permanecido en el ranking de las 100 más escuchadas.
- **Reproducciones:** Cantidad total de reproducciones de la canción en el mes correspondiente.

4. **Observaciones sobre la Base de datos**

La variable peak_ranking puede variar para una misma canción si regresa al ranking en meses posteriores, mostrando el mejor rendimiento alcanzado en cualquier periodo.
La base de datos no incluye información sobre géneros musicales, aunque podría ser un complemento relevante para análisis más profundos.
Existen casos donde un artista o canción puede aparecer más de una vez debido a colaboraciones o reversiones, lo que puede influir en la interpretación de su popularidad.
Las variaciones en el total de reproducciones podrían ser influenciadas por factores externos, como el lanzamiento de videos musicales, promociones o eventos culturales que impulsan la visibilidad de la canción.
El análisis puede incluir comparaciones entre años y observar el comportamiento de ciertos géneros o artistas a lo largo del tiempo, así como identificar tendencias estacionales en el consumo de música.
