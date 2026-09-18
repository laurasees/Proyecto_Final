# Proyecto_Final
Análisis de Ventas y Logística de E-Commerce

Markdown
# 📊 Análisis de Ventas y Logística E-Commerce: Proyecto Final

## 📖 Descripción del Proyecto
Este proyecto realiza un análisis integral de datos transaccionales de e-commerce a partir de un conjunto unificado de 128.975 registros (Amazon Sales Report y P&L). El objetivo principal es evaluar el rendimiento comercial, la salud de las operaciones logísticas y el comportamiento de las ventas por categoría para optimizar la toma de decisiones estratégicas.

Para llevar a cabo el análisis se empleó un enfoque mixto:
* **Procesamiento de datos y ETL:** Scripts de Python para la limpieza, imputación de valores nulos, estandarización y agrupación lógica de estados logísticos.
* **Exploración estadística (EDA):** Identificación de métricas globales de facturación, volumen de unidades, ticket medio y tasas de cancelación.
* **Visualización interactiva:** Diseño de un Dashboard en Excel estructurado en capas (Backend/Frontend) con tarjetas de KPIs y segmentadores dinámicos.

---

## 🗂️ Estructura del Proyecto


├── data/
│   ├── raw/                       # Archivos originales de Amazon Sales Report y P&L
│   └── processed/                 # Dataset limpio y transformado (ecommerce_final_clean.csv)
├── src/
│   ├── 01_eda_y_limpieza.py          # Script de unificación, limpieza y ETL
│   └── 02_analisis_estadistico.py # Script para análisis exploratorio de datos (EDA)
├── docs/
│   └── informe_analissi_pf.pdf        # Informe ejecutivo y técnico con hallazgos
├── results/
│   └── Analisis_ventas_e-commerce.xlsx   # Dashboard interactivo en Excel
└── README.md                      # Descripción general del proyecto

---

## 🛠️ Instalación y Requisitos
Este proyecto utiliza Python 3.9+ para el procesamiento de datos y Microsoft Excel para la capa de visualización interactiva.
Requisitos de Python:
- pandas
- numpy
---

## 📊 Resultados y Conclusiones
1. Se alcanzó un volumen de facturación global de $76.03M con 116.6K unidades vendidas durante el periodo analizado.
2. El valor medio por transacción se situó en $661.35, reflejando compras de volumen con una mediana de 1 unidad por pedido.
3. Se identificó un 14.21% de pedidos cancelados, lo que señala un punto de fricción operativa relevante a revisar en la gestión de inventarios y confirmaciones de orden.
4. Las categorías Set, Kurta y Western Dress representan el principal motor de ingresos del catálogo comercial.

---

## 🔄 Próximos Pasos
Implementar modelos predictivos en Python (Series Temporales / Prophet) para proyectar la demanda de inventario por categoría.
Diseñar estrategias de venta cruzada (cross-selling) y empaquetado para elevar el número promedio de unidades por pedido.
Automatizar la ingesta periódica de datos mediante conectores directos a la API de Amazon Seller Central.

---

## ✒️ Autores y Agradecimientos
Laura Serra - Desarrollo del proyecto, ETL, EDA y Dashboard 
Agradecimientos a la escuela y mentores por la guía en la estructuración de este análisis final.
A la comunidad Open Data de **data.world** y a los contribuidores de **Kaggle** por recopilar y compartir públicamente el dataset de Amazon Sales Report, impulsando el aprendizaje y la democratización del análisis de datos.
