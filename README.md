# 🧠 Proyecto de Análisis de Datos - [Título del Proyecto]

📍 **Objetivo**: [Breve descripción del problema de negocio o desafío abordado]  
📅 **Fecha de entrega**: [Fecha]  
👥 **Autores**: [Nombre Apellido] – [Rol]  
🏫 **Bootcamp**: [Nombre del bootcamp o institución]

---

## 🔁 Proceso de Análisis

> Basado en el enfoque CRISP-DM

### 1. 📚 Comprensión del negocio

- Definición del problema
- Objetivos del análisis
- KPIs relevantes

📌 *Ejemplo:* Identificar qué factores impactan la cancelación de suscripciones en una app de streaming.

---

### 2. 🧾 Comprensión de los datos

- Exploración inicial del dataset
- Identificación de columnas clave
- Revisión de tipos de datos

📁 Dataset: `data/dataset_original.csv`  
📊 Descripción general:  
| Variable        | Tipo     | Descripción                       |
|----------------|----------|-----------------------------------|
| `user_id`       | int      | Identificador del usuario         |
| `subscription`  | string   | Tipo de suscripción               |
| `cancel_date`   | date     | Fecha de cancelación (si aplica)  |

---

### 3. 🧹 Preparación de los datos

- Limpieza de datos nulos y duplicados
- Creación de variables derivadas
- Normalización y codificación de variables

📄 Código: `scripts/01_preprocesamiento.py`  
📂 Datos limpios: `data/dataset_limpio.csv`

---

### 4. 📊 Análisis exploratorio (EDA)

- Visualizaciones clave
- Correlaciones
- Segmentaciones

📓 Notebook: `notebooks/02_eda.ipynb`  
📈 Ejemplos de gráficos:

![Distribución](img/distribucion_variable.png)
![Heatmap](img/heatmap_correlaciones.png)

---

### 5. 📈 Modelado (opcional)

- Aplicación de modelo predictivo (si aplica)
- Validación del modelo
- Métricas: accuracy, F1, ROC-AUC

📓 Notebook: `notebooks/03_modelado.ipynb`

---

### 6. 📢 Comunicación de resultados

- Principales hallazgos
- Recomendaciones de negocio
- Visualizaciones finales

📄 Informe final: [resumen.pdf](./resumen.pdf)  
📊 Dashboard interactivo: [Ver en Power BI](https://...)

---

## 📂 Estructura del repositorio

