📊 Telecom X parte 2- Predicción de Cancelación de Clientes (Churn)
📌 Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar los servicios de Telecom X.

La cancelación de clientes (churn) representa un desafío importante para las empresas de telecomunicaciones, ya que implica pérdida de ingresos y mayores costos de adquisición de nuevos clientes. Mediante técnicas de análisis de datos y modelos predictivos, se busca identificar patrones que permitan anticipar este comportamiento y apoyar la toma de decisiones estratégicas.

🎯 Objetivos
Preparar y transformar los datos para el modelado.
Analizar la relación entre variables y la cancelación de clientes.
Entrenar modelos de clasificación para predecir churn.
Evaluar el rendimiento de los modelos mediante métricas.
Identificar las variables más influyentes en la cancelación.
Proponer estrategias de retención basadas en los resultados obtenidos.

🗂️ Dataset
El dataset utilizado contiene información de clientes de Telecom X, incluyendo:
Información demográfica
Servicios contratados
Tipo de contrato
Forma de pago
Tiempo de permanencia
Gastos mensuales y totales

📂 Dataset utilizado en el proyecto:
datos_tratados.csv
Disponible en:
https://raw.githubusercontent.com/Luis-Rivadeneyra-94/TelecomX/main/datos_tratados.csv

⚙️ Proceso del Proyecto
El proyecto sigue las principales etapas de un flujo de Machine Learning:
1️⃣ Carga y preparación de datos
Eliminación de columnas irrelevantes
Tratamiento de valores nulos
Codificación de variables categóricas (One-Hot Encoding)

2️⃣ Análisis exploratorio
Análisis de correlaciones
Visualización de relaciones entre variables
Identificación de variables relevantes

3️⃣ Preparación para modelado
División del dataset en entrenamiento y prueba
Estandarización de variables para modelos sensibles a escala

4️⃣ Entrenamiento de modelos
Se entrenaron dos modelos de clasificación:
Regresión Logística
Árbol de Decisión

5️⃣ Evaluación de modelos
Los modelos se evaluaron utilizando:
Accuracy
Precision
Recall
F1-score
Matriz de Confusión
Curva ROC

📈 Resultados
El análisis permitió identificar variables relevantes asociadas a la cancelación de clientes, especialmente aquellas relacionadas con:
Tiempo de permanencia del cliente
Tipo de contrato
Servicios adicionales contratados
Gasto mensual y total
Los modelos desarrollados permiten detectar clientes con mayor riesgo de cancelación, lo que puede ayudar a la empresa a tomar acciones preventivas.

💡 Estrategias de Retención Propuestas
A partir de los resultados obtenidos se sugieren algunas estrategias:
Programas de fidelización para clientes nuevos.
Ofertas personalizadas para clientes con mayor riesgo de cancelación.
Mejora en la oferta de servicios adicionales.
Optimización de planes según el perfil de los clientes.
Estas acciones pueden ayudar a reducir la tasa de cancelación y mejorar la retención de clientes.

🛠️ Tecnologías Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

📚 Aprendizajes del Proyecto
Este proyecto permitió aplicar conceptos de:
Análisis exploratorio de datos
Preparación de datasets
Modelos de clasificación
Evaluación de modelos de Machine Learning
Interpretación de resultados para la toma de decisiones

👨‍💻 Autor

Luis Rivadeneyra

Proyecto desarrollado como parte del desafío de Data Science y Machine Learning.
