Análisis de Datos de Airbnb en Madrid
=====================================

Este proyecto analiza un conjunto de datos de Airbnb para la ciudad de Madrid. Se ha utilizado el lenguaje de programación R y se han realizado diversos análisis y visualizaciones utilizando un archivo Quarto (`.qmd`), con versiones en HTML para una fácil visualización.

Estructura del Repositorio
--------------------------

El repositorio está organizado de la siguiente manera:

*   **Carpeta `data`**: Contiene el conjunto de datos utilizado en el análisis, `airbnb.csv`. Este archivo incluye los datos de listados de Airbnb para Madrid y es esencial para reproducir los análisis presentados.
    
*   **Carpeta `img`**: Alberga imágenes de algunos de los gráficos generados durante la práctica. Estas imágenes representan visualizaciones clave derivadas del análisis de datos y son útiles para una rápida referencia visual.
    
*   **Archivo `AirbnbAnalysis.qmd`**: El documento principal de Quarto que contiene todo el código, análisis y visualizaciones realizados en este proyecto.
    
*   **Archivo `AirbnbAnalysis.html`**: Una versión HTML del archivo `.qmd` para facilitar la visualización del análisis sin necesidad de ejecutar el código en R. Ideal para aquellos que prefieren una vista rápida del proyecto o no tienen el entorno necesario para ejecutar archivos Quarto.
    

Visualización y Uso del Proyecto
--------------------------------

Para visualizar y utilizar este proyecto:

1.  **Clonar o Descargar el Repositorio**: Puedes clonar este repositorio o descargarlo como un archivo ZIP para acceder a todos los archivos.
    
2.  **Abrir el Archivo `.qmd`**: Si tienes Quarto y R configurados, puedes abrir y ejecutar `AirbnbAnalysis.qmd` para una vista detallada y reproducible del análisis.
    
3.  **Visualizar el HTML**: Para una rápida revisión, abre `AirbnbAnalysis.html` en un navegador web.
    
4.  **Explorar los Datos y las Imágenes**: La carpeta `data` contiene los datos utilizados en el análisis, mientras que la carpeta `img` ofrece una representación gráfica de los resultados clave.

Este repositorio está diseñado para ser accesible y fácil de utilizar. 

Resumen de los Ejercicios
-------------------------

Este proyecto incluye una serie de ejercicios enfocados en el análisis de datos de Airbnb en Madrid, utilizando R:

1.  **Conversión de Unidades**: Creación de una columna `MetrosCuadrados` a partir de `PiesCuadrados`.
2.  **Limpieza de Códigos Postales**: Corrección de entradas erróneas y estandarización de los códigos postales.
3.  **Identificación de Códigos Postales**: Análisis de los códigos postales presentes en el dataset.
4.  **Frecuencia de Códigos Postales**: Determinación de los códigos postales más y menos frecuentes.
5.  **Análisis de Barrios por Código Postal**: Identificación y recuento de barrios en el código postal 28012.
6.  **Recuento de Entradas por Barrio**: Análisis de la distribución de entradas en cada barrio del código postal 28012.
7.  **Total de Barrios en el Dataset**: Recuento y listado de todos los barrios en el conjunto de datos.
8.  **Barrios con Mayor Número de Entradas**: Identificación de los cinco barrios más populares.
9.  **Análisis de Tipos de Alquiler**: Exploración de los diferentes tipos de alquiler, sus frecuencias y distribución de precios.
10.  **Análisis Estadístico de Precios**: Estudio de la significancia estadística en las diferencias de precios medios por tipo de alquiler.
11.  **Filtrado por Tipo de Alquiler**: Creación de un dataframe específico para alquileres de "Entire home/apt".
12.  **Top Barrios por Apartamentos Completos**: Análisis de los barrios con más apartamentos enteros en alquiler.
13.  **Precio Medio en Barrios Seleccionados**: Cálculo y comparación del precio medio de alquiler en barrios seleccionados.
14-25. **Análisis Detallado del Barrio Sol**: Estudio profundo del barrio Sol, incluyendo correlaciones, filtrado de datos, modelo lineal para estimar precios y análisis probabilísticos.

Estos ejercicios proporcionan una visión integral del mercado de alquileres de Airbnb en Madrid, utilizando métodos estadísticos y de visualización de datos para extraer insights valiosos.
