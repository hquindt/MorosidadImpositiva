# Morosidad Impositiva
Este repositorio contiene el código fuente y los scripts utilizados para el desarrollo de la tesis de maestría en Ciencia de Datos titulada "Predicción de Morosidad Impositiva utilizando Modelos Predictivos y Técnicas de Machine Learning" 

El objetivo principal de este proyecto es construir modelos predictivos que permitan identificar la probabilidad de morosidad en el pago de impuestos por parte de contribuyentes, utilizando datos históricos y técnicas avanzadas de aprendizaje automático. La tesis aborda todo el ciclo de desarrollo, desde la preparación de los datos hasta la evaluación de los modelos, y se enfoca en la aplicación práctica de métodos como regresión logística, árboles de decisión, bosques aleatorios y redes neuronales, entre otros.


## Contenido del Repositorio

Aquí tienes una versión corregida y actualizada del texto para el archivo **README** de tu repositorio en GitHub, basada en los anexos que me proporcionaste:

---

# Códigos fuente - Tesis de Maestría en Ciencia de Datos: Predicción de Morosidad Impositiva

Este repositorio contiene el código fuente y los scripts utilizados para el desarrollo de la tesis de maestría en Ciencia de Datos titulada **"Predicción de Morosidad Impositiva utilizando Modelos Predictivos y Técnicas de Machine Learning"**.

## Descripción del Proyecto

El objetivo principal de este proyecto es construir modelos predictivos que permitan identificar la probabilidad de morosidad en el pago de impuestos por parte de contribuyentes, utilizando datos históricos y técnicas avanzadas de aprendizaje automático. La tesis aborda todo el ciclo de desarrollo, desde la preparación de los datos hasta la validación y evaluación de los modelos.

## Estructura del Repositorio

El repositorio está estructurado de la siguiente manera:

### `data_preparation/`
Contiene scripts para la preparación de los datos, incluyendo:
- Limpieza y normalización de datos.
- Manejo de valores nulos y outliers.
- Análisis exploratorio de datos (EDA) y visualización de patrones de morosidad.  

👉 [Ver Anexo I: Preparación de los Datos](https://github.com/hquindt/MorosidadImpositiva/tree/main/data_preparation)  

---

### `feature_engineering/`
Contiene los scripts utilizados para la generación y transformación de variables (ingeniería de características), como:
- Creación de nuevas variables relevantes.
- Codificación de variables categóricas.
- Escalado y normalización de características.  

👉 [Ver Anexo II: Ingeniería de Características](https://github.com/hquindt/MorosidadImpositiva/tree/main/feature_engineering)  

---

### `balancing_techniques/`
Implementación de técnicas para balancear conjuntos de datos desbalanceados:
- Sobremuestreo (oversampling) y submuestreo (undersampling).
- Uso de SMOTE (Synthetic Minority Oversampling Technique).
- Combinaciones de técnicas.  

👉 [Ver Anexo III: Balanceo de Datos](https://github.com/hquindt/MorosidadImpositiva/tree/main/balancing_techniques)  

---

### `parameter_optimization/`
Scripts relacionados con la optimización de hiperparámetros de los modelos:
- Grid Search y Random Search para ajuste de parámetros.
- Optimización mediante técnicas avanzadas, como búsqueda bayesiana (opcional).  

👉 [Ver Anexo IV: Optimización de Parámetros](https://github.com/hquindt/MorosidadImpositiva/tree/main/parameter_optimization)  

---

### `cross_validation/`
Contiene los scripts utilizados para la validación de modelos predictivos, incluyendo:
- Validación cruzada (K-Fold, Stratified K-Fold, etc.).
- Validación hold-out.  

👉 [Ver Anexo VI: Validación de Modelos](https://github.com/hquindt/MorosidadImpositiva/tree/main/cross_validation)  

---

### `evaluation/`
Scripts para la evaluación de los modelos y análisis de su rendimiento:
- Métricas de evaluación como precisión, recall, F1-score y curva ROC-AUC.
- Generación de matrices de confusión y otros gráficos para interpretar el desempeño de los modelos.  

👉 [Ver Anexo V: Evaluación de Modelos](https://github.com/hquindt/MorosidadImpositiva/tree/main/evaluation)  

---

### `visualizations/`
Contiene scripts para la creación de gráficos y visualizaciones utilizados en la tesis:
- Visualización de datos exploratorios (EDA).
- Representación de métricas y resultados de los modelos.

---

### `notebooks/`
Notebooks de Jupyter que integran el flujo completo de análisis, desde la preparación de los datos hasta la evaluación del modelo final.

---

### `utils/`
Funciones auxiliares reutilizables empleadas en distintos scripts, como:
- Funciones de preprocesamiento.
- Visualizaciones personalizadas.
- Métricas de evaluación adicionales.

---

### `reports/`
Plantillas y ejemplos de reportes generados durante el análisis, incluyendo gráficos, tablas y resúmenes.

---

## Requisitos y Dependencias

Para ejecutar los scripts de este repositorio, es necesario instalar las siguientes dependencias:

- **Python 3.8** o superior.  
- Librerías principales utilizadas:  
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `imbalanced-learn`
  - `xgboost`
  - Otras dependencias especificadas en el archivo [`requirements.txt`](requirements.txt).

### Instalación de dependencias:

```bash
pip install -r requirements.txt
```

---

## Cómo Usar Este Repositorio

1. **Clonar el repositorio:**  
   ```bash
   git clone https://github.com/hquindt/MorosidadImpositiva.git
   cd MorosidadImpositiva
   ```

2. **Instalar las dependencias:**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar los scripts:**  
   Sigue el orden sugerido en los anexos o el flujo de trabajo detallado en la tesis, comenzando por la preparación de datos, pasando por la ingeniería de características, balanceo de datos, optimización de parámetros, validación y finalmente la evaluación.

---

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [`LICENSE`](LICENSE) para más detalles.

---

## Contacto

Para consultas sobre el proyecto, puedes contactarme a través de:  
- **Email:** [hquindt@gmail.com](mailto:hquindt@gmail.com)  
- **LinkedIn:** [https://www.linkedin.com/in/rhquindt/](https://www.linkedin.com/in/rhquindt/)  

---


