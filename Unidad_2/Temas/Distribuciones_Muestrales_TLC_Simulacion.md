# 🎲 Distribuciones Muestrales y TLC mediante Simulación Estocástica

## Demostrando el TLC de forma empírica
Más allá de su enunciado teórico, el **Teorema del Límite Central (TLC)** puede demostrarse computacionalmente mediante simulación: si se parte de una población claramente **no normal** (por ejemplo, con una distribución muy asimétrica), y se extraen repetidamente muchas muestras de tamaño n, calculando la media de cada una, la distribución resultante de esas medias muestrales converge visiblemente hacia una forma de campana Normal a medida que n crece.

Este ejercicio de simulación (a veces llamado un experimento de "Monte Carlo") permite observar, de forma directa, cómo el TLC transforma variables originalmente asimétricas en un resultado manejable con herramientas de la distribución Normal.

## Remuestreo (bootstrapping básico)
El **remuestreo** consiste en extraer múltiples submuestras a partir de un mismo conjunto de datos, para estudiar el comportamiento de un estadístico (como la media) sin depender de supuestos teóricos rígidos sobre la población original. Es especialmente útil cuando la variable de interés no cumple el supuesto de normalidad.

## Error estándar y ley de los grandes números
El **Error Estándar de la Media (σ/√n)** cuantifica cuánto varía, en promedio, la media muestral respecto a la media poblacional real. A medida que el tamaño de muestra n aumenta, este error disminuye — pero no de forma lineal, sino según la raíz cuadrada de n. Esto significa que, para **reducir a la mitad** el error estándar, es necesario **cuadruplicar** el tamaño de la muestra, un principio clave a la hora de planificar cuántos datos recolectar.

Este comportamiento es una manifestación práctica de la **Ley de los Grandes Números**: entre más datos se recolectan, más se estabiliza y se acerca a la realidad poblacional el estimador calculado.

## ¿Cuándo es suficiente el tamaño de muestra?
Existe una regla práctica que sugiere que, a partir de n ≈ 30, las medias muestrales ya se aproximan razonablemente bien a una Normal. Sin embargo, esta regla no es universal: si la población original tiene una asimetría muy extrema, puede requerirse un tamaño de muestra considerablemente mayor para que la aproximación del TLC sea confiable.

## Desviación estándar vs. error estándar
Es importante no confundir dos conceptos relacionados pero distintos:
- La **desviación estándar** describe la dispersión de los datos individuales de una muestra.
- El **error estándar** describe la dispersión esperada de un estadístico (como la media) calculado repetidamente a partir de distintas muestras.

## Aplicación práctica
Adaptar este proceso de remuestreo a una variable real de un dataset regional que no cumple el supuesto de normalidad permite "normalizar" el análisis de sus medias muestrales, habilitando el uso posterior de intervalos de confianza y pruebas de hipótesis con mayor solidez estadística.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 2](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Contenidos.md)

</div>
