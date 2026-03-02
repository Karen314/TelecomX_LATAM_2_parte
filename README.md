# TelecomX_LATAM_2_parte
Este proyecto utiliza aprendizaje automático para identificar a los clientes con mayor probabilidad de cancelar sus servicios en una empresa de telecomunicaciones.

## Objetivo

Desarrollar un modelo de clasificación que permita entender por qué los clientes abandonan la compañía y qué factores ayudan a retenerlos.

## Estructura de los Datos

El análisis se basa en un conjunto de datos de 7,043 clientes que incluye información sobre:

* Servicios contratados: internet, seguridad, soporte técnico.
* Detalles del contrato: antigüedad, tipo de pago y cargos mensuales.
* Estado de fuga: variable churn que indica si el cliente se retiró.

## Herramientas Utilizadas

Para el desarrollo se utilizaron las librerías de Python: pandas, numpy, scikit-learn, seaborn y matplotlib.

## Resultados del Análisis

El modelo y el análisis de correlación revelaron los siguientes puntos:

* Los clientes con facturas mensuales elevadas y servicio de fibra óptica tienen mayor tendencia a retirarse.
* La antigüedad del cliente y los contratos a largo plazo (dos años) son los factores que más ayudan a mantener a los clientes.
* Servicios como soporte técnico y seguridad en línea reducen significativamente la probabilidad de fuga.

## Conclusiones y Estrategias

Se recomienda incentivar los contratos de larga duración y ofrecer programas de fidelización durante los primeros meses de servicio para reducir la rotación.

---

### Instrucciones de uso

1. Instalar las dependencias necesarias.
2. Abrir el archivo telecomX_2.ipynb en un entorno de Jupyter Notebook.
3. Ejecutar las celdas en orden para reproducir el entrenamiento del modelo y los gráficos.
