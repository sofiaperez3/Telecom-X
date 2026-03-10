# 📊 Telecom X: Análisis de Evasión de Clientes (Churn)

Este repositorio contiene el análisis exploratorio de datos (EDA) realizado para Telecom X, una empresa de telecomunicaciones que enfrenta un desafío crítico de retención de clientes. El objetivo principal es limpiar y transformar datos complejos en formato JSON para facilitar el modelado predictivo por parte del equipo de Ciencia de Datos.

## 📋 Contexto del Proyecto

Telecom X ha identificado un alto índice de evasión de clientes. Mi rol como Analista de Datos consistió en:

Extraer datos anidados desde fuentes JSON.

Limpiar y tratar valores nulos o tipos de datos incorrectos.

Analizar visualmente los factores que impulsan el Churn (abandono).

Exportar un dataset listo para Machine Learning.

## 🛠️ Tecnologías y Herramientas

Python 3.x

Pandas: Procesamiento y limpieza de datos (normalización de JSON).

Matplotlib & Seaborn: Visualización de patrones de comportamiento.

Google Colab: Entorno de desarrollo colaborativo.

## 📂 Estructura de los Datos

El dataset original (TelecomX_Data.json) presenta una estructura anidada que fue aplanada para el análisis:

customer_: Datos demográficos y antigüedad (tenure).

phone_ / internet_: Servicios contratados por el cliente.

account_: Información financiera y de contrato (Cargos mensuales y totales).

Churn: Variable objetivo (Yes/No).

## 🚀 Instalación y Uso

Clona este repositorio:

git clone [https://github.com/tu-usuario/telecom-x-churn.git](https://github.com/tu-usuario/telecom-x-churn.git)


Sube el archivo TelecomX_Data.json a tu entorno de Google Colab.

Ejecuta el notebook o el script telecom_x_churn_analysis.py.

## 📈 Hallazgos Clave

A través del análisis visual, se identificaron tres factores críticos:

Tipo de Contrato: Los clientes con contrato de mes a mes representan la mayor parte de la evasión.

Permanencia: Los primeros 12 meses son el periodo de mayor riesgo de abandono.

Costos: Existe una tendencia donde los clientes que cancelan el servicio tenían cargos mensuales superiores al promedio de los clientes leales.
