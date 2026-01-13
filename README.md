# Telecom X – Análisis de Churn

## Descripción
Este proyecto analiza la evasión de clientes (Churn) en la empresa Telecom X con el fin de identificar patrones que expliquen por qué los clientes cancelan el servicio.

El análisis forma parte de un desafío de Alura en el área de Ciencia de Datos.

## Objetivo
- Analizar el comportamiento de los clientes que cancelan el servicio.
- Identificar variables relacionadas con la evasión.
- Proponer recomendaciones basadas en datos.

## Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Archivo principal
El análisis se encuentra en el notebook:

- `Challenge_Telecom_x.ipynb`

3. Ejecutar las celdas en orden para visualizar el análisis.

📊 Análisis Realizado

Durante el análisis se llevaron a cabo los siguientes procesos:

Carga de datos desde una API pública.

Limpieza y tratamiento de datos.

Normalización de columnas anidadas.

Conversión de variables binarias (Sí/No → 1/0).

Creación de la variable derivada Cuentas_Diarias.

Análisis descriptivo general del dataset.

Visualización de la distribución de churn.

Análisis de churn según variables categóricas.

Comparación de churn con variables numéricas usando boxplots.

🔍 Principales Insights

Aproximadamente 26.5% de los clientes presenta evasión (Churn = 1).

Los clientes con contratos mensuales tienen una tasa de evasión significativamente mayor que aquellos con contratos a largo plazo.

Los clientes con menos de 18 meses de antigüedad tienen mayor probabilidad de cancelar el servicio.

Los clientes con cargos mensuales altos tienden a abandonar el servicio con mayor frecuencia.

Los servicios adicionales como OnlineSecurity y TechSupport parecen actuar como elementos de retención.

La automatización del pago (métodos automáticos) está asociada con una tasa de churn menor.

🚀 Recomendaciones Estratégicas

A partir de los resultados del análisis, se sugieren las siguientes acciones:

Incentivar a los clientes a migrar de contratos mensuales a contratos de mayor duración ofreciendo beneficios o descuentos.

Implementar campañas de retención para clientes con baja antigüedad (primeros 12–18 meses).

Promover servicios adicionales que aumenten el valor percibido por el cliente.

Incentivar el uso de métodos de pago automáticos para reducir la evasión.

Como siguiente etapa, desarrollar modelos predictivos para estimar la probabilidad de churn por cliente.

👩‍💻 Autor

Proyecto desarrollado por Alejandra Molina (Ale2779)
Proyecto realizado – Alura LATAM
