# 📈 Análisis de Desempeño - Alura Store Latam

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/pandas-1.3%2B-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Compatible-brightgreen)

## 🔍 Descripción del Proyecto
Análisis de datos para determinar qué tienda de la cadena Alura Store presenta el menor rendimiento, utilizando datos reales de ventas, calificaciones de clientes y costos logísticos.

## 📋 Estructura del Código (Google Colab)
```python
import pandas as pd

# Importación de datos
url1 = "https://raw.githubusercontent.com/.../tienda_1.csv"
url2 = "https://raw.githubusercontent.com/.../tienda_2.csv" 
url3 = "https://raw.githubusercontent.com/.../tienda_3.csv"
url4 = "https://raw.githubusercontent.com/.../tienda_4.csv"

tiendas = {
    "Tienda 1": pd.read_csv(url1),
    "Tienda 2": pd.read_csv(url2),
    "Tienda 3": pd.read_csv(url3),
    "Tienda 4": pd.read_csv(url4)
}

## 📋 Análisis Realizados

- **Facturación por tienda**: Suma de ingresos totales por ubicación  
- **Ventas por categoría**: Distribución porcentual de productos vendidos  
- **Satisfacción del cliente**: Calificación promedio (escala 1-5)  
- **Productos destacados**:  
  - Top 3 productos más vendidos  
  - 3 productos con menor rotación  
- **Logística**: Costo promedio de envío por tienda  

---

## 🚀 Cómo Ejecutar

1. Abre el notebook en Google Colab:  
   [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/TU_ENLACE_AQUÍ)
2. Ejecuta todas las celdas en orden secuencial  
3. Explora los gráficos y conclusiones generados automáticamente  

---

## 📌 Resultados Clave

| Métrica       | Tienda 1 | Tienda 2 | Tienda 3 (Recomendada) | Tienda 4 |
|---------------|----------|----------|-------------------------|----------|
| Ingresos      | $320k    | $280k    | $150k                   | $310k    |
| Calificación  | 4.2/5    | 4.1/5    | 2.9/5                   | 4.3/5    |
| Envío         | $2.1k    | $1.9k    | $5.2k                   | $2.0k    |

**Conclusión:**  
La **Tienda 3** es la **menos recomendable** para ventas debido a:
- Ingresos significativamente menores  
- Baja satisfacción del cliente  
- Costos logísticos elevados  

---

## 📄 Licencia

Este proyecto utiliza datos simulados bajo licencia **MIT**.

---

## ✉️ Contacto

**xsebasx3**  
🔗 Repositorio: [https://github.com/xsebasx3/challenge-alura-store.git]

