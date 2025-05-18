# -MastersThesisProject-Prediction-and-Optimization-of-the-Food-Market-in-the-27-EU-Countries-

Descripción del Proyecto
Este proyecto analiza el impacto económico en los precios y la vulnerabilidad alimentaria en los 27 países de la Unión Europea durante el período 2016-2023. Utilizando tecnologías avanzadas del ecosistema SAP (DataSphere y Analytics Cloud) e integrando datos macroeconómicos fiables de Eurostat, se examina la relación entre el índice de precios alimentarios, inflación general, PIB per cápita y tasas de desempleo.
El estudio identifica patrones regionales de inflación alimentaria, cuantifica el impacto desproporcionado en diferentes economías europeas, y desarrolla modelos predictivos para proyectar tendencias futuras. Los resultados se presentan mediante dashboards interactivos que visualizan la aceleración inflacionaria del período 2021-2023, las disparidades regionales entre Europa Oriental y Occidental, y la correlación entre indicadores macroeconómicos y presión en precios alimentarios.
Características Principales

Análisis Temporal: Evolución comparativa entre la media del Índice de Precios Alimentarios y el Índice de Precios al Consumo Armonizado
Mapeo de Disparidades Regionales: Identificación de patrones geográficos en vulnerabilidad alimentaria
Correlación con Indicadores Económicos: Análisis de relación entre PIB per cápita y presión alimentaria
Modelos Predictivos: Implementación de modelos de series temporales para proyectar tendencias futuras
Visualización Interactiva: Dashboards diseñados en SAP Analytics Cloud

Arquitectura del Sistema
El proyecto implementa una arquitectura basada en:

Fuentes de Datos: Eurostat (indicadores macroeconómicos y de precios)
Procesamiento y Modelado: SAP Datasphere
Análisis y Visualización: SAP Analytics Cloud (SAC)

Requisitos

Python 3.8+
Acceso a SAP Datasphere
Acceso a SAP Analytics Cloud
Librerías Python (ver requirements.txt)

Instalación
bash# Clonar el repositorio
git clone https://github.com/su-usuario/mercado-alimentario-ue.git
cd mercado-alimentario-ue

# Instalar dependencias
pip install -r requirements.txt
Uso
Preparación de Datos
python# Ejecutar script de procesamiento de datos
python src/data_preparation.py
Análisis Exploratorio
python# Ejecutar notebook de análisis
jupyter notebook notebooks/exploratory_analysis.ipynb
Modelado Predictivo
python# Entrenar modelos predictivos
python src/train_models.py
Estructura del Proyecto
├── LICENSE
├── README.md
├── data/
│   ├── processed/
│   └── raw/
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   └── model_evaluation.ipynb
├── requirements.txt
├── results/
│   ├── figures/
│   └── models/
└── src/
    ├── __init__.py
    ├── data_preparation.py
    ├── modeling.py
    └── visualization.py
Glosario
ARIMA: Modelo de media móvil integrada autorregresiva. Acrónimo en inglés de Autoregressive Integrated Moving Average.
Prophet: Modelo para la predicción de series temporales desarrollado por Facebook.
Big Data Streaming: Tecnologías y técnicas para el procesamiento continuo de grandes volúmenes de datos en tiempo real.
Apache Kafka: Plataforma distribuida para la transmisión en tiempo real de datos de gran escala.
Apache Spark: Herramienta de análisis distribuido para el procesamiento de datos a gran escala.
MongoDB: Base de datos NoSQL orientada a documentos.
Changepoint: Punto de cambio en una serie temporal donde se produce una variación significativa en la tendencia o estacionalidad.
MAE: Error absoluto medio. Acrónimo en inglés de Mean Absolute Error.
RMSE: Raíz del error cuadrático medio. Acrónimo en inglés de Root Mean Squared Error.
MAPE: Error porcentual absoluto medio. Acrónimo en inglés de Mean Absolute Percentage Error.
CoinGecko API: Interfaz de programación para obtener datos en tiempo real de criptomonedas.
Estacionariedad: Propiedad de una serie temporal en la que sus características estadísticas no cambian con el tiempo.
Dickey-Fuller Aumentada (ADF): Prueba estadística para determinar la estacionariedad de una serie temporal.
TFM: Trabajo Final de Máster.
SAP Datasphere: Plataforma de integración y modelado de datos en la nube, anteriormente conocida como SAP Data Warehouse Cloud.
SAP Analytics Cloud (SAC): Plataforma de análisis de datos y visualización en la nube que permite la creación de dashboards interactivos y modelos predictivos.
HICP_Index: Índice de Precios al Consumo Armonizado. Medida estándar de inflación utilizada en la UE.
Food_Price_Index: Índice que mide la evolución del coste de la canasta alimentaria en cada país.
PIB per cápita (GDP_per_capita): Indicador del nivel de riqueza y desarrollo económico usado para contextualizar la asequibilidad de los alimentos.
Eurostat: Oficina estadística oficial de la Unión Europea, fuente principal de los datos del estudio.
CAGR: Tasa de crecimiento anual compuesto. Acrónimo en inglés de Compound Annual Growth Rate.
Autor
Adrià Vidal de Palol

Máster en Ciencia de Datos
Área de Analytics for Data Streaming
Universitat Oberta de Catalunya (UOC)

Licencia
Este proyecto está licenciado bajo la Licencia MIT - vea el archivo LICENSE para detalles.
