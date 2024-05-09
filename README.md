# qwikstartsolution
LAB: Vertex AI Workbench Notebook: Qwik Start
Semana 1: ML Engineer Google Cloud Certification.
Descripción:
Con este lab, obtendrás experiencia práctica en el entrenamiento de modelos de TensorFlow 2.x, tanto a nivel local como en Vertex AI Workbench. Después del entrenamiento, aprenderás a implementar tu modelo en Vertex AI para derivas (predicciones). Entrenarás el modelo para predecir la categoría de ingresos de una persona mediante el conjunto de datos de ingresos del censo de Estados Unidos.

En este lab, se brinda una introducción al entrenamiento y la predicción en Vertex AI de principio a fin. Se utilizará un conjunto de datos del censo para realizar lo siguiente:

Crear una aplicación de entrenamiento de TensorFlow 2.x y validarla de manera local
Ejecutar tu trabajo de entrenamiento en una sola instancia de trabajador en la nube
Implementar un modelo que admita la predicción
Solicitar una predicción en línea y ver la respuesta
Qué compilarás
Con la muestra, se compila un modelo de clasificación para la predicción de la categoría de ingresos según el conjunto de datos del censo de Estados Unidos. Las siguientes son las dos categorías de ingresos (también conocidas como etiquetas):

>50K: Superior a $50,000
≤50K: Inferior o igual a $50,000
La muestra define el modelo con la API secuencial de Keras. También determina las transformaciones de datos particulares del conjunto de datos del censo y luego asigna estos atributos (potencialmente) transformados a la DNN o a la parte lineal del modelo.

