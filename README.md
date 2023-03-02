
<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INTEGRADOR M6** </h1>

# <h1 align=center>**`MERCADO AUTOMOTOR`**</h1>

<p align="center">
<img src="https://www.rionegro.com.ar/wp-content/uploads/2022/01/digitalizacion-en-la-industria-automotriz-G.jpg"  height=300>
</p>
 
<hr>  

## **Clasificación y precio de los vehículos**

## 1. Introducción
El mercado automotor esta muy ligado a la cultura de cada país, según los gustos de cada uno, el mercado norteamericano, por ejemplo, valora mucho los motores y vehículos muy grandes, el mercado europeo prefiere el bajo consumo, el mercado latinoamericano, los precios finales bajos y asi varía según región, país, nivel socioeconómico y cultura. Un mismo vehículo puede tener un valor muy distinto de un pais al otro, y no solo por los impuestos o costos de producción, sino por cómo cotiza el modelo en el mercado.  
Hemos sido contratados en el equipo de ciencias de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de mercado de una importante automotriz china. Nuestro cliente desea ingresar a nuestro mercado de automóviles, por lo que nos han encomendado analizar las características de los vehículos presentes en el mercado actual. Dado que tienen en su catálogo una amplia colección de modelos de todo tipo, cuyo catálogo está estratificado en gamas según el gusto de cada región, desean saber qué características presentan los vehículos de gama alta y los de gama baja en nuestro mercado, para poder abarcar todo los públicos objetivos ajustándose a toda la demanda y, en base a estos datos, poder cotizar correctamente los vehículos que ofrecerá.  
Para ello, nuestro departamento de datos ha recopilado precios y características de varios de los modelos de vehículos disponibles en nuestro mercado, junto con sus precios de venta al público.  
Nuestro Data Lead nos ha recomendado que analicemos detalladamente los datos, los preprocesemos debidamente y que diseñemos dos modelos predictivos, uno para el precio y otro para distinguir vehículos de gama alta y de gama baja, utilizando la mediana de los precios como punto de corte. Desean obtener los archivos con las predicciones en formato de texto plano.

Además del análisis detallado de la exploración de los datos, estas son las dos predicciones posibles que les interesaría analizar:

1. Implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de los vehículos en baratos y caros usando la mediana de los precios como punto de corte, utilizando los datos que se han puesto a su disposición.

2. Implementar un modelo de regresión con aprendizaje supervisado que permita predecir el precio final de los vehículos, utilizando los datos que se han puesto a su disposición.

## 2. Preparación de datos
### Descripción de los datos
Los datos recopilados constan de información de 205 vehículos, incluyendo su precio de venta, características técnicas como la marca, modelo, año, tipo de combustible, capacidad de motor, entre otras. Los datos se han recopilado de varias fuentes en línea, y se han procesado para que sean coherentes y estén limpios. Los datos se encuentran en formato CSV, y se han almacenado en la carpeta "data".

### Procesamiento de datos
Para poder utilizar los datos para nuestros análisis, se han realizado los siguientes procesos:

**Limpieza de datos**: se han eliminado las filas duplicadas y se han completado los valores faltantes.  
**Selección de características**: se han seleccionado las características que se consideran relevantes para nuestros análisis.  
**Codificación de características categóricas**: se han codificado las características categóricas en valores numéricos.  
**Escalado de características**: se ha utilizado la técnica de escalado para normalizar las características numéricas.  
Los datos limpios y procesados se han almacenado en la carpeta "processed_data".  

## 3. Modelamiento y evaluación
**Modelos de aprendizaje automático**:
Se han implementado dos modelos de aprendizaje supervisado para realizar las predicciones solicitadas por el cliente:

**Modelo de clasificación**: se ha utilizado el algoritmo de Random Forest para clasificar los vehículos en baratos y caros, utilizando la mediana de los precios como punto de corte. Se ha utilizado la técnica de validación cruzada para evaluar la precisión del modelo.

**Modelo de regresión**: se ha utilizado el algoritmo de Regresión Lineal para predecir el precio final de los vehículos. También se ha utilizado la técnica de validación cruzada para evaluar la precisión del modelo.

### Evaluación de los modelos
Se ha evaluado la precisión de los modelos utilizando la técnica de validación cruzada y se han comparado los resultados con los valores reales. Se ha utilizado la métrica de error cuadrático medio (MSE) para evaluar el rendimiento de los modelos.

### Resultados
Los resultados de los modelos se han almacenado en la carpeta "results" en formato de texto plano, tal y como lo solicitó el cliente. También se han generado gráficos para visualizar los resultados de las predicciones.

### Instrucciones para replicar el proyecto
Para replicar el proyecto, se deben seguir los siguientes pasos:

Descargar o clonar el repositorio en local.  
Instalar las dependencias necesarias que se encuentran en el archivo "requirements.txt".  
Ejecutar el notebook "EDA.ipynb" para realizar el análisis exploratorio de datos.  
Ejecutar el notebook "Data Preparation.ipynb" para preparar los datos para los modelos.  
Ejecutar el notebook "Modeling and Evaluation.ipynb" para implementar los modelos de aprendizaje automático y generar los resultados.  
Verificar que los resultados generados se encuentran en la carpeta "results".  

## **Fuente de datos**



## **Material de apoyo**

"Prolijidad" del codigo:

+ https://pandas.pydata.org/docs/development/contributing_docstring.html

contacto: takticflow
:bowtie:
