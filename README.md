# LATAM Mobility Economy Project  
**Objetivo** Evaluar cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades latinoamericanas.  Para ello utilizamos datos reales de TomTom Traffic Index y OECD Cities, que vamos a limpiar, combinar y analizar para identificar en qué ciudades conviene invertir en infraestructura de transporte.  
**Herramientas utilizadas:** Python & Pandas
Dataframes: tomtom_traffic.csv y oecd_city_economy.csv  
**Paso 1:** Cargar y explorar  
**Paso 2:** Explorar, limpiar y preparar los datos  
**Paso 3:** Extraer año y filtrar  
**Paso 4:** Analizar y resumir datos de movilidad  
La ciudad con el mayor tiempo promedio de tráfico es ...**mexico-city**  
**Paso 5:** Unir movilidad y economía  
**Paso 6:** Visualización y análisis de relaciones  
**No hay una relación clara entre el PIB per cápita y el congestionamiento vehicular, por ejemplo Montevideo tiene un PIB muy alto con un congestionamiento bajo, Ciudad de México tiene un PIB y congestionamiento altos y Santiago tiene un PIB bajo y alto congestionamiento**  
**Paso 7:** Exportar y documentar resultados  
1.- Boxplot de retrasos por congestionamiento (JamsDelay) donde observamos que la media es de 629.52 min y existen outliers donde el valor es de más de 2,500 min cuando el rango normal va de los 100 a los 700 min.  
2.- Histograma con la Distribución de la Economía donde se grafica la frecuencia del PIB per cápita y observamos que la mayor frecuencia se da entre los 6,000 USD y los 14,000 USD con un rango ampliado a 22,000 USD habiendo casos extremos a la baja entre 2,000 USD y 4,000 USD y a la alta entre 24,000 USD y 26,000 USD.  
3.- Gráfica de Barras conjunta de PIB per cápita y retrasos por congestionamiento, donde observamos el comportamiento de ambos durante el 2024 por ciudad de LATAM.  
**Hallazgos iniciales:**  
1.- La ciudad que presenta una alta congestión y una baja productividad es Santiago de Chile  
2.- Las ciudades que muestran una movilidad eficiente en conjunto con una economía fuerte de acuerdo a su PIB son: Belo Horizonte, Brasilia, Buenos Aires, Curitiba, Fortaleza, Montevideo, Porto Alegre, Recife, Rio de Janeiro y Salvador Bahía  
3.- No hay una relación directa del PIB per cápita vs Movilidad, esto es, a mayor PIB no necesariamente hay más problemas de movilidad y viceversa  
4.- Ciudades como Lima, México y Sao Paulo, tienen alto PIB pero también problemas de congestionamiento  
Habría que analizar los outliers donde los retrasos por congestionamiento tienen valores superiores a los 2,500 min cuando la media está en 629 min, eso podría afectar el resultado de alguna de las ciudades  
Tal vez se requiere de análisis más profundo en conjunto del porcentaje de desempleo por ciudad y su movilidad pues al existir un alto índice de desempleo la gente no se desplaza  
También se recomienda analizar con base al Traffic Index Live y el Week ago para ver si hay una tendencia o se mantiene estable  

**Recomendaciones**  
¿Qué ciudad : Bogotá, Lima o Buenos Aires o alguna otra en particular, muestra la mayor correlación significativa entre altos niveles de congestión vehicular y bajos indicadores de productividad económica, sugiriendo ser una **ciudad prioritaria para inversión en infraestructura de transporte? **   
**Bogotá** sería la ciudad prioritaria para inversión en infraestructura de transporte, aunque Santiago de Chile también podría ser una ciudad objetivo por la gran diferencia entre sus altos niveles de congestionamiento y baja productividad económica. Las otras ciudades donde se tiene un problema mayor de congestionamiento son Ciudad de México y Sao Paulo.
