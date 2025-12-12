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

/data          → archivos de datos (si se requieren)
/imgs          → imágenes de las visualizaciones
/notebooks     → notebook principal (.ipynb)
/README.md     → documentación del proyecto
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

Ventas del producto más y menos vendido por tienda-participación en las ventas totales

Todas las visualizaciones restantes están disponibles en /imgs.

📌 4. Tabla comparativa de KPIs
## 4. Comparativa de Métricas Clave

| Comparativo                         | Cómo aporta valor a la decisión                                                                 | Señal de alerta (benchmark)                                      | Resultados obtenidos                                                                 |
|-------------------------------------|--------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Facturación % vs. total 4 tiendas**   | Identifica la tienda de menor contribución al portafolio de ingresos                             | <25 % de participación sostenida en el período analizado          | Tienda 4 aporta **23,6 %**, siendo la de menor facturación acumulada.                 |
| **Envío promedio vs. media tiendas**    | Señala posibles ineficiencias logísticas que erosionan margen cuando el envío lo asume el cliente | >15 % por encima del promedio de tiendas                          | T1 tiene el envío más alto y T4 el más bajo; **no hay relación ventas–envío clara**.   |
| **Calificación vs. líderes**            | Mide satisfacción y probabilidad de recompra a futuro                                            | <4,0 cuando el benchmark interno se sitúa en 4,0–4,1              | Todas entre **3,98 y 4,05**; T2 y T3 levemente mejor posicionadas, sin brechas críticas. |
| **Top productos % facturación**         | Evalúa concentración excesiva en pocos superventas o baja tracción del portafolio                | Top 5 <35 % o >60 % de las ventas totales                         | Todas ~**39–42 %**; T4 es la de menor volumen absoluto aun en sus productos estrella.  |
| **Ventas geográficas - Top ciudades %** | Detecta concentración excesiva en pocas ciudades o escasa presencia en mercados clave            | >70 % concentrado en ciudades menores de bajo potencial           | Alta concentración en Bogotá y Medellín; T4 aporta menos volumen aun en plazas clave. |

🧭 5. Conclusión ejecutiva (resumen)

Las cuatro tiendas presentan comportamientos similares en categorías, calificaciones y distribución geográfica, pero difieren de forma consistente en volumen.
La Tienda 4:

Aporta el menor porcentaje de facturación (23,6 %)

Genera el menor volumen absoluto en sus productos Top 5

Vende menos incluso en las ciudades de mayor demanda

No presenta ventajas logísticas ni en satisfacción del cliente

Mantiene el desempeño más bajo en todos los ejes relevantes del análisis

Recomendación:

👉 Mantener Tienda 1, 2 y 3 como núcleo del portafolio.

👉 Considerar la venta de Tienda 4, ya que su aporte marginal es menor y no compensa su permanencia operativa.


⚙️ 6. Requisitos

Archivo requirements.txt incluido en este repo:

pandas
numpy
matplotlib
seaborn
google-colab

👤 Autor

Tu nombre Nairobi Betancourt

Análisis + desarrollo visual + recomendaciones ejecutivas.
