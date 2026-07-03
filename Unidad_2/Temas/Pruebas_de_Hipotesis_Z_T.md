# 🧪 Pruebas de Hipótesis Paramétricas (Z y T) y Análisis del Valor-p

## Lógica de una prueba de hipótesis
Una **prueba de hipótesis** es un procedimiento formal para decidir, con base en evidencia muestral, si una afirmación sobre un parámetro poblacional (por ejemplo, la media) es razonable o debe rechazarse. Se plantean dos hipótesis complementarias:

- **Hipótesis nula (H₀):** la afirmación que se pone a prueba (por ejemplo, "la media poblacional es igual a un valor específico").
- **Hipótesis alternativa (H₁):** lo que se concluiría si se rechaza H₀ (puede ser de dos colas, "≠", o de una cola, "\>" o "\<").

## Estadístico de prueba: Z vs T
- Se usa el estadístico **Z** cuando la **varianza poblacional es conocida** (o la muestra es suficientemente grande).
- Se usa el estadístico **T** cuando la **varianza poblacional es desconocida**, lo cual es la situación más común en la práctica, y se estima a partir de la desviación estándar muestral.

## El valor-p: definición correcta
El **valor-p** es la probabilidad de observar un resultado tan extremo (o más) que el obtenido en la muestra, **asumiendo que la hipótesis nula es verdadera**. Un error conceptual grave y muy común es interpretar el valor-p como "la probabilidad de que H₀ sea cierta" — eso **no** es lo que mide.

**Regla de decisión:** si el valor-p es menor que el nivel de significancia α (comúnmente 0.05), se **rechaza H₀**; de lo contrario, no hay evidencia suficiente para rechazarla.

## Errores Tipo I y Tipo II
- **Error Tipo I:** rechazar H₀ cuando en realidad es verdadera (un "falso positivo"). Su probabilidad máxima aceptada es α.
- **Error Tipo II:** no rechazar H₀ cuando en realidad es falsa (un "falso negativo").

En un contexto de ingeniería, ambos errores tienen costos distintos: por ejemplo, declarar que un proceso falló cuando en realidad funciona bien (Tipo I) puede generar gastos innecesarios, mientras que no detectar una falla real (Tipo II) puede tener consecuencias más graves.

## Significancia estadística vs. significancia práctica
Un valor-p pequeño no siempre implica un hallazgo relevante: con **tamaños de muestra muy grandes**, incluso diferencias mínimas e irrelevantes en la práctica pueden resultar "estadísticamente significativas". Por eso es clave distinguir entre significancia estadística (lo que dice la prueba) y significancia práctica (si esa diferencia realmente importa para la ingeniería o el negocio) — un fenómeno relevante especialmente en el análisis de conjuntos de datos masivos ("Big Data"), donde las pruebas clásicas tienden a rechazar H₀ casi siempre.

## Relación entre intervalos de confianza y pruebas de hipótesis
Existe una equivalencia directa: si un intervalo de confianza del 95% para la media **no incluye** el valor propuesto en H₀, entonces la prueba de hipótesis de dos colas correspondiente (con α = 0.05) **rechazará inevitablemente H₀**. Ambos enfoques son, en el fondo, dos caras de la misma inferencia estadística.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 2](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Contenidos.md)

</div>
