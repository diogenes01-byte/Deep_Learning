# 🧠 Atracciones que enomoran : cómo un modelo aprende que le gusta a los visitantes

![Python](https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red?style=for-the-badge&logo=pytorch)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Neural%20Networks-blue?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Completado-green?style=for-the-badge)

---

## 📌 Situación (Problema de negocio)

En el sector de marketing digital basado en localización, las empresas necesitan decidir:

- Qué puntos de interés (POIs) generan mayor tráfico de usuarios  
- Dónde es más rentable colocar publicidad física o digital  
- Cómo predecir el rendimiento de ubicaciones turísticas antes de invertir  

Sin un enfoque basado en datos, estas decisiones suelen depender de intuición o análisis descriptivos limitados, lo que incrementa el riesgo de inversión ineficiente.

---

## 🎯 Tarea (Objetivo del proyecto)

Desarrollar un modelo de Deep Learning capaz de:

- Predecir el nivel de engagement o popularidad de un POI  
- Identificar ubicaciones con alto potencial publicitario  
- Combinar información visual y metadatos geográficos  
- Proporcionar una base analítica para decisiones de marketing basadas en datos  

---

## ⚙️ Acción (Solución implementada)

Se diseñó un pipeline de aprendizaje profundo utilizando:

- **PyTorch** como framework principal de modelado  
- Arquitectura híbrida:
  - CNNs para extracción de patrones visuales en imágenes de POIs  
  - Redes fully-connected para metadatos (ubicación, categoría, tags, etc.)  
- Procesamiento y preparación de datos con Python (Pandas, NumPy)  
- Entrenamiento supervisado con optimización de hiperparámetros  
- Evaluación mediante métricas de clasificación de engagement  

El flujo completo incluye:

- Carga y preprocesamiento de imágenes y metadatos  
- Construcción de dataset multimodal  
- Diseño y entrenamiento del modelo híbrido  
- Validación y análisis de resultados  

---

## 📊 Resultado

El modelo permite:

- Estimar qué POIs tienen mayor probabilidad de generar alto engagement  
- Apoyar decisiones de ubicación de campañas publicitarias  
- Reducir la dependencia de análisis manual o heurístico  
- Introducir un enfoque de inteligencia artificial en la planificación de marketing basado en localización  

---

## 🛠️ Tecnologías utilizadas

- Python (NumPy, Pandas)  
- PyTorch (CNNs, redes fully-connected)  
- Torchvision  
- Matplotlib / Seaborn para análisis  
- Jupyter Notebook  

---

## 🚀 Uso del repositorio

1. Clonar el repositorio  
2. Instalar dependencias necesarias (PyTorch y librerías asociadas)  
3. Ejecutar notebooks de preparación de datos  
4. Entrenar el modelo o cargar checkpoints preentrenados  
5. Evaluar resultados y predicciones sobre POIs  

