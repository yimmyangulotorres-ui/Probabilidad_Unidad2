# 🔔 Distribuciones Continuas Notables: Modelado Gaussiano y Normalidad

## La distribución Normal en profundidad
La distribución **Normal (Gaussiana)** describe una variable continua mediante su **Función de Densidad de Probabilidad (PDF)**, una curva simétrica en forma de campana definida por dos parámetros: la media (μ), que ubica el centro de la curva, y la desviación estándar (σ), que controla su dispersión (qué tan "ancha" o "angosta" es la campana).

La probabilidad de que la variable caiga en un rango [a, b] corresponde al **área bajo la curva** entre esos dos puntos, calculada mediante la **Función de Distribución Acumulada (CDF)**.

## Estandarización: el puntaje Z
Cualquier variable Normal X se puede transformar en una **Normal Estándar** (media 0, desviación estándar 1) mediante la fórmula:

> Z = (X − μ) / σ

Este proceso, llamado **estandarización**, permite comparar valores de distintas distribuciones en una escala común y responder preguntas como "¿qué tan atípico es este valor?". Bajo la regla empírica, un puntaje Z mayor a 2 o 3 en valor absoluto suele considerarse un indicio de valor atípico.

## ¿Cómo se valida el supuesto de normalidad?
Asumir que una variable sigue una distribución Normal no basta con "verla" en un histograma: es necesario **demostrarlo**. Dos herramientas comunes son:

1. **Método gráfico – Gráfico Cuantil-Cuantil (Q-Q Plot):** compara los cuantiles teóricos de una Normal contra los cuantiles observados en los datos. Si los puntos se alinean aproximadamente sobre la diagonal de 45°, hay evidencia visual de normalidad.
2. **Método analítico – Test de Shapiro-Wilk:** es una prueba de hipótesis formal donde la hipótesis nula (H₀) establece que los datos provienen de una distribución Normal. Un valor-p pequeño (por ejemplo, menor a 0.05) lleva a rechazar esa hipótesis, es decir, a concluir que los datos **no** son razonablemente normales.

## Riesgo metodológico de asumir normalidad sin verificarla
Si una variable presenta un fuerte sesgo (asimetría) y, aun así, se calculan probabilidades asumiendo un modelo Normal, las conclusiones pueden ser incorrectas o engañosas — por ejemplo, subestimando la probabilidad de valores extremos. Por eso la validación de normalidad es un paso previo indispensable antes de aplicar métodos que la asumen (como muchas pruebas de hipótesis paramétricas).

## Aplicación práctica
Estos conceptos permiten calcular, por ejemplo, la probabilidad de que una variable regional (temperatura, precipitación, consumo eléctrico) caiga dentro de un rango crítico, y validar si ese cálculo es estadísticamente confiable según el grado real de normalidad de los datos.

---
<div align="left">

[![⬅️ Volver a Contenidos de la Unidad 2](https://img.shields.io/badge/⬅️_Volver_a_Contenidos-blue?style=for-the-badge)](../Contenidos.md)

</div>
