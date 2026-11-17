# Predicción de enfermedad cardíaca

Proyecto de práctica de aprendizaje supervisado con scikit-learn: predecir si un paciente tiene enfermedad cardíaca (`HeartDisease`) a partir de datos clínicos y de una prueba de esfuerzo.

## Dataset

[Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) (fedesoriano, Kaggle, licencia ODbL-1.0). Tiene 918 pacientes y 11 variables. Combina 5 bases del [UCI Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease): Cleveland, Hungría, Suiza, Long Beach VA y Statlog.

## Cómo ejecutarlo

Requiere [uv](https://docs.astral.sh/uv/) y Python ≥ 3.12.

```bash
uv sync
```

Abre los notebooks de `notebooks/` en Positron o VS Code con el intérprete del `.venv` del proyecto.

## Estructura

```
data/heart.csv     # dataset original
notebooks/         # análisis y modelos
reports/figures/   # gráficos generados
src/               # código reutilizable
```
