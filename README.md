# 📡 Análisis de Evasión de Clientes - Telecom X

Este proyecto forma parte del desafío de Data Science de Alura Cursos. El objetivo es identificar los factores principales que influyen en la pérdida de clientes (Churn) y proponer estrategias de retención.

## 🚀 Proceso Realizado (ETL)

1. **Extracción:** Carga y normalización de datos desde un formato JSON complejo.
2. **Transformación:** - Limpieza de nombres de columnas.
   - Conversión de tipos de datos (Strings a Floats para cargos financieros).
   - Encoding de variables categóricas (Yes/No a 1/0).
   - Tratamiento de valores nulos en clientes nuevos.
3. **Carga y Análisis:** Generación de un dataset limpio y análisis estadístico de grupos de riesgo.

## 📊 Principales Insights
- **Contratos Críticos:** Los clientes con contratos mensuales tienen una tasa de fuga 4 veces mayor que los contratos anuales.
- **Servicios:** La fibra óptica presenta un punto de dolor, posiblemente por la relación costo-beneficio.
- **Finanzas:** El promedio de cargos mensuales de los clientes que se van es superior al de los que permanecen, sugiriendo una sensibilidad al precio.

## 🛠️ Tecnologías utilizadas
- Python
- Pandas & Numpy
- Matplotlib & Seaborn
- Google Colab
