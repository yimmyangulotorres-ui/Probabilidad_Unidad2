# ⚖️ Comparación de Medias: Pruebas T de Dos Muestras y ANOVA

## Comparar dos grupos: pruebas T de dos muestras
Cuando se quiere saber si **dos poblaciones distintas** tienen la misma media (por ejemplo, comparar dos zonas geográficas, dos proveedores o dos algoritmos), se recurre a pruebas T para dos muestras. Existen dos variantes según cómo se relacionan los datos:

- **Muestras independientes:** los dos grupos provienen de unidades de observación distintas (por ejemplo, Zona Norte vs. Zona Sur). Se evalúa si sus medias son estadísticamente diferentes.
- **Muestras pareadas (dependientes):** los datos de ambos grupos provienen de las **mismas unidades**, medidas en dos momentos distintos (por ejemplo, "antes" y "después" de una intervención). En este caso se analiza la media de las diferencias entre cada par de observaciones.

Aplicar una prueba de muestras independientes a un escenario de datos pareados es un error metodológico grave, porque ignora la correlación natural entre las mediciones "antes" y "después" del mismo sujeto, distorsionando el resultado de la prueba.

## El supuesto de homocedasticidad
La prueba T clásica para muestras independientes asume que ambas poblaciones tienen **varianzas iguales (homocedasticidad)**. Este supuesto debe verificarse, no darse por sentado — típicamente mediante el **Test de Levene**, cuya hipótesis nula es precisamente que las varianzas de ambos grupos son iguales.

Si el Test de Levene indica que las varianzas **no** son iguales (heterocedasticidad), corresponde usar la variante conocida como **Prueba T de Welch**, que ajusta automáticamente los grados de libertad para seguir haciendo una inferencia válida a pesar de la diferencia en dispersión entre los grupos.

## ANOVA: comparación de más de dos grupos
Cuando se necesita comparar las medias de **tres o más grupos** simultáneamente (por ejemplo, varias zonas o varios proveedores a la vez), el **Análisis de Varianza (ANOVA) de un factor** permite evaluar si existe al menos una diferencia significativa entre ellos, sin necesidad de realizar múltiples pruebas T por separado (lo cual incrementaría el riesgo de cometer errores Tipo I de forma acumulada).

## Pruebas Post-Hoc
Si el ANOVA detecta que existe una diferencia significativa entre los grupos, **no indica cuáles pares de grupos son distintos entre sí** — solo que al menos uno lo es. Para identificar específicamente qué pares difieren, se aplican **pruebas post-hoc**, como la **Prueba de Tukey**, diseñadas para hacer comparaciones múltiples controlando el riesgo global de error.

## El A/B Testing como aplicación de estas pruebas
Comparar dos versiones de un mismo sistema, proceso o política (el llamado "A/B Testing") es, en esencia, una aplicación directa de las pruebas T de dos muestras: se mide una variable de interés en ambos grupos y se determina, con base en el valor-p, si la diferencia observada es estadísticamente significativa o podría deberse simplemente al azar del muestreo.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 2](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Contenidos.md)

</div>
