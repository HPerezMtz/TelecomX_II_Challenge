# TelecomX_II_Challenge
Desafio de alura TelecomX parte 2
Predicción de Cancelación de Clientes (Churn) - Telecom X
Este proyecto forma parte del desafío Telecom X, enfocado en el análisis de datos y la creación de modelos predictivos para reducir la tasa de abandono de clientes (churn) en una empresa de telecomunicaciones.

📋 Descripción del Proyecto
El objetivo principal es identificar a los clientes con mayor probabilidad de cancelar sus servicios y comprender los factores críticos que influyen en esta decisión. Mediante el uso de técnicas de Machine Learning, se busca proporcionar insights accionables para diseñar estrategias de retención efectivas.

🛠️ Metodología y Preparación de Datos
El flujo de trabajo documentado en el notebook incluye:

Carga de Datos: Importación de un dataset previamente tratado con información demográfica, de servicios y facturación de los clientes.

Limpieza: Eliminación de columnas irrelevantes, como el customerID, que no aportan valor predictivo.

Codificación (Encoding): Transformación de variables categóricas a formato numérico mediante técnicas como One-Hot Encoding para asegurar la compatibilidad con los algoritmos.

Balanceo de Datos: Implementación de técnicas (como SMOTE) para manejar el desequilibrio entre clientes que cancelan y los que permanecen.

🤖 Modelos Evaluados
Se implementaron y compararon diversos modelos de clasificación, destacando:

Regresión Logística: Seleccionada por su alta interpretabilidad y rendimiento sólido en las métricas de evaluación.

Random Forest: Utilizado por su capacidad para manejar relaciones complejas entre variables.

K-Nearest Neighbors (KNN): Evaluado como alternativa de clasificación basada en proximidad.

📈 Conclusiones y Estrategias Sugeridas
Basado en los resultados del modelo de Regresión Logística, se proponen las siguientes acciones estratégicas:

Fomentar Contratos a Largo Plazo: Incentivar la migración de contratos mensuales a planes de 1 o 2 años mediante descuentos y programas de lealtad.

Mejora de la Experiencia en Fibra Óptica: Monitorear la satisfacción de clientes con cargos elevados y servicios de fibra, donde se detectaron mayores tasas de abandono.

Optimización de Métodos de Pago: Promover métodos de pago automáticos o más estables frente al uso de cheque electrónico, asociado a un mayor churn.

Onboarding para Nuevos Clientes: Reforzar la atención durante los primeros meses del contrato para mejorar la retención temprana.

🚀 Tecnologías Utilizadas
Python

Pandas / Numpy

Scikit-Learn

Jupyter Notebooks / Google Colab