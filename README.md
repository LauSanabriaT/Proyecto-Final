# Proyecto-Final
Detección automática de anomalías en señales ECG

Objetivo Principal
El objetivo principal de este programa es desarrollar una herramienta capaz de analizar señales electrocardiográficas (ECG) y detectar de manera precisa y eficiente cualquier desviación de la normalidad en el ritmo cardíaco. Estas anomalías pueden indicar la presencia de arritmias, bloqueos cardíacos u otras patologías cardiacas.

Funcionalidades Clave
Carga y Preprocesamiento de Datos:

Carga de datos: El programa permitirá cargar archivos ECG en diferentes formatos (e.g., .csv, .txt, .mat).
Filtrado: Eliminación de ruido y artefactos presentes en la señal ECG mediante filtros digitales (e.g., filtros de banda pasa, notch).
Segmentación: División de la señal en segmentos de interés, como ciclos cardíacos individuales, para un análisis más detallado.
Normalización: Escalado de los datos para garantizar una comparación consistente entre diferentes registros.
Extracción de Características:

Dominio del tiempo: Cálculo de características como frecuencia cardíaca, amplitud de las ondas P, QRS y T, intervalos RR, etc.
Dominio de la frecuencia: Análisis espectral de la señal para identificar componentes de frecuencia relevantes.
Dominio del tiempo-frecuencia: Utilización de transformadas de onda para obtener una representación conjunta de la señal en tiempo y frecuencia.
Detección de Anomalías:

Aprendizaje supervisado: Entrenamiento de modelos de clasificación (e.g., redes neuronales artificiales, máquinas de soporte vectorial) utilizando un conjunto de datos etiquetado con ejemplos de señales normales y anómalas.
Aprendizaje no supervisado: Detección de anomalías como puntos atípicos en un espacio de características utilizando técnicas como autoencoders o aislamiento de bosques.
Reglas basadas: Definición de umbrales y reglas empíricas para identificar desviaciones de la normalidad en las características calculadas.
Visualización de Resultados:

Gráficas: Representación visual de las señales ECG originales y procesadas, junto con las características extraídas y los resultados de la clasificación.
