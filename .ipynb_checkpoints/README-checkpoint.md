# 🤖 Proyecto de Clasificación Automática de Noticias

## 📝 Propósito del Proyecto
El presente proyecto tiene como objetivo diseñar e implementar un sistema de clasificación automática de noticias utilizando técnicas avanzadas de Procesamiento de Lenguaje Natural (NLP). A lo largo del desarrollo, se abordarán distintas etapas clave: 

- **Exploración y Preprocesamiento de Datos**: Filtros aplicados a datos de noticias categorizadas en temas como deportes, cultura, economía y justicia.
- **Modelado**: Implementación de modelos de aprendizaje profundo basados en arquitecturas RNN y LSTM.
- **Evaluación Comparativa**: Uso de métricas como precisión y F1-score para determinar el impacto de distintas arquitecturas.

Este proyecto no solo optimiza la clasificación de noticias, sino que también explora su impacto en sistemas de recomendación y análisis de medios.

---

## 📚 Archivos Incluidos

- **Cuadernos**: Notebooks de Jupyter que detallan cada etapa del proyecto.
- **Datos**: Conjunto de datos categorizados en formato CSV y XLSX.
- **Modelos**: Almacena los modelos entrenados en formatos como `.pt` y `.h5`.

---

## 🚀 Instrucciones de Instalación y Ejecución

Para ejecutar este proyecto, sigue los pasos a continuación:

### Paso 1: Clona el repositorio y navega a la carpeta del proyecto
```bash
https://github.com/Jiliar/npl_final_project.git
cd npl_final_project/
```

### Paso 2: Instala las dependencias

Asegúrate de tener instalado **Python 3.10** y ejecuta:
```bash
pip install -r requirements.txt
```

### Paso 3: Ejecuta los notebooks

1. Activa el entorno virtual:
    ```bash
    source venv/bin/activate # En sistemas Unix
    .\venv\Scripts\activate # En Windows
    ```
2. Abre los cuadernos con Jupyter:
    ```bash
    jupyter notebook
    ```

---

## 📦 Dependencias

- `python = "^3.10"`
- `pandas = "^2.2.3"`
- `nltk = "^3.9.1"`
- `scikit-learn = "^1.5.2"`
- `matplotlib = "^3.9.2"`
- `openpyxl = "^3.1.5"`
- `gensim = "^4.3.3"`
- `tensorflow = "^2.18.0"`
- `seaborn = "^0.13.2"`
- `keras-preprocessing = "^1.1.2"`
- `transformers = "^4.47.0"`
- `tf-keras = "^2.18.0"`
- `torch = "^2.5.1"`
- `torchvision = "^0.20.1"`
- `torchaudio = "^2.5.1"`
- `pytorch-transformers = "^1.2.0"`
- `captum = "^0.7.0"`
- `datasets = "^3.1.0"`

---

## 📂 Estructura del Proyecto

### Directorios

- **Cuadernos**: 📓 Contiene notebooks de Jupyter para exploración de datos, preprocesamiento y entrenamiento de modelos.
- **Datos**: 📊 Contiene los conjuntos de datos en formatos como CSV y XLSX.
- **Modelos**: 🤖 Almacena modelos entrenados para futura referencia.

### Archivos

- `Datos/Noticias.xlsx`: Datos principales categorizados en deportes, cultura, economía y justicia.
- `Código/Clasificacion NPL.ipynb`: Notebook de exploración inicial de datos.

---

## 📊 Resultados Esperados

- Precisión y F1-score superiores al 90% para la clasificación de noticias.
- Comparativa entre modelos RNN y LSTM para identificar el más eficiente.

---

## 👥 Autor
- **Jiliar Antonio Silgado Cardona**
