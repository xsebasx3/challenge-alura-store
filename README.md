
# 📈 Análisis de Desempeño - Alura Store

## 🎯 Propósito del Análisis
Este proyecto tiene como objetivo identificar la tienda de menor rendimiento en la cadena Alura Store mediante:
- Evaluación comparativa de métricas financieras
- Análisis de satisfacción del cliente
- Optimización de costos logísticos
- Segmentación geográfica de ventas

Los resultados permitirán al dueño tomar decisiones estratégicas basadas en datos.

## 📂 Estructura del Proyecto
challenge-alura-store/
├── AluraStoreLatam.ipynb
├── base-de-datos-challenge1-latam/ 
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
├── README.md 
└── LICENSE 


## 📊 Insights Clave (Ejemplos Visuales)

### 1. Facturación por Tienda
![Facturación](https://via.placeholder.com/600x400/FF6B6B/FFFFFF?text=Tienda+3+con+53%+menos+ingresos)

**Hallazgo**: La Tienda 3 genera $150k vs $300k promedio

### 2. Satisfacción del Cliente
![Calificaciones](https://via.placeholder.com/600x400/4ECDC4/FFFFFF?text=Calificación+2.9/5+en+Tienda+3)

**Patrón**: 45% de quejas relacionadas con tiempos de entrega

## 🚀 Ejecución del Proyecto

### Opción 1: Google Colab (Recomendada)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuusuario/repositorio/blob/main/notebooks/Analisis_Principal.ipynb)

1. Haz clic en el botón superior
2. Conéctate a un entorno de ejecución
3. Ejecuta todas las celdas secuencialmente (Runtime → Run all)

### Opción 2: Ejecución Local
```bash
git clone https://github.com/tuusuario/alura-store-analysis.git
cd alura-store-analysis
pip install -r requirements.txt  # pandas matplotlib seaborn
jupyter notebook notebooks/Analisis_Principal.ipynb

