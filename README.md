Análisis electoral de La Libertad Avanza en CABA (Elecciones Legislativas 2025)

Este repositorio presenta un análisis exploratorio del desempeño electoral de La Libertad Avanza (LLA) en la Ciudad Autónoma de Buenos Aires (CABA) durante las elecciones legislativas de octubre de 2025.
El trabajo combina herramientas de visualización geográfica, análisis descriptivo y modelado estadístico a nivel de mesa electoral, con el objetivo de identificar patrones territoriales y socioeconómicos en la distribución del voto.

Contenido del análisis

1. Mapa del Nivel Socioeconómico (NSE) por comuna (fuente: De Grande y Salvia, 2022).
2. Mapa de votos absolutos por comuna en las elecciones de octubre 2025 (fuente: Direccion Nacional Electoral).
3. Distribución del voto por mesa electoral, desagregada por comuna y NSE.
4. Modelo de regresión lineal entre NSE y porcentaje de votos para LLA.
5. Evaluación de supuestos del modelo (residuos, heterocedasticidad, normalidad) y estimación de errores estándar robustos.

Principales hallazgos

1.Fuerte fractura electoral norte-sur: las comunas con NSE alto concentran el mayor caudal de votos.
2.El coeficiente del NSE (≈5.9) indica que cada unidad de aumento en el nivel socioeconómico se asocia con un incremento de casi 6 puntos porcentuales en el voto a LLA.
3.El modelo es estadísticamente significativo (p < 0.001), aunque presenta leve heterocedasticidad.
4.La estimación con errores estándar robustos confirma la robustez de los resultados.

Próximos pasos

Este estudio tiene un enfoque exploratorio. Se propone avanzar hacia modelos multivariados que integren variables sociodemográficas y educativas, con el fin de comprender en mayor profundidad las bases sociales del voto a LLA en la ciudad.

Herramientas utilizadas

Lenguaje: R
Librerías principales: tidyverse, ggplot2, sf, lmtest, sandwich
Fuentes de datos: Junta Electoral CABA (elecciones 2025) y ODSA-UCA (Índice de Estratificación y Desigualdad Social, De Grande y Salvia, 2022).
