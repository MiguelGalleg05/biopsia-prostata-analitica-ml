# 🧬 Predicción de Hospitalización en Pacientes con Biopsia de Próstata

Este proyecto se centra en el **análisis de datos de pacientes que se sometieron a biopsias de próstata**, con el objetivo de **predecir la hospitalización** posterior al procedimiento.  
Se utiliza un enfoque de **Machine Learning** para identificar las características más relevantes asociadas a un mayor riesgo de hospitalización.


## 📂 Estructura del Repositorio
- **data/** → contiene los datos utilizados en el análisis (`BBDD_Hospitalización.xlsx`).  
- **notebooks/** → Jupyter Notebooks con el análisis y modelado de datos (`Taller3.ipynb`).  
- **README.md** → documentación del proyecto.  


## 🔎 Contenido del Proyecto
1. **Exploratory Data Analysis (EDA)**  
   - Análisis exploratorio de las características de los pacientes.  
   - Relación de variables clínicas con la hospitalización.  

2. **Preprocesamiento de Datos**  
   - Limpieza de datos.  
   - Conversión de tipos y normalización.  
   - Manejo de valores faltantes.  

3. **Modelado de Datos**  
   - Entrenamiento de un modelo de clasificación con **RandomForestClassifier**.  
   - Ajuste de hiperparámetros y validación.  

4. **Evaluación del Modelo**  
   - Métricas de rendimiento: **precisión, recall, F1-score**.  
   - Interpretación de resultados.  

5. **Conclusiones y Recomendaciones**  
   - Hallazgos sobre factores de riesgo.  
   - Sugerencias para mejorar el modelo y su capacidad predictiva.  


## ⚙️ Instrucciones de Uso
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/MiguelGalleg05/biopsia-prostata-analitica-ml.git
   cd biopsia-prostata-analitica-ml
   
### Instalar dependencias necesarias:
pip install -r requirements.txt

### Ejecutar el notebook principal:
jupyter notebook notebooks/Taller3.ipynb

### 🛠️ Tecnologías utilizadas
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
Jupyter Notebook
Excel (fuente de datos)

### 📣 Autor
Miguel Gallego Álvarez
✉️ miguelgallego2020@gmail.com
