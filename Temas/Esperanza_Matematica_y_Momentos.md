# ➗ Esperanza Matemática, Varianza y Momentos Estadísticos

## Esperanza matemática (E[X])
La **esperanza matemática** (o valor esperado) es el promedio ponderado de todos los valores que puede tomar una variable aleatoria, ponderado por su probabilidad de ocurrencia. Representa el "centro de masa" de la distribución:

- Para una variable **discreta**: E[X] es la suma de cada valor x multiplicado por su probabilidad p(x).
- Para una variable **continua**: E[X] es la integral de x multiplicado por su densidad f(x), sobre todo el dominio.

## Varianza y desviación estándar
La **varianza (Var(X))** mide qué tan dispersos están los valores de la variable respecto a su esperanza. Una forma útil de calcularla es:

> Var(X) = E[X²] − (E[X])²

La **desviación estándar** es la raíz cuadrada de la varianza, y se interpreta en las mismas unidades que la variable original, lo que la hace más fácil de comunicar que la varianza.

## Estimadores puntuales: media y varianza muestral
Cuando se trabaja con una muestra real de datos (por ejemplo, un dataset regional) en lugar de un modelo teórico, se calculan sus equivalentes empíricos:

- **Media muestral (x̄):** estimador de la esperanza poblacional.
- **Varianza muestral (s²):** estimador de la varianza poblacional, calculada dividiendo la suma de las diferencias cuadráticas entre **n − 1** (y no entre n), para obtener un **estimador insesgado** de la varianza poblacional. A este ajuste se lo conoce como corrección de Bessel.

## ¿Por qué dividir entre n−1 y no entre n?
Al dividir entre n, la varianza muestral tiende, en promedio, a **subestimar** la varianza real de la población, porque la media muestral siempre se ajusta ligeramente a los propios datos de la muestra. Dividir entre n−1 corrige ese sesgo sistemático, produciendo un estimador insesgado — es decir, uno cuyo valor esperado coincide con el parámetro poblacional real.

## Momentos estadísticos
La esperanza y la varianza son casos particulares de los llamados **momentos** de una distribución:
- El **primer momento** (esperanza) describe la tendencia central.
- El **segundo momento centrado** (varianza) describe la dispersión.
- Momentos de orden superior permiten describir la asimetría (sesgo) y el apuntamiento (curtosis) de una distribución.

## Interpretación práctica
En un análisis regional, combinar la esperanza (tendencia central) con la varianza (dispersión) permite identificar valores atípicos, evaluar qué tan confiable es la media como representante del comportamiento típico de los datos, y decidir si conviene seguir asumiendo un modelo probabilístico simple o uno más flexible.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 1](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Unidad_1/Contenidos.md)

</div>
