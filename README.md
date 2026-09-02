# Predicción de Churn con Árbol de Decisión (implementación manual)
## Archivos

- **`decision_tree.py`**
  Implementación manual de un árbol de decisión (con entropía y
  ganancia de información) Incluye una autoprueba con
  el dataset "Play Tennis" visto en clase, que corre solo con:
  ```
  python decision_tree.py
  ```

- **`WA_Fn-UseC_-Telco-Customer-Churn.csv`**
  Dataset público Telco Customer Churn (7,043 clientes, 21 columnas), usado
  para entrenar y probar el árbol.

- **`telco_churn_analysis.ipynb`**
  Notebook con el análisis completo: carga y limpieza de datos, EDA,
  entrenamiento del árbol (importando `decision_tree.py`), visualización
  gráfica del árbol, matriz de confusión, métricas de evaluación, y
  comparación de resultados contra `scikit-learn`.

- **`reporte_churn.docx`**
  Reporte con los resultados: dataset usado, metodología, matriz de
  confusión y métricas justificadas, comparación contra scikit-learn, y
  análisis/conclusión del desempeño obtenido.

