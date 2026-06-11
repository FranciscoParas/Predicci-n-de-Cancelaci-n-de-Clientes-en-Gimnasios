# Predicción de Cancelación de Clientes en Gimnasios 

### Descripción del proyecto

La cadena de gimnasios Model Fitness busca reducir la pérdida de clientes mediante el uso de análisis de datos y aprendizaje automático.

El objetivo de este proyecto fue identificar los factores que influyen en la cancelación de membresías, desarrollar un modelo predictivo capaz de detectar clientes con riesgo de abandono y segmentar a los usuarios mediante técnicas de clustering para diseñar estrategias de retención más efectivas.

🎯 Objetivos:

Analizar el comportamiento de los clientes del gimnasio.
Identificar las variables relacionadas con la cancelación de membresías.
Construir modelos de clasificación para predecir la pérdida de clientes.
Comparar el desempeño de distintos algoritmos de Machine Learning.
Crear segmentos de clientes mediante clustering.
Generar recomendaciones para mejorar la retención.

Herramientas utilizadas:

Python,
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-Learn,
SciPy,
Jupyter Notebook

Metodología:

Preparación y exploración de datos (EDA)

Se realizó una revisión completa del conjunto de datos para:

Verificar valores faltantes.
Analizar estadísticas descriptivas.
Identificar patrones de comportamiento.
Comparar clientes que permanecieron activos contra aquellos que cancelaron su membresía.

También se construyeron histogramas y distribuciones para visualizar diferencias entre ambos grupos.

Análisis de correlación

Se generó una matriz de correlación para identificar relaciones entre las variables del negocio y detectar factores asociados con la cancelación de clientes.

Modelo predictivo de churn

Se construyeron modelos de clasificación binaria para predecir si un cliente cancelaría su membresía el mes siguiente.

Modelos evaluados:

Regresión Logística
Random Forest

Las métricas utilizadas para comparar el desempeño fueron:

Accuracy
Precision
Recall

Segmentación de clientes

Se aplicaron técnicas de aprendizaje no supervisado para identificar grupos de clientes con características similares.

Proceso realizado:

Estandarización de variables.
Construcción de dendrograma.
Aplicación de K-Means.
Análisis de características promedio por clúster.
Evaluación de la tasa de cancelación por segmento.

Principales hallazgos:

El análisis mostró que los clientes con menor riesgo de cancelación suelen presentar:

Contratos de mayor duración.
Mayor frecuencia de visitas al gimnasio.
Participación en servicios adicionales.
Mayor interacción con actividades grupales.

Por otro lado, los clientes con baja asistencia y contratos cortos presentaron mayores tasas de abandono.

Recomendaciones:

Incentivar contratos de largo plazo.
Diseñar campañas de seguimiento para clientes con baja frecuencia de asistencia.
Promover actividades grupales para aumentar el compromiso.
Implementar programas de fidelización para clientes con mayor riesgo de cancelación.
Utilizar el modelo predictivo para detectar usuarios en riesgo antes de que abandonen el servicio.

Habilidades demostradas:

Análisis Exploratorio de Datos (EDA)
Limpieza y preparación de datos
Visualización de datos
Machine Learning Supervisado
Clasificación Binaria
Predicción de Churn
Segmentación de Clientes
Clustering (K-Means)
Interpretación de métricas de modelos
Generación de recomendaciones de negocio
