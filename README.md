# Aplicación de Predicción con Machine Learning

Esta es una aplicación web interactiva desarrollada con **Streamlit** para realizar predicciones utilizando un modelo de Machine Learning (XGBoost) entrenado para estimar la ocupación.

## Características
- Interfaz intuitiva para ingresar parámetros de ocupación histórica (`lags`) y fechas.
- Predicciones en tiempo real utilizando un modelo XGBoost.
- Explicabilidad del modelo mediante valores **SHAP** integrados en la interfaz gráfica.

## Requisitos del Sistema

Para ejecutar esta aplicación localmente, asegúrate de tener instalado Python 3.8 o superior y las dependencias necesarias.

### Instalación de dependencias
Instala las librerías requeridas ejecutando:
```bash
pip install -r requirements.txt
```

## Ejecución de la Aplicación Localmente

Para lanzar la aplicación de Streamlit, ejecuta el siguiente comando en tu terminal:
```bash
streamlit run app.py
```

## Despliegue en Streamlit Community Cloud
Puede encontrar la aplicación en la siguiente URL Pública de Streamlit Community

