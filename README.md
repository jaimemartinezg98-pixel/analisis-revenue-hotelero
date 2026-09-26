# Análisis Cuantitativo de Revenue Management Hotelero

Este proyecto es un análisis exploratorio de casi 120.000 reservas hoteleras (un resort y un hotel urbano en Portugal), desarrollado en **R (Tidyverse)**.

El objetivo de este análisis es extraer *insights* de negocio sobre el comportamiento de la demanda, la estacionalidad, los canales de distribución y la política de precios, simulando un encargo de consultoría para una cadena hotelera en expansión.

👉 [Ver el análisis interactivo y los resultados aquí](https://jaimemartinezg98-pixel.github.io/analisis-revenue-hotelero/)

## 🛠️ Herramientas y Técnicas Aplicadas
* **Lenguaje:** R
* **Librerías:** `tidyverse` (dplyr, tidyr, ggplot2, forcats, lubridate), `cowplot`.
* **Técnicas Cuantitativas:** 
  * Limpieza y recodificación de datos (gestión de nulos y atípicos).
  * Feature engineering (creación de variables de facturación, estancia y tipología de cliente).
  * Descomposición de factores de crecimiento (precio vs. volumen).
  * Análisis de correlación demanda-precio.

## 📊 Principales Insights de Negocio
1. **Riesgo de intermediación:** El canal online aporta hasta el 61% de la facturación en el hotel urbano, presionando el margen neto por comisiones y mostrando tasas de cancelación elevadas.
2. **Motores de crecimiento:** Mientras el hotel urbano creció un 56% interanual apalancado en volumen de reservas, el resort creció un 18% impulsado por un aumento del 15% en el precio medio (ADR).
3. **Elasticidad de tarifas:** El precio del hotel urbano se correlaciona con su demanda (0.58), mientras que el resort (0.43) mantiene tarifas de temporada rígidas, sugiriendo un margen de optimización en su estrategia de precios dinámicos.

*Datos extraídos del dataset público "Hotel booking demand" (Antonio, Almeida y Nunes, 2019).*
 
