# 🎯 Distribuciones Discretas Notables: Binomial y Poisson

## Distribución Binomial
La distribución **Binomial** modela el número de éxitos **x** obtenidos en **n** ensayos independientes de Bernoulli, cada uno con la misma probabilidad de éxito **p**. Es el modelo adecuado cuando:
- El experimento se repite un número fijo de veces (n).
- Cada ensayo tiene solo dos resultados posibles (éxito / fracaso).
- Los ensayos son independientes entre sí, y p permanece constante.

Su media es n·p y su varianza es n·p·(1−p).

## Distribución de Poisson
La distribución de **Poisson** modela el número de eventos que ocurren en un intervalo fijo de tiempo o espacio, conociendo una **tasa media de ocurrencia (λ)**. Es útil para modelar "eventos raros" o de conteo, como el número de peticiones erróneas por minuto en un servidor, accidentes por semana, o llamadas recibidas por hora.

Una propiedad característica del modelo de Poisson es que su media y su varianza son iguales: **E[X] = Var(X) = λ**.

## La aproximación de la Binomial a la Poisson
Cuando en una distribución Binomial el número de ensayos **n** es muy grande y la probabilidad de éxito **p** es muy pequeña (de forma que el producto λ = n·p permanece moderado), la distribución Binomial se aproxima muy bien a una distribución de Poisson con parámetro λ = n·p. Esta aproximación es útil porque simplifica el cálculo cuando n es grande y p es pequeño, situación común al modelar eventos poco frecuentes dentro de una gran cantidad de oportunidades.

## Función de Distribución Acumulada (CDF) en variables discretas
Al ser variables que solo toman valores enteros, su CDF avanza a "saltos" (función escalonada): permanece constante entre valores enteros consecutivos y salta hacia arriba en cada valor posible de la variable, a diferencia de la CDF suave y continua de las variables continuas.

## Supuestos y limitaciones
Es importante verificar que los supuestos del modelo se cumplan antes de aplicarlo a datos reales:
- Para la Binomial: independencia entre ensayos y probabilidad de éxito constante (por ejemplo, un muestreo *sin reemplazo* de una población pequeña rompe estos supuestos).
- Para la Poisson: la tasa λ debe ser razonablemente estable durante todo el período analizado (propiedad de estacionariedad); si la tasa cambia con el tiempo, el modelo deja de ser adecuado.

## Aplicación práctica
Al trabajar con un dataset real, se puede identificar una variable de "conteo" (por ejemplo, transacciones por hora, accidentes por semana), calcular su media muestral como estimador de λ, y contrastar visualmente si el comportamiento empírico se ajusta razonablemente al modelo teórico de Poisson.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 1](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Unidad_1/Contenidos.md)

</div>
