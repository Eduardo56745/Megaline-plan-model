# 📊🤖 Modelo de Recomendación de Planes de Megaline

Este proyecto tiene como objetivo ayudar a **Megaline** a recomendar de forma automática los **nuevos planes móviles Smart y Ultra** a sus clientes, basándose en su comportamiento de uso. A través de modelos de clasificación supervisada, se predice si un cliente debería cambiarse a uno de estos planes.

---

## 🎯 Objetivos del Proyecto

- 🔍 Analizar características de clientes actuales y su consumo de servicios.
- 🤖 Entrenar modelos de machine learning para predecir la elección óptima de plan.
- 🧪 Evaluar el rendimiento de los modelos y seleccionar el más preciso para producción.

---

## 🛠️ Herramientas y Tecnologías

- Python 🐍  
- Pandas & NumPy 📋  
- Scikit-learn 🔍  
- Matplotlib 📈  

---

## 📌 Flujo de Trabajo

1. **Preprocesamiento de Datos**
   - Limpieza de datos y codificación de variables categóricas.
   - Análisis exploratorio de datos para comprender el comportamiento del cliente.

2. **Entrenamiento de Modelos**
   - Modelos utilizados:
     - 🌲 `RandomForestClassifier`
     - 🌳 `DecisionTreeClassifier`
     - 📈 `LogisticRegression`
   - Ajuste de hiperparámetros mediante validación cruzada.

3. **Evaluación**
   - Comparación de precisión (`accuracy`) en conjuntos de entrenamiento, validación y prueba.
   - Selección del modelo con mejor desempeño general.

---

## 📈 Resultados

- ✅ El modelo **RandomForestClassifier** obtuvo la mejor precisión con un valor de **0.8192** en el conjunto de prueba.
- 🔍 Se observó un rendimiento equilibrado en entrenamiento y validación, mostrando buena generalización.
- 🎯 El modelo final puede integrarse en el sistema de atención al cliente para **recomendar automáticamente el plan óptimo**.

---

## 🧠 Conclusiones

Este sistema de recomendación automatizado permite a Megaline mejorar su oferta personalizada, aumentar la satisfacción del cliente y optimizar sus procesos comerciales. El uso de modelos de clasificación se demuestra eficaz para tareas de segmentación y recomendaciones de productos.

---

📬 **¿Comentarios o ideas?** ¡Estoy abierto a sugerencias y mejoras!

