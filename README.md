# Dashboard de Desempeño Comercial 2024–2025 | Andes Retail Group

[![Ver Dashboard en Tableau](https://img.shields.io/badge/Ver_Dashboard-Tableau_Public-E97627?style=for-the-badge&logo=tableau)](https://public.tableau.com/views/RendimientoComercialAndesRetail2024-2025/VistaGeneral?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Resumen del Proyecto
Análisis integral del desempeño comercial de **Andes Retail Group** durante el periodo 2024–2025. Este proyecto abarca desde la limpieza y preparación de datos hasta la creación de un dashboard interactivo en Tableau y la comunicación de insights de negocio utilizando el **Framework SCQA** (Situación, Complicación, Pregunta, Respuesta).

**Herramientas y Habilidades:** `Tableau`, `Análisis de Datos`, `Visualización de Datos`, `Comunicación Ejecutiva`, `Storytelling con Datos (SCQA)`.

![Vista General](Vista%20General.png)

![Vista Detalle](Vista%20Detalle.png)

---

## Contexto del Negocio (Situación)
Andes Retail Group generó **$5.53M en ingresos totales** durante 2024–2025, operando en tres mercados principales (Colombia, Perú y Chile) y manteniendo un margen bruto saludable del **35.1%**. El negocio muestra un patrón estacional muy consistente: 
* **Picos de ventas:** Diciembre - Enero.
* **Valles de ventas:** Junio - Julio.

## Problema Identificado (Complicación)
A pesar de la estacionalidad estable, se detectó una **caída interanual del 6.8% en los ingresos totales** (pasando de $2.86M en 2024 a $2.67M en 2025). Esta retracción fue de carácter transversal:
* **Impacto geográfico:** Los tres países retrocedieron. Perú, el mercado líder, fue el más afectado con un **-10.3%**. Colombia cayó -4.5% y Chile -4.4%.
* **Impacto por categoría:** 3 de las 4 categorías de producto experimentaron caídas. "Hogar" fue la única excepción, mostrando un crecimiento del +3.3%.

## Hallazgos Clave (Respuesta Analítica)
Tras profundizar en los datos transaccionales, se descubrieron los siguientes insights:

1. **El valor reside en la "Venta Alta":** El 44% de los pedidos (aquellos ≥ $1,000) concentra el **72% del ingreso total**. Estos pedidos tienen, en promedio, un precio unitario 59% más alto y casi el doble de unidades.
2. **Cero sensibilidad al precio:** Existe una correlación casi nula (-0.01) entre el precio unitario y las unidades vendidas. La caída en ingresos no se debe a que el cliente rechace precios altos, sino a una disminución neta en la actividad comercial de alto valor.
3. **Riesgo de cartera mitigado:** La base de clientes está sana y altamente diversificada (3,821 clientes únicos). Los 5 clientes principales representan solo el **0.8% del ingreso total**, descartando dependencia de cuentas clave.

## Recomendaciones Estratégicas
El foco comercial del próximo trimestre debe ser táctico y transversal:
* **Campañas de Cross-sell / Bundle:** Implementar estrategias para empujar los pedidos actuales de "Venta Baja" hacia el umbral de los $1,000. El problema es de volumen de venta alta, no de retención puntual.
* **Foco Geográfico:** Priorizar las iniciativas en **Perú** (por ser el mercado de mayor peso) y en la región **Sur** (por registrar la caída más pronunciada).

---

## Estructura del Repositorio
* `S10_Proyecto_Limpio.ipynb`: Notebook con el flujo de trabajo, limpieza conceptual y el desarrollo detallado de la narrativa SCQA.

> **Nota:** Puedes interactuar con el análisis visual completo directamente en el [Dashboard de Tableau Public](https://public.tableau.com/views/RendimientoComercialAndesRetail2024-2025/VistaGeneral?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
