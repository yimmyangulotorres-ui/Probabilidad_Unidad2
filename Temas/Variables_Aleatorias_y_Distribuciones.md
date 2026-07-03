# 📊 Variables Aleatorias y Distribuciones de Probabilidad

## ¿Qué es una variable aleatoria?
Una **variable aleatoria (V.A.)** es una función que asigna un número real a cada resultado posible de un experimento aleatorio. Se representa habitualmente con una letra mayúscula (X, Y…) y permite trabajar de forma numérica con fenómenos que, en principio, son incierto.

## Variables aleatorias discretas
Toman valores en un conjunto **finito o infinito numerable** (por ejemplo, el número de defectos en un lote, o el número de clientes que llegan en una hora).

Se describen mediante la **Función de Masa de Probabilidad (PMF)**: `p(x) = P(X = x)`, que cumple:
- 0 ≤ p(x) ≤ 1 para todo x
- La suma de p(x) sobre todos los valores posibles es igual a 1

## Variables aleatorias continuas
Toman valores en un **intervalo continuo** de números reales (por ejemplo, un tiempo de respuesta, una temperatura o un peso).

Se describen mediante la **Función de Densidad de Probabilidad (PDF)**: `f(x) ≥ 0`, tal que la probabilidad de que X caiga en un intervalo [a, b] es el área bajo la curva entre a y b. En una variable continua, la probabilidad de un valor puntual exacto es siempre cero: `P(X = x) = 0`.

## Función de Distribución Acumulada (CDF)
La CDF se define como `F(x) = P(X ≤ x)` y acumula la probabilidad hasta un punto x:
- En variables **discretas**, la CDF tiene forma de "escalera" (función escalonada), porque acumula saltos de probabilidad en cada valor posible.
- En variables **continuas**, la CDF es una curva suave, calculada como el área bajo la PDF hasta x.

## Distribución Binomial
Modela el número de éxitos en **n** ensayos independientes de Bernoulli, cada uno con la misma probabilidad de éxito **p**. Es el modelo natural para conteos de "éxito/fracaso" repetidos (por ejemplo, cuántos componentes de un lote resultan defectuosos).

Sus propiedades teóricas son:
- Esperanza: E[X] = n·p
- Varianza: Var(X) = n·p·(1−p)

## Distribución Normal
Es la distribución más importante de la estadística, también llamada **distribución gaussiana**. Tiene forma de campana simétrica alrededor de su media y describe adecuadamente muchos fenómenos naturales y de ingeniería (tiempos, mediciones físicas, errores de medición, etc.), en gran parte gracias al Teorema del Límite Central que se aborda más adelante en la Unidad 2.

## ¿Por qué importa esta distinción?
Diferenciar si una variable es discreta o continua determina qué herramienta matemática usar (PMF o PDF), cómo interpretar sus gráficas y qué distribuciones de probabilidad son aplicables — una base indispensable antes de calcular esperanza, varianza o hacer inferencia estadística.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 1](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Unidad_1/Contenidos.md)

</div>
