# 🎲 Fundamentos de Probabilidad y Espacios Muestrales

## ¿Qué es un experimento aleatorio?
Un **experimento aleatorio** es cualquier proceso cuyo resultado no se puede predecir con certeza antes de realizarlo, aunque se conozcan de antemano todos los resultados posibles (por ejemplo, lanzar una moneda, tirar un dado o registrar el tiempo entre fallos de un componente).

## Espacio muestral y eventos
- **Espacio muestral (Ω):** es el conjunto de todos los resultados posibles de un experimento aleatorio.
- **Evento:** es cualquier subconjunto del espacio muestral; representa un resultado o combinación de resultados de interés.

Por ejemplo, al lanzar dos dados el espacio muestral tiene 36 resultados posibles, y un evento podría ser "la suma de los dados es 7".

## Operaciones entre eventos
Como los eventos son conjuntos, se les aplican las operaciones clásicas de la teoría de conjuntos:

| Operación | Significado |
|:--|:--|
| **A ∪ B** (unión) | Ocurre A, o B, o ambos |
| **A ∩ B** (intersección) | Ocurren A y B simultáneamente |
| **Aᶜ** (complemento) | No ocurre A |
| **A y B mutuamente excluyentes** | A ∩ B = ∅ (no pueden ocurrir al mismo tiempo) |

## Enfoques para asignar probabilidad
1. **Enfoque clásico:** todos los resultados del espacio muestral son igualmente probables. `P(A) = (casos favorables) / (casos posibles)`.
2. **Enfoque empírico (frecuentista):** la probabilidad se estima repitiendo el experimento muchas veces y observando la frecuencia relativa del evento. Este enfoque se sustenta en la **Ley de los Grandes Números**: a medida que aumenta el número de repeticiones, la frecuencia relativa converge al valor teórico de la probabilidad.
3. **Enfoque subjetivo:** la probabilidad se asigna en función del grado de creencia o experiencia de quien la estima, cuando no es posible calcularla ni repetir el experimento.

## Probabilidad condicional e independencia
La **probabilidad condicional** mide la probabilidad de que ocurra un evento A, sabiendo que ya ocurrió otro evento B:

> P(A|B) = P(A ∩ B) / P(B)

Dos eventos son **independientes** cuando el hecho de que ocurra uno no cambia la probabilidad del otro, es decir, cuando:

> P(A ∩ B) = P(A) · P(B)

## Reglas básicas de probabilidad
- 0 ≤ P(A) ≤ 1 para cualquier evento A.
- P(Ω) = 1 (algún resultado del espacio muestral siempre ocurre).
- **Regla de la suma:** P(A ∪ B) = P(A) + P(B) − P(A ∩ B).

## Aplicación práctica
Estos fundamentos permiten, por ejemplo, seleccionar y justificar el tipo de variable y el modelo probabilístico más adecuado para un conjunto de datos regional (como los del proyecto integrador), antes de avanzar hacia variables aleatorias y distribuciones más específicas.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 1](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Unidad_1/Contenidos.md)

</div>
