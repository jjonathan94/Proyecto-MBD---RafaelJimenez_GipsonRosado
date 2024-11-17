# Módulo Proyecto MBD

## Nombre de la Maestría: 
Maestría en Inteligencia de Negocios y Ciencia de Datos

## Universidad:
Universidad de las Américas

## Nombre de los Integrantes:
Rafael Jimenez y Gipson Rosado

---

## Problema a Resolver:
**ANÁLISIS DE LOS FACTORES FÍSICOS Y QUÍMICOS QUE IMPACTAN EL CRECIMIENTO DEL CAMARÓN BLANCO MEDIANTE ALGORITMOS DE MACHINE LEARNING**

---

## Modelo Seleccionado:
Modelos de series de tiempo y machine learning

---

## Base de Datos:
Empresa acuícola, nombre: `ProyectoMBD_MST_ML`

---

## Cómo usar el Notebook para replicar los resultados:

1. **Requisitos previos:**
   - Instalar Python 3.8 o superior.
   - Instalar las dependencias requeridas ejecutando:
     ```bash
     pip install -r requirements.txt
     ```
     (El archivo `requirements.txt` debe incluir librerías como `pandas`, `numpy`, `scikit-learn`, `keras`, entre otras).

2. **Archivos incluidos:**
   - `ProyectoMBD_F1_ETL.ipynb`: Notebook para la limpieza y preprocesamiento de los datos.
   - `ProyectoMBD_ML.ipynb`: Notebook que implementa modelos de machine learning.
   - `ProyectoMBD_MST_ML.ipynb`: Notebook que integra modelos de series de tiempo y machine learning.
   - `ProyectoMBD_MST_ML.xlsx`: Base de datos utilizada.

3. **Ejecución de los notebooks:**
   - **Paso 1:** Ejecutar `ProyectoMBD_F1_ETL.ipynb` para preprocesar los datos y generar un archivo limpio.
   - **Paso 2:** Ejecutar `ProyectoMBD_ML.ipynb` para explorar los modelos de machine learning con los datos preprocesados.
   - **Paso 3:** Ejecutar `ProyectoMBD_MST_ML.ipynb` para integrar el análisis de series de tiempo con machine learning.

4. **Resultados esperados:**
   - Identificación de los factores más relevantes que influyen en el crecimiento del camarón blanco.
   - Comparación del desempeño de los modelos, con énfasis en el coeficiente de determinación y precisión.

5. **Notas adicionales:**
   - El modelo con mejor desempeño hasta el momento es Random Forest, con un coeficiente de determinación del 47%.
   - Utiliza las normas APA (7ª edición) en las citas y referencias de este proyecto.

---

### Autoría:
Este proyecto es desarrollado como parte del módulo de la Maestría en Inteligencia de Negocios y Ciencia de Datos en la Universidad de las Américas.
