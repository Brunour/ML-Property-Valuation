# VentaInmueblesCABA


Descripción General

¿Cuál es el propósito del proyecto?

Este proyecto tiene como objetivo predecir los precios de inmuebles basados en diversas características de las propiedades y la calidad de vida en la zona. El objetivo es proporcionar estimaciones precisas que ayuden a compradores, vendedores o agencias inmobiliarias a tomar decisiones informadas.


Planteamiento del Problema

¿Por qué es relevante el proyecto?

El mercado inmobiliario es complejo, y los precios fluctúan según muchos factores. Este proyecto utiliza Machine Learning para ayudar a predecir estos precios, considerando tanto las características de los inmuebles como la calidad de vida en diferentes zonas.


¿Qué estoy tratando de resolver?

La meta es mejorar la precisión en la estimación de precios, integrando información sobre la situación socio-económica de la zona donde se ubica el inmueble y las características del mismo.


Pasos del Proyecto

  Cargar el Dataset
  Comenzamos cargando un dataset principal en formato CSV con más de 9000 registros de inmuebles en venta en la zona de CABA (Ciudad Autónoma de Buenos Aires).
      
  Entender el Dataset:
  Exploramos el dataset para comprender el tipo de datos con los que estamos trabajando, revisando el formato de las columnas, estadísticas generales y muestras.
      
  Limpieza de Datos:
  Se realizaron varias tareas de limpieza, como convertir valores nulos, cambiar formatos de columnas y ajustar los datos para su correcto análisis. Por ejemplo, la columna con los     
  precios de los inmuebles estaba en formato texto (string) y fue convertida a formato numérico (float) para facilitar los cálculos.
      
  Filtrar Información Irrelevante:
  Eliminar algunas columnas que contenían información irrelevante, como descripciones largas de los inmuebles, para centrarnos en las variables más importantes para el análisis.
      
  Combinar con Datos Externos:
  Se integró un nuevo dataset que contenía información de encuestas sobre la calidad de vida en Buenos Aires, incluyendo temas de seguridad e infraestructura. Esto permitió que el 
  modelo también pudiera considerar la zona en la que se encontraba cada inmueble para calcular el costo-beneficio o la calidad de vida.
      
  Transformar y Limpiar los Datos:
  Continuamos la limpieza de datos, agregando un nuevo dataset con códigos identificatorios de los barrios, ya que la columna de barrios estaba en formato texto, lo que no es adecuado 
  para el análisis de Machine Learning.
      
  Preparación para Machine Learning:
  Preparé los datos para trabajar con la biblioteca Scikit-learn (sklearn). Creé una nueva variable con los datos listos para entrenar el modelo de Machine Learning.
      
  Evaluación del Modelo:
  Al evaluar los resultados iniciales, el modelo no ajustaba correctamente debido a la falta de datos. Para mejorar la precisión, se agregaron más datos al conjunto, lo que mejoró la 
  predicción.


Análisis de Datos

¿Qué herramientas y métodos utilicé para el análisis?

El análisis fue realizado utilizando Python y varias librerías, como Scikit-learn para Machine Learning, Pandas para la manipulación de los datos, Matplotlib y Seaborn para las visualizaciones, y Google Colab como entorno de trabajo.

Perspectivas e Interpretaciones

¿Qué encontré y por qué es importante?

Los hallazgos muestran que tanto las características del inmueble como la calidad de vida en la zona son factores importantes en la determinación del precio. Esto ayuda a usuarios y empresas a tomar  mejores decisiones en el mercado inmobiliario.


¿Dónde encontré mis datos?

Los datos originales fueron extraídos de un proyecto correspondiente a la formación de Python para Data Science de Alura Latam. Este proyecto fue desarrollado inicialmente en base a datos de la ciudad de Bogotá, pero creí más conveniente convertirlos a datos de la ciudad de Buenos Aires, específicamente de los 49 barrios de la zona de CABA. El dataset de datos_indec fue armado por mi para los fines del proyecto, aunque podría hacerse con información relevada por el gobierno de la ciudad de buenos aires. Los precios de los inmuebles y las características de los barrios no son tampoco 100% reales, pueden ver un departamento en Núñez con 5 habitaciones a USD 100.000 que no es real ni mucho menos. 

Concusiones Finales

El proyecto y el análisis puede ser mejorado mucho mas cambiando variables como el tipo de inmueble, agregando enlaces para ver el inmueble, ampliar la zona de análisis a toda la provincia, hacer un análisis por comuna, agregar visualizaciones como Power Bi y mucho más que voy a ir realizando conforme vaya descubriendo más información y herramientas.
