
# Modelo de Regresión en Salud

Este repositorio contiene un análisis de regresión lineal para predecir una variable objetivo relacionada con la salud, basado en variables independientes como Edad, Índice de Masa Corporal (IMC), Frecuencia de Ejercicio y más.

## Estructura del Proyecto

```
health_regression/
├── data/
│   └── synthetic_health_data.csv      # Conjunto de datos utilizado para el análisis
├── notebooks/
│   └── regression_salud.ipynb         # Notebook Jupyter con el análisis completo
├── src/
│   └── regression_script.py           # Script en Python para ejecutar el modelo de regresión
├── results/
│   └── predictions_vs_actual.png      # Visualización de predicciones vs valores reales
├── README.md                          # Documentación del proyecto
└── requirements.txt                   # Dependencias de Python
```

## Descripción General

El proyecto demuestra un modelo de regresión lineal para predecir resultados en salud usando las siguientes características:
- Edad
- Índice de Masa Corporal (IMC)
- Frecuencia de Ejercicio
- Calidad de la Dieta
- Horas de Sueño
- Estado de Fumador
- Consumo de Alcohol

### Resultados
- **Error Cuadrático Medio (MSE):** 37.24
- **Coeficiente de Determinación (R²):** 0.81

El modelo sugiere que variables como las Horas de Sueño y la Frecuencia de Ejercicio tienen impactos positivos, mientras que el Tabaquismo y el Consumo de Alcohol tienen impactos negativos.

### Herramientas Utilizadas
- Python
- pandas
- scikit-learn
- matplotlib

## Cómo Usar

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/modelo-prediccion-salud.git
   cd modelo-prediccion-salud
   ```

2. **Instalar dependencias**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar el análisis**:
   - Para ejecutar el modelo de regresión, utiliza:
     ```bash
     python src/regression_script.py
     ```
   - Alternativamente, explora el notebook interactivo en `notebooks/regression_salud.ipynb`.

4. **Conjunto de datos**:
   - El conjunto de datos `synthetic_health_data.csv` se encuentra en la carpeta `data/`.

## Visualización de Resultados

![Predicciones vs Valores Reales](results/predictions_vs_actual.png)

---

## Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).
