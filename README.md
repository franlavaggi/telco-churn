# Telco Churn Prediction
Repositorio para el desarrollo de un modelo de Machine Learning enfocado en la predicción de la deserción de clientes de una empresa de telecomunicaciones.

# Descripción
Este proyecto tiene como objetivo principal predecir la deserción de clientes (churn) para que la empresa pueda tomar medidas preventivas y reducir la pérdida de clientes. Utiliza datos históricos proporcionados por la empresa Telco NN y aplica técnicas avanzadas de análisis de datos y aprendizaje supervisado.

Este trabajo forma parte de un proyecto académico realizado en la UTN.FRBA y alcanza una precisión del 80% en la predicción de clientes desertores.

# Objetivos
Identificar clientes con alta probabilidad de deserción.  
Evaluar y seleccionar el modelo de Machine Learning más adecuado.  
Aplicar técnicas de preprocesamiento y optimización de datos para mejorar el rendimiento del modelo.

# Dataset
El dataset inicial contiene 7043 muestras y 22 variables, incluyendo información sobre:

- Género del cliente (Gender).  
- Servicios contratados (InternetService, PhoneService, Contract).  
- Costos mensuales (MonthlyCharges).  
- Indicador de deserción (Churn), la variable objetivo.  

# Tecnologías
Lenguaje: Python 3.9+  
Bibliotecas principales:  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn

# Metodología
Exploración de datos (EDA): Análisis estadístico y visualización de datos para identificar patrones y relaciones.  
Modelos entrenados:  
- Support Vector Machine (SVM): Mejor modelo con un accuracy del 81.76%.  
- K-Nearest Neighbors (KNN): Accuracy del 77.78%.  
Reducción de dimensionalidad: Uso de PCA para evaluar impacto en el rendimiento. Resultado final del modelo con PCA: accuracy de 78.7%.  
Evaluación:  
- Matriz de confusión.  
- Curvas ROC.

# Estructura del proyecto
- clusterai_francisco_lavaggi_eda.ipynb: Notebook para el Análisis Exploratorio de Datos (EDA) y preprocesamiento.  
- clusterai_francisco_lavaggi_machine_learning.ipynb: Notebook con el desarrollo, pruebas y evaluación del modelo de Machine Learning.

# Ejemplo de uso
Ejecuta los notebooks en cualquier entorno compatible con Jupyter Notebook (por ejemplo, Jupyter Lab o Google Colab).

# Colaboradores
Francisco Lavaggi  
Luciano De Domenico

# Contribuciones
Las sugerencias y contribuciones son bienvenidas!

# Referencias
- Documentación de Scikit-learn  
- StandardScaler - Scikit-learn  
- Awad, M., & Khanna, R. Efficient Learning Machines (2015).  
- Cunningham, P., & Delany, S. J. k-Nearest Neighbour Classifiers (2015).
