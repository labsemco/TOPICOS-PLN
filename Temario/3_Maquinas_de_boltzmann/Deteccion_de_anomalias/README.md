# ECG-Anomaly-Detection-and-Classification

En este repositorio se hace un análisis para la detección de anomalías en señales de ECG y su clasificación utilizando autoencoders. Se entrena un autoencoder para aprender la representación normal de las señales cardíacas y detectar desviaciones que indiquen posibles anomalías. Además, se utiliza la representación aprendida para clasificar diferentes tipos de anomalías.

---

## ✨ Características
- **Preprocesamiento de datos de ECG**: Normalización, segmentación y limpieza de señales.  
- **Entrenamiento de autoencoder**: Modelado de patrones normales en ECG.  
- **Detección de anomalías**: Identificación de latidos irregulares mediante reconstrucción de errores.  
- **Clasificación de anomalías**: Uso del autoencoder para diferenciar tipos de anomalías en ECG.  
- **Visualización de resultados**: Gráficos de señales, reconstrucción y umbrales de anomalía.  

---

## 📌 Tecnologías utilizadas
- **Python** (NumPy, Pandas, Matplotlib)  
- **TensorFlow/Keras** (para el autoencoder)   

---

## 🚀 Uso
1. Cargar y preprocesar los datos de ECG.  
2. Entrenar el autoencoder en datos normales.  
3. Evaluar la detección de anomalías mediante el error de reconstrucción.  
4. Clasificar anomalías con técnicas supervisadas o semi-supervisadas.  

---
