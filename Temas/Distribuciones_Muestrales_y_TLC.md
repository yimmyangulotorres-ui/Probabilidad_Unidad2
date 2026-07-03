# 🔔 Distribuciones Muestrales, TLC, t de Student y Chi-cuadrado

## El Teorema del Límite Central (TLC)
El **Teorema del Límite Central** establece que, dada una población con media μ y varianza finita σ², la distribución de las **medias muestrales** (calculadas a partir de muestras de tamaño n) se aproxima a una distribución **Normal**, sin importar cuál sea la forma de la distribución poblacional original — siempre que n sea suficientemente grande.

Este teorema es el puente matemático entre la probabilidad descriptiva y la **inferencia estadística**: gracias a él podemos usar herramientas basadas en la distribución Normal aun cuando los datos originales no lo sean.

## Distribución muestral de la media
Si se extraen repetidamente muestras de tamaño n de una población, y se calcula la media de cada muestra, esas medias forman una nueva distribución (la "distribución muestral de la media") que cumple:
- Su media coincide con la media poblacional: E[X̄] = μ
- Su desviación estándar, llamada **Error Estándar (σ/√n)**, disminuye a medida que aumenta el tamaño de muestra n.

## Error Estándar y tamaño de muestra
El error estándar mide la variabilidad esperada de la media muestral respecto a la media poblacional real. Como depende de **√n** en el denominador, reducirlo a la mitad requiere **cuadruplicar** el tamaño de la muestra — de allí que recolectar más datos tenga un beneficio decreciente en precisión.

## Distribución t de Student
Cuando el tamaño de muestra es pequeño y la **varianza poblacional es desconocida**, no es correcto usar la distribución Normal estándar (Z); en su lugar se utiliza la distribución **t de Student**, que tiene colas más "pesadas" que la Normal para compensar la incertidumbre adicional de estimar la varianza a partir de la propia muestra. Su forma depende de los **grados de libertad (gl = n − 1)**: a mayor gl, más se parece la t a la Normal estándar.

## Distribución Chi-cuadrado (χ²)
La distribución **Chi-cuadrado** se utiliza, entre otros usos, para construir intervalos de confianza sobre la **varianza poblacional**, y es la base de numerosas pruebas de bondad de ajuste e independencia en estadística inferencial.

## Intervalos de confianza: primera aproximación
A partir de una media muestral y su error estándar, se puede construir un rango de valores plausibles (intervalo de confianza) para la media poblacional real, usando el valor crítico correspondiente de la distribución Z o t según el tamaño de muestra disponible. Este concepto se retoma con mayor profundidad en la Unidad 2.

## Aplicación práctica
Estas herramientas permiten, por ejemplo, verificar si un proceso de fabricación está "bajo control" comparando un intervalo de confianza construido a partir de una muestra contra un valor nominal esperado, o decidir si conviene usar t o Z al analizar una variable de un dataset regional según el tamaño de muestra disponible.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 1](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Unidad_1/Contenidos.md)

</div>
