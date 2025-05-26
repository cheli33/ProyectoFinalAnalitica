# Análisis de Siniestros Viales con Python y Google Colab

Este proyecto tiene como objetivo analizar una base de datos de siniestros viales utilizando herramientas de análisis de datos en Python. El análisis se realizó en Google Colab y se enfoca en identificar patrones relevantes que permitan comprender mejor el comportamiento de los accidentes de tránsito en función de variables como tipo de vehículo, gravedad del accidente, día de la semana, hora y ubicación geográfica.

---

## ¿Qué se realizó en el proyecto?

1. **Carga y limpieza de datos**  
   - Se utilizó una base de datos con más de 1 millón de registros.
   - Se limpiaron valores nulos e inconsistencias.
   - Se normalizaron columnas clave (por ejemplo, tipo de vehículo, fechas y horas).

2. **Análisis Exploratorio de Datos (EDA)**  
   - Se graficaron distribuciones por tipo de vehículo, gravedad, día y hora.
   - Se identificaron patrones de siniestralidad a lo largo de la semana.
   - Se analizó la franja horaria de mayor incidencia.
   - Se analizó los vehiculos de mayor incidencia
  

3. **Visualizaciones**  
   - Gráficos de barras, gráficos de línea y matriz.
   - Uso de `matplotlib`y `seaborn` para representar los datos.

4. **Hallazgos clave**  
   - Predominio de siniestros con motocicletas y autos.
   - Mayor número de siniestros los viernes y martes.
   - Horarios críticos entre 12:00 a.m. y 1:00 p.m.
   - Mayor frecuencia en zonas urbanas densas.

---


## ¿Cómo ejecutar este proyecto?

1. Abre los archivos de Google Colab:

    Limpieza datos: [Abrir en Google Colab](LimpiezaProyectoFinal(1).ipynb)

    Analisis Exploratorio: [Abrir en Google Colab](AnalisisExploratorioProyectoFinal.ipynb)

2. Asegúrate de subir el archivo `.csv` o `.xlsx` de la base de datos al entorno (`Archivo > Subir archivo`).

3. Ejecuta las celdas del notebook una por una.

4. Verifica los resultados en las gráficas interactivas.

---


