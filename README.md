# Proyecto de Reducción de Dimensionalidad con PCA  
### Ciencias de Datos para la Economía  

---

## **Descripción del Proyecto**

Este proyecto tiene como objetivo aplicar **análisis de componentes principales (PCA)** para reducir la dimensionalidad de un conjunto de datos relacionado con las características socioeconómicas y de salud de individuos. El dataset incluye variables como ingresos, educación, edad, entre otros factores.

El PCA permite simplificar la estructura de los datos al conservar la mayor parte de la información original en menos dimensiones, facilitando la visualización y el análisis.

---

## **Estructura del Proyecto**

1. **Análisis Exploratorio de Datos (EDA):**
   - Carga y limpieza del dataset.
   - Transformación de variables categóricas a formato numérico.
   - Análisis descriptivo y matriz de correlación para identificar relaciones lineales.

2. **Preparación de los datos:**
   - Selección de variables numéricas relevantes.
   - Aplicación de escalamiento con `StandardScaler` para garantizar igualdad de importancia entre variables.

3. **Aplicación del PCA:**
   - Reducción de dimensionalidad a **2 componentes principales**.
   - Análisis de la varianza explicada por cada componente.
   - Visualización gráfica de los componentes principales (PC1 y PC2).

4. **Explicación de los Supuestos del PCA:**
   - Linealidad de las variables.
   - Uso exclusivo de datos numéricos.
   - Captura de máxima varianza.
   - Independencia (ortogonalidad) de los componentes principales.
   - Escalamiento previo de las variables.

---

## **Requisitos y Librerías Utilizadas**

Este proyecto fue desarrollado en **Python**, utilizando las siguientes librerías:

- `pandas` - Manipulación y análisis de datos.
- `numpy` - Operaciones numéricas.
- `matplotlib` y `seaborn` - Visualización de datos.
- `sklearn` - Implementación del algoritmo PCA y escalamiento de datos.

---

## **Resultados**

1. **Matriz de Correlación:**
   Se identificaron relaciones lineales entre variables como `estatura` y `peso`, lo cual valida la aplicabilidad del PCA.

2. **Varianza Explicada:**
   Los dos primeros componentes principales capturan aproximadamente **44.24%** de la varianza total de los datos.

3. **Gráfica de PCA:**
   La visualización en 2D permite observar la distribución de los datos en el espacio reducido definido por los componentes PC1 y PC2.

---

## **Ejecución del Proyecto**

1. Clona el repositorio:
   ```bash
   git https://github.com/lmeneses7/Prediccion_Ingresos
   cd Prediccion_Ingresos
