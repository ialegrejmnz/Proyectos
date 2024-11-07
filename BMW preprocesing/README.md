# Proyecto de Limpieza y Preprocesado de Datos para Predicción de Precios

## Descripción del Proyecto

El objetivo de este proyecto es realizar la limpieza y el preprocesado de un conjunto de datos con el fin de crear un modelo que permita predecir el precio de un producto o servicio en un futuro.

## Project Description

The goal of this project is to perform data cleaning and preprocessing on a dataset to build a model that can predict the price of a product or service.

### Librerías Utilizadas / Libraries Used

Para el desarrollo de este proyecto, se emplearon las siguientes librerías de Python:

```
$ import pandas as pd
$ import numpy as np
$ import math
$ import matplotlib.pyplot as plt
$ import seaborn as sns
$ from sklearn.preprocessing import LabelEncoder, MinMaxScaler, OrdinalEncoder
$ from sklearn.model_selection import train_test_split
$ from sklearn.linear_model import LinearRegression
```

### Estructura del Proyecto / Project Structure

* Análisis Exploratorio de Datos (EDA)
  
Exploración inicial de los datos para identificar valores nulos, outliers, y patrones en las variables.

* Limpieza de Datos
  
Eliminación de valores nulos, manejo de outliers y corrección de inconsistencias en los datos.

* Codificación y Escalado
  
Codificación de variables categóricas (usando LabelEncoder y OrdinalEncoder) y escalado de variables numéricas (con MinMaxScaler) para optimizar el rendimiento del modelo.

* División del Conjunto de Datos
  
Separación de los datos en conjuntos de entrenamiento y prueba para evaluar el modelo en futuras etapas.

* Modelo de Regresión Lineal (Guía)
Implementación de un modelo de regresión lineal básico que sirve como guía para la creación y evaluación del preprocesamiento.
