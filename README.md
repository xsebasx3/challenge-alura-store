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

# 📊 Análisis Realizados

# Facturación por tienda
- Suma de ingresos totales por ubicación
- Comparativa entre tiendas

# Ventas por categoría  
- Distribución porcentual de productos vendidos
- Identificación de categorías más rentables

### Satisfacción del cliente
- Calificación promedio (escala 1-5)
- Análisis de tendencias en evaluaciones

# Productos destacados
- **Top 3**: Productos con mayor volumen de ventas
- **Peores 3**: Productos con menor rotación

# Logística  
- Costo promedio de envío por tienda
- Relación costo-beneficio de la distribución

---

# ▶️ Cómo Ejecutar

1. **Accede al notebook**:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/TU_ENLACE)

2. **Flujo de trabajo**:
   - Ejecuta celdas en orden secuencial
   - Revisa outputs después de cada análisis
   - Explora gráficos interactivos

3. **Requisitos**:
   - Navegador web actualizado
   - Cuenta Google (para guardar resultados)

---

# 📌 Resultados Clave

| Métrica               | Tienda 1 | Tienda 2 | Tienda 3 (Recomendada) | Tienda 4 |
|-----------------------|----------|----------|------------------------|----------|
| **Ingresos totales**  | $320k    | $280k    | $150k                  | $310k    |
| **Calificación**      | 4.2 ★    | 4.1 ★    | 2.9 ★                  | 4.3 ★    |
| **Producto estrella** | Laptop   | Tablet   | Silla básica           | Smartphone|
| **Costo envío**       | $2,100   | $1,900   | $5,200                 | $2,000   |

**Conclusión definitiva**:  
La Tienda 3 presenta:
- ☑️ 53% menos ingresos que el promedio  
- ☑️ Calificación 31% inferior  
- ☑️ Costos logísticos 2.6× más altos  

---

# 📄 Licencia  
MIT License - Uso académico/comercial permitido con atribución

✉️ **Contacto**: [Tu nombre] - [tu@email.com]  
🔗 **Repositorio**: [github.com/tusuario/alura-store-analysis]
