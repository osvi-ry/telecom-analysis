# ConnectaTel User's Analysis - Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel (empresa de telecomunicaciones).

El dataset `users.csv` y `usage.csv` incluyen 4,000 registros de clientes con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del planes de servicio móvil (llamadas y mensajes) .

## 📂 Contenido del repositorio

- `notebooks/S7-Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[Open In Colab]()]
O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S7-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden, o desde la celda final a través del menú **'Run'** y seleccionando **'Run All Above Selected Cell'**
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir e implementar un pipeline de limpieza reproducible
- Identificar patrones de uso, analizar comportamientos atípicos, distribuciones y outliers, con el fin de optimizar la oferta comercial y experiencia de usuario
- Generar insights comerciales para segmentación de clientes basadas en edad, país y comportamiento de uso
