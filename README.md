# 🚀 Proyecto ETL – Food Delivery

Pipeline ETL para una startup de Food Delivery que quiere expandirse en EE. UU.

## 🎯 Objetivo
Limpiar los datos de la competencia, cargarlos en SQLite y responder preguntas de negocio con SQL y gráficos.

## ⚙️ Fases
1. **Extract:** lectura de `restaurants.csv` y los 10 CSV de menús con Pandas.
2. **Transform:** limpieza de precios, split de direcciones, filtros de calidad y cruce (merge) de tablas.
3. **Load:** carga en SQLite (`delivery_insights.db`) con SQLAlchemy.
4. **BI:** consultas SQL y gráficos con Seaborn/Matplotlib.

## 🔍 Preguntas respondidas
- Top 5 ciudades con más restaurantes
- Distribución por rango de precio
- Precio promedio en las 3 ciudades principales
- ¿Más caro = mejor calidad?

## 🛠️ Tecnologías
Python · Pandas · SQLAlchemy · SQLite · Matplotlib · Seaborn · Google Colab
