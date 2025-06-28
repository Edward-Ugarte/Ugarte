# Ugarte
  Resumen del script UGARTE en Hansl
  Este script realiza una simulación completa de ingresos y análisis econométrico en cinco grandes bloques:
- Preparación y Simulación de Datos:
- Crea 1,000 observaciones con ingresos simulados de distribución normal.
- Define estadísticas descriptivas para calcular márgenes de error y desviación estándar.
- Tamaño Muestral e Intervalos de Confianza:
- Calcula el tamaño muestral necesario (con y sin corrección por población finita).
- Genera intervalos de confianza del 95% para la media de ingresos.
- Prueba de Hipótesis:
- Contrasta la media muestral frente a un valor poblacional (𝜇₀ = 1700) usando el estadístico Z.
- Modelado con Regresión de Poisson:
- Agrupa ingresos en categorías y estima un modelo de Poisson con tres variables explicativas (X1, X2, X3).
- Estimación Bayesiana con Gibbs Sampling:
- Simula distribuciones posteriores de los coeficientes (β0 a β3) con 1,000 iteraciones.
- Imprime estimaciones medias, desviaciones típicas y estadísticos adicionales como el Criterio de Akaike.

El script está diseñado para mostrar todo el flujo de trabajo, desde la generación de datos hasta la inferencia clásica y Bayesiana. muy util para trabajo y docencia para econometría simulada.
