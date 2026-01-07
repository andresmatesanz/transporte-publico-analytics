# 🚌 Análisis y Predicción de Demanda de Transporte Público – EMT Madrid (Python, Pandas, scikit-learn)

Este proyecto analiza la **demanda diaria de viajeros en las líneas de autobús de EMT Madrid** durante 2025 y propone un **modelo predictivo sencillo** para anticipar picos de demanda y apoyar la planificación de recursos.

El objetivo es practicar **Data Analytics, visualización de datos y Machine Learning ligero**, aplicando técnicas que podrían ser útiles en un entorno real de planificación de transporte.

---

## 📦 Dataset

- **Fuente**: [EMT Madrid – Portal de Datos Abiertos](https://datos.madrid.es/portal/site/egob)  
- **Formato**: CSV  
- **Contenido**:  
  - `Fecha`: día de medición  
  - `Línea`: código interno de EMT  
  - `TotalViajeros`: número de viajeros  
- **Actualización**: datos consolidados y actualizados a mes vencido  
- **Autor / Mantenimiento**: Subdirección de Estrategia, EMT Madrid

---

## 🎯 Objetivos del proyecto

1. 🔍 **Exploración de los datos**: estructura, tipos de columnas, valores nulos y resumen estadístico.  
2. 🧹 **Limpieza y transformación**: formateo de fechas, manejo de valores nulos, agregaciones por línea y mes.  
3. 📊 **Visualizaciones**: evolución diaria/mensual de viajeros, líneas más concurridas, patrones estacionales y de fin de semana.  
4. 🤖 **Modelado predictivo** (opcional pero recomendado):  
   - Predicción de demanda diaria por línea con **Regresión Lineal o Random Forest**  
   - Evaluación simple del modelo (RMSE, MAE)  
5. 🚀 **Extensiones futuras**:  
   - Integración de otros años de datos para series temporales más robustas  
   - Dashboard interactivo con Plotly, Power BI o Looker Studio  
   - Análisis de correlación con eventos, festivos y clima

---

## 🗂️ Estructura del proyecto

```text
transporte-publico-analytics/
├── data/
│ ├── raw/
│ │ └── DemandaDiaLinea2025.csv
│ └── processed/
├── notebooks/
│ ├── 01_exploracion.ipynb
│ └── 02_modelado.ipynb
├── scripts/
│ └── pipeline.py
├── outputs/
│ ├── graficos/
│ └── predicciones.csv
├── README.md
└── requirements.txt
```

---