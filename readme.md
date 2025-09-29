# Student Dropout Synthetic Dataset

## Descripción
Este dataset fue generado de manera sintética para simular el problema de predicción de deserción estudiantil en el primer año universitario. Contiene 500 registros con información demográfica, académica, financiera y una variable objetivo (**Dropout**).

## Variables
- **Age** (int): Edad del estudiante (16–30, con outliers entre 40–80).
- **Gender** (categorical): Male/Female.
- **Origin** (categorical): Urban/Rural.
- **HS_Avg** (float): Promedio de bachillerato (0–5, media aproximada 3.5).
- **Admission_Test** (int): Resultado examen de admisión (200–400).
- **First_Sem_Grades** (float): Promedio primer semestre (0–5, con outliers entre 8–10).
- **Socioeconomic** (categorical): Low/Medium/High.
- **Scholarship** (binary): 1 = tiene beca, 0 = no.
- **Loan** (binary): 1 = tiene préstamo, 0 = no.
- **Aid** (binary): 1 = recibe ayuda financiera, 0 = no.
- **Dropout** (binary): 1 = abandono, 0 = continuó.

## Manejo de Nulos y Outliers
- **Nulos:** Se introdujeron de forma aleatoria en aproximadamente un 5% de los registros en todas las columnas.
- **Outliers:** Se añadieron valores anómalos en la edad (40–80 años) y en las notas del primer semestre (8–10).

## Uso
Este dataset puede usarse para entrenar y evaluar modelos de clasificación supervisada en Machine Learning, específicamente para predecir la deserción estudiantil.  
Se recomienda limpiar los datos (manejo de nulos y outliers) antes de su uso en un modelo.

---
**Autor:**
Mateo Baca