<h1 align="center">📊 Telecom X - Análisis de Evasión de Clientes (Churn) 📈</h1>

<p align="center">
<a href="#status"><img src="https://img.shields.io/badge/status-completed-yellow"></a>
<a href="#release-date"><img src="https://img.shields.io/badge/release_date-junio-blue"></a>
<a href="#python"><img src="https://img.shields.io/badge/python-purple"></a>
</a>
</p>

---

## 📋 Descripción del proyecto
Este proyecto realiza un análisis exploratorio detallado del comportamiento de los clientes de la empresa **Telecom X** con el fin de identificar patrones que expliquen la evasión (churn) y proponer estrategias para su reducción.

El presente proyecto forma parte del curso de Data Science del Programa ONE (Oracle Next Education) de Oracle y Alura Latam.

## 🧠 Objetivo

Analizar los datos de clientes de Telecom X para:

- Entender las características de los clientes que abandonan.
- Identificar correlaciones y patrones clave.
- Proponer recomendaciones para reducir la tasa de churn.
  
## 📁 Estructura del proyecto


`📂Challenge_TelecomX/`

`├── 📄Challenge_TelecomX_LATAM.ipynb` – Notebook principal con todo el análisis.

`├── 📄TelecomX_Data.json` – Fuente de datos original

`└── 📄README.md` – Descripción del proyecto

## 🛠️ Herramientas utilizadas

- **Python:** Lenguaje de programacion para el análisis de datos.
- **Google Colab / Jupyter Notebook:** Entorno de ejecución
- **Pandas** para manipulación de datos.
- **Seaborn / Matplotlib / Plotly** para visualizaciones.
- **Requests** para carga de datos remotos (JSON desde GitHub).

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/RubiDiana/Challenge_TelecomX.git
cd Challenge_TelecomX
```

2. Ejecuta el notebook:
   
    Puedes abrir y ejecutar el archivo .ipynb en:
    - Google Colab
    - Jupyter Notebook
    - VSCode (con extensión de Python)

## 🗂️ Estructura del Análisis

1. Extracción de Datos

    - Carga desde archivo JSON alojado en GitHub.

2. Transformación y Limpieza

    - Normalización de datos anidados.
    - Manejo de valores nulos y duplicados.
    - Renombramiento y recodificación de columnas.

3. Análisis Exploratorio de Datos (EDA)

    - Distribución del churn.
    - Análisis por género, tipo de contrato, método de pago, tipo de servicio, etc.
    - Correlación entre variables numéricas y abandono.

4. Visualizaciones

    - Barras, pastel, línea, cajas, dispersión, y heatmaps con matplotlib, seaborn y plotly.

5. Conclusiones & Recomendaciones
    - Insights clave y propuestas para la retención de clientes.

## ⚠️ Posibles problemas y soluciones

| Problema                         | Solución sugerida                                                                     |
|----------------------------------|---------------------------------------------------------------------------------------|
| Error en conexión a datos        | Verifica la URL o utiliza el archivo que se adjunta `TelecomX_Data.json`             |
| Gráficos no aparecen             | Ejecuta todas las celdas en orden sin omitir ninguna (Entorno de ejecución --> Ejecutar todas).  |

## 👤 Autor
- Github: [@RubiDiana](https://github.com/RubiDiana)
