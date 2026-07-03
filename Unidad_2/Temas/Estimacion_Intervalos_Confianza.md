# 📐 Estimación de Parámetros e Intervalos de Confianza

## Estimación puntual vs. estimación por intervalos
Una **estimación puntual** entrega un único valor (por ejemplo, la media muestral) como "mejor apuesta" del parámetro poblacional real. El problema es que esa estimación, por sí sola, casi nunca coincide exactamente con el valor real y no comunica ningún margen de incertidumbre.

Una **estimación por intervalos** resuelve esta limitación entregando un **rango de valores plausibles** para el parámetro, junto con un nivel de confianza asociado — una forma mucho más honesta y útil de reportar resultados en ingeniería.

## Intervalo de confianza para la media (muestras grandes – distribución Z)
Cuando el tamaño de muestra es grande, el Teorema del Límite Central permite construir el intervalo de confianza (IC) para la media poblacional usando la distribución Normal estándar, combinando la media muestral, el error estándar y un valor crítico Z asociado al nivel de confianza deseado (por ejemplo 95%).

## Intervalo de confianza para muestras pequeñas (distribución t de Student)
Cuando el tamaño de muestra es pequeño y la varianza poblacional es desconocida, se usa la distribución **t de Student** en lugar de la Z. Al tener colas más pesadas, la t compensa la incertidumbre adicional de estimar la varianza a partir de una muestra reducida, e incorpora los **grados de libertad (n − 1)** en su cálculo.

## Interpretación correcta de un intervalo de confianza
Una interpretación frecuentista correcta de un intervalo de confianza del 95% es: si se repitiera el proceso de muestreo muchas veces y se construyera un intervalo en cada ocasión, aproximadamente el 95% de esos intervalos contendría el verdadero valor poblacional. **No es correcto decir** que "existe un 95% de probabilidad de que el parámetro caiga dentro de este intervalo específico" — el parámetro poblacional es fijo, lo aleatorio es el intervalo construido a partir de la muestra.

## El compromiso entre confianza y precisión
Existe un trade-off fundamental: **a mayor nivel de confianza exigido (por ejemplo, pasar de 95% a 99%), más ancho se vuelve el intervalo**, es decir, se pierde precisión. Un intervalo extremadamente amplio (cercano al 100% de confianza) puede terminar siendo tan poco específico que pierde utilidad práctica para la toma de decisiones. Por esta razón, el 95% es el estándar más usado en la industria: ofrece un equilibrio razonable entre certeza y precisión.

## ¿Cómo reducir el margen de error sin perder confianza?
La única forma de reducir el margen de error sin sacrificar el nivel de confianza es **aumentar el tamaño de la muestra**, ya que el error estándar (y por lo tanto el margen de error) depende inversamente de √n.

## Aplicación práctica
Estos conceptos permiten reportar, por ejemplo, no solo "el consumo energético promedio es de 350 kWh", sino un rango con respaldo estadístico como "el consumo energético promedio se encuentra, con 95% de confianza, entre 341 y 359 kWh" — una forma de comunicar resultados mucho más rigurosa para la toma de decisiones de ingeniería o de políticas públicas regionales.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 2](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Contenidos.md)

</div>
