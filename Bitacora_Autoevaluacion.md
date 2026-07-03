# 📔 Bitácora de Autoevaluación – Unidad 2 (Inferencia Estadística)
---

## 🎯 ¿Qué aprendí en esta unidad?

Esta unidad marcó el paso de simplemente **describir** el comportamiento de una variable aleatoria, a usarla activamente para **tomar decisiones basadas en evidencia**. Aprendí a:

- Validar si una variable continua se comporta realmente como una Normal (Gráfico Q-Q, Test de Shapiro-Wilk), en lugar de asumirlo solo por la forma del histograma.
- Comprobar de forma práctica cómo el Teorema del Límite Central "normaliza" las medias muestrales incluso cuando la población original es muy asimétrica.
- Construir e interpretar correctamente un intervalo de confianza, entendiendo que no es lo mismo un 95% de confianza que "95% de probabilidad de que el parámetro esté ahí dentro".
- Plantear y resolver pruebas de hipótesis (Z y T), y sobre todo, a leer el valor-p de forma correcta en vez de caer en el error común de tratarlo como "la probabilidad de que H0 sea cierta".
- Comparar dos o más grupos de datos con pruebas T (independientes y pareadas) y con ANOVA, verificando primero supuestos como la homocedasticidad (Test de Levene) antes de confiar en el resultado.

## 🧩 Dificultades superadas

Durante el desarrollo de la unidad me encontré con varias dificultades, principalmente relacionadas con el razonamiento estadístico más que con la ejecución en sí:

1. **Elegir el estadístico correcto (Z vs. T):** al inicio no tenía claro cuándo la varianza poblacional se consideraba "conocida" y cuándo no, lo que me llevaba a dudar entre usar la distribución Normal o la t de Student. Resolví esto entendiendo que, en la práctica, casi siempre se trabaja con la varianza muestral, por lo que la t de Student termina siendo la herramienta más usada con muestras pequeñas.
2. **Interpretar el valor-p sin caer en el error conceptual clásico:** me costó separar "el valor-p es pequeño" de "hay una diferencia importante en la realidad". Superar esto significó entender la diferencia entre significancia **estadística** y significancia **práctica**, sobre todo al simular tamaños de muestra muy grandes donde casi cualquier diferencia mínima termina siendo "significativa".
3. **Verificar supuestos antes de aplicar una prueba:** inicialmente aplicaba las pruebas T directamente, sin comprobar primero si las varianzas de los grupos comparados eran realmente iguales. Aprender a usar el Test de Levene como paso previo me ayudó a decidir correctamente entre la T clásica y la T de Welch.
4. **Relacionar los conceptos entre sí:** conectar intervalos de confianza con pruebas de hipótesis (si el IC no incluye el valor de H0, la prueba lo rechaza) fue algo que solo terminé de comprender al trabajarlo con datos y ejemplos concretos, más que con la fórmula sola.

## 💡 Reflexión final

Esta unidad me hizo ver la estadística no como una serie de fórmulas aisladas, sino como una manera estructurada de **cuantificar la incertidumbre** al tomar decisiones: desde estimar un promedio con un margen de error honesto, hasta decidir si dos algoritmos, procesos o regiones realmente se comportan distinto o si esa diferencia podría explicarse solo por el azar del muestreo. El mayor aprendizaje no fue tanto ejecutar cada prueba, sino desarrollar el criterio para saber **cuál prueba usar, cuándo confiar en el resultado y qué tan lejos se puede llegar con una conclusión estadística**.

---
<div align="left">

[![⬅️ Volver al Inicio](https://img.shields.io/badge/⬅️_Volver_al_Inicio-blue?style=for-the-badge)](/README.md)

</div>
