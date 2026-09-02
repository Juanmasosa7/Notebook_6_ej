# Notebook 6: Introducción a Pandas

## Programa: Ingenias+ en Data Science

### Descripción General

Este notebook corresponde a la **Clase 5** del programa Ingenias+ en Data Science, donde se presenta una introducción completa a **Pandas**, una de las librerías fundamentales para el análisis y manipulación de datos en Python.

### Objetivos de Aprendizaje

- Comprender las estructuras de datos principales de Pandas: `Series` y `DataFrame`
- Aprender a cargar datasets en formato CSV utilizando `pd.read_csv()`
- Dominar las técnicas de exploración inicial de datos
- Aplicar filtros y selecciones condicionales sobre DataFrames
- Identificar y manejar valores faltantes
- Calcular estadísticas descriptivas básicas
- Utilizar funciones de agrupación y transformación de datos

### Dataset Utilizado

**Archivo**: `StudentsPerformance.csv`

| Descripción | Valor |
|-------------|-------|
| Registros | 1000 |
| Columnas | 9 |
| Variables | gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score |

El dataset contiene información sobre el rendimiento académico de estudiantes, incluyendo variables demográficas y sus puntuaciones en matemáticas, lectura y escritura.

### Librerías Utilizadas

| Librería | Propósito |
|----------|-----------|
| `pandas` | Manipulación y análisis de datos estructurados |
| `numpy` | Computación numérica (dependencia de pandas) |
| `matplotlib` | Generación de gráficos y visualizaciones |
| `seaborn` | Visualización estadística de datos |

### Contenido del Notebook

1. **Introducción a Pandas** - Conceptos básicos y documentación
2. **Creación de Series y DataFrames** - Estructuras de datos fundamentales
3. **Lectura de archivos CSV** - Carga de datasets externos
4. **Exploración de datos** - `.shape`, `.columns`, `.head()`, `.tail()`, `.dtypes`
5. **Acceso a datos** - Indexación por columna, `.iloc[]`, `.loc[]`
6. **Filtrado condicional** - Máscaras booleanas y selección avanzada
7. **Valores faltantes** - Detección con `.isnull()` y manejo con `.dropna()`, `.fillna()`
8. **Estadísticas descriptivas** - `.describe()`, `.mean()`, `.min()`, `.max()`, `.median()`, `.std()`
9. **Funciones adicionales** - `.groupby()`, `.rename()`, `.astype()`, `.unique()`, `.value_counts()`

### Entorno de Ejecución

- **Python**: 3.14.7
- **Kernel**: .venv (virtual environment)
- **Plataforma**: Jupyter Notebook

### Cómo Ejecutar

1. Asegurarse de tener Python instalado
2. Crear y activar el entorno virtual:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   ```
3. Instalar las dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Ejecutar el notebook `Notebook_6_actualizado.ipynb` en Jupyter

### Notas Adicionales

- El dataset `StudentsPerformance.csv` debe encontrarse en el mismo directorio que el notebook
- El notebook incluye ejercicios prácticos con sus respectivas respuestas
- Se recomienda consultar la [documentación oficial de Pandas](https://pandas.pydata.org/pandas-docs/stable/) para profundizar en cada función utilizada
