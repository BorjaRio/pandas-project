# PANDAS-PROJECT

#Analisis inicial:

1. importamos el archivo a nuestro Jupyter Notebook.

hacemos una exploración preliminar del archivo:
    1. head(): primera vista preliminar del archivo
    2. describe(): max, min, mean , etc
    3. miramos el Shape() para definir filas y columnas

2. definimos el scope sobre el que vamos a trabajar: analisis del tipo de ataque y paises con mayor incidencia.

3. filtrado de las columnas que vamos a utilizar(columns Drop) :( Case Number, Type, Country,Area, Activity, Injury )

4. Data Cleaning:
    a) filtrado de datos: 1) Dentro del DataFrame
                          2) Dentro de la serie a analizar
    b)limpiar duplicados (Case Number)
    c) limpiado de valores nulos

5. definimos la variable master_data con nuestro DataFrame limpio

6. Analisis:
    1) por mayor numero de incidencia en el pais
    2) por tipo de actividad
    3) por área geografica más afectada
    4) por tipo de ataque ( objeto de estudio)

7. Representación visual mediante graficas

8. Analisis de los dtypes de datos.

9. Conclusiones del análisis por type de ataque, zona geográfica, área

