# MorosidadImpositiva
Este repositorio contiene el código fuente y los scripts utilizados para el desarrollo de la tesis de maestría en Ciencia de Datos titulada "Predicción de Morosidad Impositiva utilizando Modelos Predictivos y Técnicas de Machine Learning" 

El objetivo principal de este proyecto es construir modelos predictivos que permitan identificar la probabilidad de morosidad en el pago de impuestos por parte de contribuyentes, utilizando datos históricos y técnicas avanzadas de aprendizaje automático. La tesis aborda todo el ciclo de desarrollo, desde la preparación de los datos hasta la evaluación de los modelos, y se enfoca en la aplicación práctica de métodos como regresión logística, árboles de decisión, bosques aleatorios y redes neuronales, entre otros.


## Contenido del Repositorio

El repositorio está estructurado de la siguiente manera:

1. **`data_preparation/`**  
   Contiene scripts para la limpieza, preprocesamiento y análisis exploratorio de datos (EDA).  
   - Limpieza y normalización de datos.  
   - Manejo de valores nulos y outliers.  
   - Análisis exploratorio y visualización de patrones de morosidad.

2. **`models/`**  
   Implementaciones de los modelos predictivos utilizados en la tesis.  
   - Scripts para entrenar y validar modelos de machine learning.  
   - Comparación de métricas de evaluación (precisión, recall, F1-score, AUC-ROC).  
   - Ajuste de hiperparámetros y selección del mejor modelo.

3. **`balancing_techniques/`**  
   Técnicas de balanceo aplicadas para manejar el desbalanceo en la variable objetivo (morosidad).  
   - Submuestreo, sobremuestreo (SMOTE) y combinaciones.  

4. **`evaluation/`**  
   Evaluación y análisis del rendimiento de los modelos:  
   - Métricas de desempeño.  
   - Curvas ROC, matrices de confusión y otras visualizaciones.  

5. **`visualizations/`**  
   Scripts para la generación de gráficos y visualizaciones utilizados en el reporte final de la tesis.  

6. **`notebooks/`**  
   Notebooks de Jupyter que integran el flujo completo de análisis, desde la preparación de los datos hasta la evaluación del mejor modelo.

7. **`utils/`**  
   Funciones auxiliares y utilitarios reutilizables que se emplean en múltiples scripts.

8. **`reports/`**  
   Plantillas o ejemplos de los resultados generados, como gráficos, tablas y análisis.

## Requisitos y Dependencias

Para ejecutar los scripts de este repositorio, es necesario instalar las siguientes dependencias:

- Python 3.8 o superior.  
- Librerías principales: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `imbalanced-learn`, `xgboost`, entre otras.  

Las dependencias completas se pueden encontrar en el archivo [`requirements.txt`](requirements.txt).

## Cómo Usar Este Repositorio

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/nombre_repositorio.git
   ```

2. Instalar las dependencias:  
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutar los scripts en el orden sugerido en la tesis o en el archivo `README`.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [`LICENSE`](LICENSE) para más detalles.

## Contacto

Para consultas sobre el proyecto, puedes contactarme a través de:  
- **Email**: tu_correo@ejemplo.com  
- **LinkedIn**: [Tu Perfil](https://www.linkedin.com/in/tu_usuario)  

---

Este texto se puede ajustar según el contenido real y las necesidades de tu repositorio. ¿Te gustaría que profundice en alguna sección o agregue algún detalle adicional?
