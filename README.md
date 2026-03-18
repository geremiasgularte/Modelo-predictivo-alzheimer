🧠 Predicción de Alzheimer con Machine Learning
📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar factores asociados a la enfermedad de Alzheimer y desarrollar un modelo de Machine Learning capaz de predecir su diagnóstico a partir de datos clínicos.

El análisis se basa en un dataset con información demográfica, hábitos de vida, historial médico, evaluaciones cognitivas y síntomas de pacientes.

🎯 Objetivos

-Explorar los datos para identificar patrones relevantes

-Analizar qué variables están más asociadas al Alzheimer

-Construir y evaluar modelos predictivos

-Validar si es posible predecir el diagnóstico con datos clínicos

🧰 Tecnologías utilizadas

-Python

-Pandas

-NumPy

-Scikit-learn

-Matplotlib / Seaborn

-Jupyter Notebook

📊 Dataset

El dataset contiene:

-2149 registros de pacientes

-35 variables

Incluye:

-Datos demográficos (edad, género)

-Factores de estilo de vida

-Historial médico

-Mediciones clínicas

-Evaluaciones cognitivas y funcionales

-Síntomas

-Diagnóstico de Alzheimer (variable objetivo)

🔄 Pipeline del proyecto

1.Carga y limpieza de datos

-Revisión de valores nulos

-Preparación de variables

2.Análisis exploratorio (EDA)

-Distribución de variables

-Identificación de patrones

-Correlaciones

3.Preprocesamiento

-Selección de variables relevantes

-División en train/test

4.Modelado

-Entrenamiento de modelos de clasificación

-Evaluación con métricas

5.Evaluación

-Accuracy

-Precision / Recall

-Análisis de desempeño

🤖 Modelos utilizados

-Random Forest

-Gradient Boosting Classifier

-CatBoost Classifier

📈 Resultados

    Precisión Recall F1-score
0   0.95      0.97   0.96
1   0.94      0.91   0.93

Accuracy: 0.95    AUC: 0.94

El modelo mostró una buena capacidad para identificar pacientes con Alzheimer, lo que sugiere que los datos clínicos utilizados tienen valor predictivo.

🧠 Conclusiones

Variables como la edad y el deterioro cognitivo tienen una fuerte relación con el diagnóstico

El modelo logra predecir el Alzheimer con un nivel aceptable de precisión

Este enfoque podría utilizarse como apoyo en estudios clínicos preliminares

🚀 Cómo ejecutar el proyecto

Clonar el repositorio:

git clone https://github.com/tu-usuario/tu-repo.git

Instalar dependencias:

pip install -r requirements.txt

Ejecutar el notebook:

jupyter notebook
📂 Estructura del proyecto
├── Dataset_Alzheimer.xlsx
├── Analisis_Alzheimer.ipynb
├── Explicacion.ipynb
├── README.md
└── requirements.txt

💡 Mejoras futuras

-Optimización de hiperparámetros

-Probar modelos más avanzados

-Validación cruzada

-Deploy del modelo (API o app)

👨‍💻 Autor

Proyecto desarrollado como práctica de análisis de datos y machine learning aplicado a salud.
