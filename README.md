# Proyecto Final Data Science - Parte III

**Autor:** Juan Martín Santulián  
**Notebook:** `ProyectoParteIII+Santulian.ipynb`  
**Carrera:** Ciencia de Datos  
**Institución:** CoderHouse

## Abstract

Este proyecto tiene como objetivo explorar la relación entre el rendimiento estadístico de los jugadores de la NBA y su participación en el All-Star Game. Mediante el análisis de datos históricos por temporada, se construyó un modelo predictivo capaz de identificar si un jugador fue seleccionado como All-Star a partir de variables cuantitativas que reflejan su desempeño en cancha. Para ello, se aplicaron técnicas de selección de características, modelos de clasificación supervisada y validación estadística. Asimismo, se integró un estudio comparativo clásico entre tres figuras emblemáticas (Michael Jordan, Kobe Bryant y LeBron James) para aportar un marco referencial al análisis. Este enfoque integral busca no solo desarrollar una herramienta predictiva, sino también ofrecer una interpretación coherente y significativa del valor estadístico en el contexto de la élite del baloncesto profesional.

## Objetivo

Predecir si un jugador fue All-Star en una temporada de la NBA utilizando estadísticas por partido. Se aplican técnicas de reducción de dimensionalidad, clasificación supervisada y evaluación del modelo.

## Contenido

- Limpieza y análisis del dataset `per game stats.csv`
- Creación de variable objetivo (All-Star)
- Selección de variables con `SelectKBest`
- Entrenamiento de modelo con `LogisticRegression`
- Balanceo de clases con `SMOTE`
- Métricas de evaluación y matriz de confusión
- Análisis comparativo clásico entre Michael Jordan, Kobe Bryant y LeBron James usando ANOVA y prueba de Tukey

## Librerías usadas

- pandas, numpy, matplotlib, seaborn
- scikit-learn
- imbalanced-learn
- statsmodels

## Resultados

- **Accuracy sin SMOTE:** 95%
- **Accuracy con SMOTE:** mejor cobertura para clase minoritaria
- Variables más importantes: minutos jugados, puntos, tiros libres, asistencias
- Diferencias estadísticamente significativas en el rendimiento ofensivo entre los tres jugadores analizados

## Instrucciones

1. Abrir el notebook `ProyectoParteIII+Santulian.ipynb` en Google Colab.
2. Ejecutar todas las celdas secuencialmente.
3. Instalar dependencias si es necesario:
   !pip install imbalanced-learn
> 🎯 Análisis y predicción de participación en el NBA All-Star Game usando estadísticas por partido, técnicas de machine learning y validación estadística.

Juan Martín Santulián  
Rosario, Santa Fe, Argentina  
2000
