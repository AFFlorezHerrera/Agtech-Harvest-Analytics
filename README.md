# 📊 Análisis de Producción de Cosecha y Dashboard de Power BI (2025-2026)

## 📝 Descripción del Proyecto

Este repositorio contiene el ecosistema completo de análisis de datos e inteligencia de negocios desarrollado para evaluar el rendimiento de la campaña de cosecha de los años 2025 y 2026. El objetivo principal es transformar registros planos de campo en insights accionables para la optimización logística, la planificación de mano de obra y la toma de decisiones agronómicas.

El proyecto aborda todo el ciclo de vida del dato:
1. **ETL y Modelado de Datos:** Limpieza, estandarización y anulación de dinamización de columnas (Unpivot) en Power Query para consolidar bases de datos estructuradas bajo un esquema en estrella (Star Schema).
2. **Ingeniería de Datos Espaciales:** Solución al problema de fragmentación cartográfica mediante la conversión y reproyección masiva de coordenadas planas locales (MAGNA-SIRGAS Origen Este Este y UTM Zona 19N) al sistema universal de Grados Decimales (WGS84) para su correcta visualización en mapas.
3. **Análisis de Rendimiento (BI):** Diseño de un cuadro de mando interactivo en Power BI que destaca un crecimiento global del 113.3% en la producción (de 71.04 toneladas a 151.56 toneladas), identificando los lotes de mayor rendimiento (Lotes A y B), aceleraciones críticas (Lote BP) y cuellos de botella operativos.
