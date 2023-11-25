Análisis de Datos de Airbnb
===========================

Este proyecto analiza un conjunto de datos de Airbnb. Se ha utilizado el lenguaje de programación R y se han realizado diversos análisis y visualizaciones utilizando un archivo Quarto (`.qmd`).

Ejercicios Realizados
---------------------

1.  **Conversión de Unidades**: Creación de una nueva columna `MetrosCuadrados` a partir de la columna `PiesCuadrados`.
2.  **Limpieza de Códigos Postales**: Corrección y estandarización de los datos de la columna `Codigo Postal`.
3.  **Análisis de Códigos Postales**: Identificación de los códigos postales presentes en el conjunto de datos.
4.  **Análisis de Frecuencia de Códigos Postales**: Determinación de los códigos postales con más y menos entradas.
5.  **Barrios en Código Postal 28012**: Identificación de barrios en el código postal específico 28012.
6.  **Frecuencia de Entradas por Barrio en 28012**: Recuento de entradas para cada barrio en el código postal 28012.
7.  **Recuento de Barrios**: Total de barrios en el dataset y sus nombres.
8.  **Barrios con Mayor Número de Entradas**: Identificación de los 5 barrios con más entradas.
9.  **Tipos de Alquiler**: Análisis de los diferentes tipos de alquiler, sus nombres y frecuencias.
10.  **Análisis Estadístico de Precios**: Cálculo del precio medio de alquiler por tipo y análisis de significancia estadística.
11.  **Filtrado de Tipo de Alquiler**: Creación de un dataframe `airbnb_entire` para alquileres de "Entire home/apt".
12.  **Top Barrios por Apartamentos Completos**: Análisis de los barrios con más apartamentos enteros.
13.  **Precio Medio por Barrio en Apartamentos Completos**: Cálculo del precio medio y su distribución por barrio.
14.  **Distribución de Apartamentos por Barrio**: Análisis de la cantidad de apartamentos por barrio.
15.  **Barrios con Mayor Precio y Suficientes Entradas**: Identificación de barrios con alto precio medio y más de 100 entradas.
16.  **Distribución de Precios por Barrio**: Visualización de la distribución de precios para los barrios seleccionados.
17.  **Tamaño Medio de Apartamentos**: Cálculo del tamaño medio de apartamentos en los barrios seleccionados.
18.  **Distribución de Tamaños de Apartamentos**: Visualización de la distribución de tamaños de apartamentos.
19.  **Análisis Estadístico de Tamaños de Apartamentos**: Prueba estadística para diferencias en el tamaño medio entre barrios. 20-25. **Modelo Lineal en Barrio Sol**: Análisis detallado del barrio Sol, incluyendo correlación entre variables, filtrado de datos, modelo lineal para estimar precios y análisis de probabilidades.

Trabajando con Archivos `.qmd`
------------------------------

Los archivos Quarto (`.qmd`) son utilizados para la creación de documentos reproducibles en R. Para trabajar con estos archivos, sigue estos pasos:

1.  **Instalación de Quarto**: Asegúrate de tener [Quarto](https://quarto.org/) instalado en tu sistema.
2.  **Abrir el Archivo `.qmd`**: Puedes abrir archivos `.qmd` en un editor de texto o en un IDE compatible como RStudio.
3.  **Ejecutar el Código**: En RStudio, puedes ejecutar el código en el archivo `.qmd` de manera interactiva. Esto te permitirá ver los resultados del análisis paso a paso.
4.  **Generar Reportes**: Quarto te permite convertir tu `.qmd` en varios formatos como HTML, PDF o Word, facilitando la compartición y presentación de tus análisis.

Para más detalles sobre cómo trabajar con archivos `.qmd`, consulta la [documentación oficial de Quarto](https://quarto.org/docs/get-started/).