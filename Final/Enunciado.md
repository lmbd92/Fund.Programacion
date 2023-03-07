# PROYECTO FINAL ESPECIALIZACION ANALISIS DE DATOS

UNIVERSIDAD DE ANTIOQUIA

1. COVID

    Realizar la limpieza de datos, analizar los tipos de datos, datos nulos, generar un gráfico que indique la cantidad de muertos por covid a nivel mundial

    usar las siguientes librerías  

    import numpy as np

    import pandas as pd

    import matplotlib.pyplot as plt

    import plotly.express as px

    import seaborn as sns

    a) Leer archivo

    b) Conocer la forma del dataset

    c) Información del dataset --- df.info()

    d) Borrar elementos con tipo de dato diferente

    e) Encontrar datos nulos en más del 50% de datos nulos

    f) Revisar si hay países duplicados

    g) Porcentaje de pacientes que murieron por cada país

    h) Top 10 de países con más cantidad de muertos

    i) Los 10 países con menos muertos

    j) 10 países con más pacientes recuperados

    k) En cada caso anterior graficar los resultados país vs muertes totales

    l) investigar la libreria px.scatter_geo y usarla para mostrar los casos en un mapa

2. Analizar los canales más vistos en youtube.

    A diciembre de 2022, MrBeast es el YouTuber con más suscriptores, con 116 millones de suscriptores. PewDiePie es el segundo más popular con 111 millones de suscriptores.

    Para celebrar haber alcanzado los 100 millones de suscriptores, MrBeast regaló una isla privada, lo que probablemente sea parte de la razón por la que le quitó el primer puesto a PewDiePie.

    a) Leer estadísticas

    b) Mostrar datos nulos  

    c) Mostrar datos duplicados

    d) Las columnas de datos 2, 3 y 4 contienen datos numéricos, pero tienen formato de objetos (cadenas) y deberán limpiarse y convertirse.

    e) Contar cantidad de registros por categoría - Desgloce por categoria

    f) Hay 30 entradas para una categoría desconocida titulada como una URL que debe eliminarse.

    g) Se debe hacer limpieza del dataframe , para esto debe remover los delimitadores (,) y convertir los string a enteros

    h) Muestre el canal con mayor cantidad de vistas

    i) Realice un diagrama de distribución de canales por subscriptores con boxplot

    j) Diagrama de distribución de canales por vistas de videos

    k) Diagrama de distribución de canales por cantidad de videos

    l) Nuevo Dataframe para mantener el recuento de valores de categoría  

    m) Graficar el top 5 de canales por categoría con más vistas usando sns.countplot y plt.pie
