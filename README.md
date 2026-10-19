# 📊 Retail Performance Dashboard & Strategic Analysis — 4 Stores  
**Revenue · Logistics · Customer Experience · Geographic Insights**

This project analyzes three years of sales data from four retail stores to identify performance drivers, underperforming locations and opportunities for portfolio optimization. Using Python for data cleaning, exploratory analysis and visualization, it delivers clear dashboards and an executive recommendation to support strategic business decisions.

## 🎯 Project Objective

Conduct an exploratory, visual and strategic analysis to:

- Compare revenue, logistics and customer satisfaction across 4 stores.
- Identify top-performing products, categories and cities.
- Detect geographic sales patterns and market concentration.
- Evaluate whether any store consistently underperforms.
- Deliver a data-driven executive recommendation.

## 🗂️ Repository Structure

```text
/data          → source data files
/imgs          → dashboard and visualization images
/notebooks     → main Jupyter notebook (.ipynb)
README.md      → project documentation
requirements.txt → required Python libraries
```

## 📈 Key Dashboards & Visualizations

- Store performance comparison: revenue, shipments and market share
- Top 10 cities by revenue and sales volume
- Sales breakdown by product category per store
- Geographic distribution of sales by city
- Total revenue vs. average shipping cost
- Revenue share (%) by store
- Customer rating vs. revenue relationship
- Best- and worst-selling products by store
- Product concentration analysis (Top 5 share of sales)

All visualizations are available in the `/imgs` folder.

## 📌 KPI Comparison

| KPI | Business Question | Benchmark / Warning Sign | Key Finding |
|---|---|---|---|
| Revenue share (%) | Which store contributes least to total revenue? | <25% sustained share | Store 4 contributes 23.6%, the lowest cumulative revenue. |
| Shipping cost | Are logistics costs eroding margins? | >15% above store average | Store 1 has the highest shipping costs; no clear correlation with sales. |
| Customer rating | Is satisfaction consistent across stores? | <4.0 vs. internal benchmark | Ratings range 3.98–4.05; no critical gaps. |
| Top 5 products share | Is revenue overly concentrated in few products? | <35% or >60% of sales | All stores between 39–42%; balanced but Store 4 has lower absolute volume. |
| Geographic concentration | Are sales overly dependent on few cities? | >70% in low-potential cities | High concentration in Bogotá and Medellín; Store 4 underperforms even in key markets. |

## 🧭 Executive Summary

The four stores show similar performance in categories, ratings and geographic distribution, but differ significantly in sales volume. **Store 4** consistently underperforms:

- Lowest revenue contribution (23.6%)
- Lowest absolute volume for Top 5 products
- Weaker traction even in high-demand cities
- No logistical or customer experience advantage
- Weakest overall performance across compared KPIs

## ✅ Recommendation

- Maintain Stores 1, 2 and 3 as the core portfolio.
- Consider divesting Store 4, as its marginal contribution does not justify continued operation.

## ⚙️ Tools & Technologies

- Python (pandas, numpy)
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## 👤 Author

**Nairobi Betancourt**  
Data Analysis · Dashboard Development · Executive Reporting



## 📊 **Análisis Comparativo de 4 Tiendas**  
### Facturación · Envíos · Top Productos · Geografía


Este proyecto realiza un análisis integral del desempeño de cuatro tiendas durante un período de tres años, evaluando su contribución a la facturación total, comportamiento por categorías, dependencia del Top 5 de productos, costos logísticos, experiencia de cliente y ventas geográficas.
El objetivo final es identificar cuál tienda mantiene menor aporte al portafolio y debería considerarse para venta.


🧠 1. Objetivo del proyecto

Realizar un análisis exploratorio, visual y estratégico que permita:

Comparar el rendimiento de las 4 tiendas.

Evaluar factores logísticos y de satisfacción del cliente.

Identificar patrones geográficos de ventas.

Determinar si alguna tienda presenta desempeños sistemáticamente inferiores.

Proveer una recomendación ejecutiva basada en datos.


🗂️ 2. Estructura del repositorio
/data            → archivos de datos (si se requieren)
/imgs            → imágenes de las visualizaciones
/notebooks       → notebook principal (.ipynb)
/README.md       → documentación del proyecto
/requirements.txt → librerías necesarias


📈 3. Visualizaciones principales

Comparativa Integral de Desempeño por Tienda

Comparativo Top 10 de Ciudades por Tienda

Composición de ventas por categoría en cada tienda

Distribución Geográfica por Ciudad

Facturación total vs costo de envío promedio por tienda

Participación en la facturación total (%)

Relación entre Calificación y Facturación

Top 10 ciudades por facturación

Ventas del producto más y menos vendido por tienda — participación en ventas

Todas las visualizaciones están disponibles en /imgs.


📌 4. Comparativa de Métricas Clave (KPIs)

Tabla con benchmarks y hallazgos clave

## 4. Comparativa de Métricas Clave


| Comparativo                         | Cómo aporta valor a la decisión                                                                 | Señal de alerta (benchmark)                                      | Resultados obtenidos                                                                 |
|-------------------------------------|--------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Facturación % vs. total 4 tiendas**   | Identifica la tienda de menor contribución al portafolio de ingresos                             | <25 % de participación sostenida en el período analizado          | Tienda 4 aporta **23,6 %**, siendo la de menor facturación acumulada.                 |
| **Envío promedio vs. media tiendas**    | Señala posibles ineficiencias logísticas que erosionan margen cuando el envío lo asume el cliente | >15 % por encima del promedio de tiendas                          | T1 tiene el envío más alto y T4 el más bajo; **no hay relación ventas–envío clara**.   |
| **Calificación vs. líderes**            | Mide satisfacción y probabilidad de recompra a futuro                                            | <4,0 cuando el benchmark interno se sitúa en 4,0–4,1              | Todas entre **3,98 y 4,05**; T2 y T3 levemente mejor posicionadas, sin brechas críticas. |
| **Top productos % facturación**         | Evalúa concentración excesiva en pocos superventas o baja tracción del portafolio                | Top 5 <35 % o >60 % de las ventas totales                         | Todas ~**39–42 %**; T4 es la de menor volumen absoluto aun en sus productos estrella.  |
| **Ventas geográficas - Top ciudades %** | Detecta concentración excesiva en pocas ciudades o escasa presencia en mercados clave            | >70 % concentrado en ciudades menores de bajo potencial           | Alta concentración en Bogotá y Medellín; T4 aporta menos volumen aun en plazas clave. |



🧭 5. Conclusión ejecutiva

Las cuatro tiendas presentan comportamientos similares en categorías, calificaciones y distribución geográfica, pero difieren de forma consistente en volumen. La Tienda 4:

Aporta el menor porcentaje de facturación (23,6 %)

Genera el menor volumen absoluto en sus productos Top 5

Tiene menor tracción incluso en ciudades de mayor demanda

No presenta ventajas logísticas ni de experiencia del cliente

Mantiene el rendimiento más bajo en los ejes comparados

✅ Recomendación

Mantener Tienda 1, 2 y 3 como núcleo principal del portafolio.

Considerar la venta de la Tienda 4, ya que su aporte marginal es menor y no compensa su permanencia operativa.

⚙️ 6. Requisitos

Archivo requirements.txt incluido en este repositorio:

pandas
numpy
matplotlib
seaborn
google-colab

👤 Autor

Nairobi Betancourt
Análisis · Desarrollo visual · Recomendaciones ejecutivas
