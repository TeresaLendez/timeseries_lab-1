# timeseries_lab
Laboratorio de Series Temporales para Tinámica

## Objetivos
    1. Los participantes obtengan conocimiento práctico de análisis y modelado de series temporales con datos de proyectos reales
    2. Los participantes conozcan y apliquen modelos tradicionales y nuevos de series temporales sabiendo evaluarlos y ajustarlos de manera eficiente
    3. Los participantes puedan relizar propuestas y ofertas al cliente con conocimiento práctico de las dimensiones y necesidades de un proyecto de Forecasting. 


Como cualquier proyecto de Data Science, la creación del modelo empieza por entender los datos, pero dado que tenemos una componente temporal, necesitamos información adicional.
## Fase 1
### Creación y Análisis de Series Temporales
    Creación de Series Temporales
        Elección fuentes
        Elección de Resolución temporal
    Descomposición de Series
        Tendencia
        Estacionalidad
        Ruido
    Análisis de las Series
        Tests (ACF & PACF, ADF, etc…)
        Cross Correlations
    Transformación de Series Temporales
        Logaritmos, Diferencias y Normalizaciones
        Medias Móviles

## Fase 2
### Modelado de Series Temporales
    Entrenamiento y Validación en Series Temporales
      Walkforward Validations
      Métricas de validación (MAE, MAPE, RMSE, MDA)
    Modelos tradicionales 
      ARIMAX (SARIMAX), prophet
      Creación de variables step, impulso y lidiar con outliers
    Modelado de Series Temporales con Redes Neuronales
      LSTM

## Fase 3
### Aplicabilidad de modelos
    Teoría de los mercados eficientes
    Simuladores
      Importancia relativa de variables
      Identificación de varianza base vs variable



## Requierements
    statsmodels == '0.10.1'
    tensorflow == '1.15.0'
    keras == '1.2.0'
