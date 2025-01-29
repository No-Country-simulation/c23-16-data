# 🏦 Home Credit Default Risk

[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)  [![Pandas](https://img.shields.io/badge/Pandas-1.3+-green)](https://pandas.pydata.org/)  [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24+-yellow)](https://scikit-learn.org/)  

Este repositorio contiene el código y los recursos para analizar el riesgo de incumplimiento de crédito en el contexto de Home Credit. El proyecto se basa en la exploración, limpieza y modelado de datos para predecir la probabilidad de que un cliente incumpla un préstamo.

---

## 🌟 Objetivo del Proyecto
El objetivo es desarrollar un modelo de machine learning que pueda predecir si un solicitante de crédito tendrá dificultades para pagar su préstamo en base a su perfil financiero e histórico de crédito.

---

## 📂 Estructura del Proyecto

```plaintext
home-credit-default-risk/
├── data/                   # Conjunto de datos
├── notebooks/              # Jupyter notebooks con análisis exploratorio y modelado
├── scripts/                # Scripts Python para preprocesamiento y entrenamiento
├── models/                 # Modelos entrenados y sus pesos
├── requirements.txt        # Dependencias del proyecto
├── README.md               # Documentación del repositorio
└── config.yaml             # Configuración del pipeline de datos
```

---

## 🚀 Instalación y Configuración

### 1️⃣ Clonar el Repositorio
Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/No-Country-simulation/c23-16-data.git
cd c23-16-data
```

### 2️⃣ Crear un Entorno Virtual
Crea y activa un entorno virtual para mantener las dependencias aisladas:

```bash
python -m venv .venv  # Crea el entorno virtual
source .venv/bin/activate  # Activa el entorno en Mac/Linux
.venv\Scripts\activate  # Activa el entorno en Windows
```

### 3️⃣ Instalar Dependencias
Asegúrate de tener Python 3.9+ instalado y luego ejecuta:

```bash
pip install -r requirements.txt
```

---

## 📊 Exploración de Datos

El conjunto de datos contiene información sobre solicitantes de crédito, como:
- 
- 
- 
- 

Se han aplicado técnicas de limpieza de datos y visualización para entender la relación entre las variables y el riesgo de incumplimiento.

---

## 🤖 Modelado y Evaluación

Se han probado diferentes modelos de machine learning, incluyendo:
- **Regresión Logística**
- **Random Forest**

Las métricas utilizadas para evaluar el rendimiento del modelo incluyen:
- **Precisión (Accuracy)**
- **ROC-AUC Score**
- **F1-Score**

---

## 📌 Uso del Modelo

Para hacer predicciones con el modelo entrenado:

```python
import pickle
import pandas as pd

# Cargar el modelo
with open('models/final_model.pkl', 'rb') as file:
    model = pickle.load(file)

# Cargar nuevos datos
new_data = pd.read_csv('data/new_applicants.csv')

# Hacer predicciones
predictions = model.predict(new_data)
print(predictions)
```

---

## 📈 Resultados y Conclusiones


---

## 📌 Tecnologías Utilizadas

- **Lenguaje:** Python
- **Análisis de Datos:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Manejo de Modelos:** Pickle

---

## 📞 Contacto

Si tienes alguna consulta o sugerencia, puedes contactar a los miembros del equipo:

- **[Joseph Arroyo]** - [GitHub/LinkedIn]
- **[Franco Iribarne]** - [GitHub/LinkedIn]
- **[Camila Breide]** - [GitHub/LinkedIn]
- **[Kelly Saltos]** - [GitHub/LinkedIn]


¡Esperamos tu feedback y contribuciones! 🚀


## 📜 Licencia
Este proyecto es de libre acceso. Puedes usarlo, modificarlo y compartirlo libremente.

