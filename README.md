# Análisis del Desempeño del Modelo de Taxi
Este repositorio contiene el análisis del desempeño de un modelo de clasificación aplicado a datos de taxis para el año 2020. El análisis incluye la comparación del desempeño del modelo a lo largo de los meses del año y la evaluación de cómo varía el F1-score del modelo en función del tiempo.

## Estructura del Repositorio

- `src/`: Carpeta que contiene scripts Python para el procesamiento de datos y la extracción de características.
  - `dataset.py`: Script para cargar y preparar los datos.
  - `features.py`: Script para construir características y comparar distribuciones.


- `00_nyc_taxi_model.ipynb`: Notebook principal para la evaluación del modelo.

- `Modelo/`: Carpeta que contiene el archivo del modelo entrenado.
  - `random_forest.joblib`: Modelo de clasificación guardado.

## Requisitos

Asegúrate de tener instalado Python 3.7 o superior. Los paquetes necesarios están listados en el archivo `requirements.txt`. Puedes instalar todos los paquetes necesarios ejecutando:

```bash
pip install -r requirements.txt
```
## Configuración del Entorno

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio

2. **Instala los requisitos**:
   ```bash
   pip install -r requirements.txt

## Ejecución del Análisis

1. **Carga el Notebook**:
   Abre el notebook `00_nyc_taxi_model.ipynb` en Jupyter Notebook o Google Colab.

2. **Cargar Datos y Modelo**:
   Asegúrate de que los datos estén cargados y el modelo esté disponible en la carpeta `Modelo/`.

3. **Preprocesamiento de Datos**:
   Ejecuta las celdas para cargar los datos mensuales y preprocesarlos. Los datos se cargan usando la función `load_data` del archivo `dataset.py`.

4. **Evaluación del Modelo**:
   Ejecuta las celdas para aplicar el modelo a los datos de cada mes. Calcula el F1-score utilizando el código de ejemplo proporcionado en el notebook.

5. **Análisis de Resultados**:
   Revisa los gráficos generados y las estadísticas para analizar el desempeño del modelo a lo largo del año. El notebook incluye visualizaciones y análisis de tendencia que te ayudarán a entender cómo varía el desempeño del modelo en función del tiempo.
