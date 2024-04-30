# Análisis de Admisión Universitaria basado en Puntaje SAT

---

## Requisitos:

- Python 3.x
- Bibliotecas de Python: numpy, pandas, statsmodels, matplotlib, seaborn

---

## Detalles del Análisis:

En este análisis, se examina la relación entre los puntajes SAT y la probabilidad de admisión universitaria utilizando regresión lineal y regresión logística. Los pasos incluyen:

1. **Preparación de Datos:**
   - Se carga un conjunto de datos que contiene información sobre admisiones universitarias, incluyendo los puntajes SAT y la admisión (Sí/No).
   - Las entradas 'No' se reemplazan con 0 y las entradas 'Sí' con 1 para la variable 'Admitted'.

2. **Análisis Exploratorio:**
   - Se visualiza la relación entre los puntajes SAT y la admisión mediante un gráfico de dispersión.

3. **Regresión Lineal:**
   - Se ajusta un modelo de regresión lineal para predecir la admisión en función de los puntajes SAT.
   - Se traza una línea de regresión para visualizar la relación entre los puntajes SAT y la probabilidad de admisión.

4. **Regresión Logística:**
   - Se utiliza la regresión logística para modelar la probabilidad de admisión en función de los puntajes SAT.
   - Se traza una curva logística suave para visualizar la relación entre los puntajes SAT y la probabilidad de admisión.

---

## Resultados:

El análisis revela una relación significativa entre los puntajes SAT y la probabilidad de admisión universitaria. Tanto la regresión lineal como la regresión logística muestran una tendencia creciente en la probabilidad de admisión a medida que aumentan los puntajes SAT. La regresión logística proporciona una representación más adecuada de la relación, ya que modela directamente la probabilidad de admisión como una función logística de los puntajes SAT.

El gráfico muestra una curva suave que ilustra cómo la probabilidad de admisión varía con los puntajes SAT, lo que permite una mejor comprensión de la relación no lineal entre estas variables.

Este análisis podría ser útil para los estudiantes que desean comprender cómo sus puntajes SAT afectan sus posibilidades de ser admitidos en una universidad, así como para los consejeros y administradores universitarios que buscan comprender mejor los factores que influyen en las decisiones de admisión.

