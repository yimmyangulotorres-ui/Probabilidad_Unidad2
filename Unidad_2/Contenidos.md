# 📖 Contenidos de la Unidad 2

* En este documento se presenta un breve resumen de lo visto dentro de las semanas de la Unidad 2 en la asignatura
  de Teoría de la Distribución y Probabilidad. Esta unidad da continuidad a la Unidad 1, avanzando desde el
  modelado de variables aleatorias hacia la **estadística inferencial**: distribuciones continuas notables,
  simulación del Teorema del Límite Central, estimación por intervalos de confianza, pruebas de hipótesis
  paramétricas y comparación de medias entre grupos (incluyendo ANOVA). *

### 🔹 Temas Principales
- Distribución Normal, estandarización (puntajes Z) y validación de normalidad
- Distribuciones muestrales y Teorema del Límite Central mediante simulación estocástica
- Estimación de parámetros e intervalos de confianza (Z y T de Student)
- Pruebas de hipótesis paramétricas (Z y T) y análisis del valor-p
- Comparación de medias entre dos o más grupos: pruebas T y ANOVA

---
## 📘 **Temas de la Unidad**

| 📂 **Tema** | 🧾 **Descripción del Contenido** |
|:--------------------------------------------|:-------------------------------------------------------------|
| [🔔 Distribuciones Continuas Notables](./Temas/Distribuciones_Continuas_Notables.md) | Distribución Normal, estandarización (Z), Gráfico Q-Q y Test de Shapiro-Wilk. |
| [🎲 Distribuciones Muestrales y TLC (Simulación)](./Temas/Distribuciones_Muestrales_TLC_Simulacion.md) | Demostración empírica del TLC, remuestreo y error estándar. |
| [📐 Estimación e Intervalos de Confianza](./Temas/Estimacion_Intervalos_Confianza.md) | Estimación puntual vs. por intervalos, IC con Z y T, nivel de confianza vs. precisión. |
| [🧪 Pruebas de Hipótesis (Z y T) y Valor-p](./Temas/Pruebas_de_Hipotesis_Z_T.md) | H₀/H₁, valor-p, errores Tipo I y II, significancia estadística vs. práctica. |
| [⚖️ Comparación de Medias y ANOVA](./Temas/Comparacion_de_Medias_ANOVA.md) | Pruebas T independientes/pareadas, homocedasticidad (Levene), ANOVA y pruebas post-hoc (Tukey). |

---

## 📓 **APES de la Unidad 2**

📌 Enlaces directos a los notebooks (`.ipynb`) trabajados durante los Aprendizajes Prácticos Experimentales (APE) de esta unidad.

| 📓 **Actividad** | 📝 **Tema de la Práctica** | 🔗 **Enlace** |
|:----------------|:---------------------------------------------------------------------------|:----------------------------------------------|
| APE 006 | Distribuciones Continuas Notables: Modelado Gaussiano, Estandarización y Pruebas de Normalidad | [Abrir](./Actividades/APE_007_Normal%283%29.ipynb) |
| APE 007 | Distribuciones Muestrales y Teorema del Límite Central (TLC) mediante Simulación Estocástica | [Abrir](./Actividades/APE_008_TLC%282%29.ipynb) |
| APE 008 | Inferencia Estadística: Estimación de Parámetros e Intervalos de Confianza (Z y T de Student) | [Abrir](./Actividades/APE_009_Intervalos%281%29.ipynb) |
| APE 009 | Inferencia Estadística: Pruebas de Hipótesis Paramétricas (Z y T) y Análisis del Valor-p | [Abrir](<./Actividades/APE10_Interferencia_EstadisticaPruebas_deHip%23U00f3tesis_Param%23U00e9tricas_%28Z_y_T%29_y%20An%23U00e1lisisdel_Valor-p%281%29.ipynb>) |
| APE 010 | Inferencia Estadística Multigrupo: Análisis de Varianza (ANOVA de 1 factor) y Pruebas Post-Hoc (Tukey) | [Abrir](./Actividades/APE_11_Varianza%28ANOVA%29.ipynb) |

---

## 🧩 **Otros apartados de la unidad**

- [📂 Tareas Entregadas](./Tareas_Entregadas.md)
- [📖 Contenidos de la Unidad](./Contenidos.md)

---
### 🧠 Concepto General
La **Unidad 2** da el salto de la probabilidad descriptiva hacia la **inferencia estadística**: ya no basta con describir cómo se comporta una variable aleatoria, sino que se aprende a usar una muestra de datos para **estimar, decidir y comparar** con respecto a una población completa, cuantificando siempre el margen de incertidumbre asociado a cada conclusión.

---

### 🔔 Distribuciones Continuas y Normalidad
La distribución **Normal** vuelve a ser protagonista, ahora con foco en su aplicación práctica: la **estandarización (Z)** permite comparar cualquier variable en una escala común, y herramientas como el **Gráfico Q-Q** y el **Test de Shapiro-Wilk** permiten *demostrar*, y no solo suponer, que una variable se comporta de forma normal antes de aplicar métodos que dependen de ese supuesto.

---

### 🎲 TLC mediante Simulación
Se retoma el **Teorema del Límite Central**, esta vez demostrado mediante simulación computacional: partiendo de poblaciones marcadamente asimétricas, se observa cómo la distribución de las medias muestrales converge hacia una Normal a medida que crece el tamaño de muestra, y cómo el **error estándar** decae según √n.

---

### 📐 Estimación por Intervalos de Confianza
En lugar de reportar un único número como estimación, se aprende a construir **rangos de valores plausibles** (intervalos de confianza) para un parámetro poblacional, entendiendo el compromiso entre el **nivel de confianza** exigido y la **precisión** (amplitud) del intervalo resultante.

---

### 🧪 Pruebas de Hipótesis
Se formaliza el proceso de **contrastar afirmaciones** sobre una población usando evidencia muestral: planteamiento de H₀ y H₁, cálculo del estadístico de prueba (Z o T), interpretación correcta del **valor-p**, y la diferencia crucial entre significancia estadística y significancia práctica.

---

### ⚖️ Comparación entre Grupos
Finalmente, la unidad cierra con la comparación de medias entre **dos o más grupos**: pruebas T para muestras independientes y pareadas, verificación del supuesto de homocedasticidad mediante el **Test de Levene**, y el **ANOVA** con sus pruebas post-hoc (Tukey) para comparaciones múltiples — la base estadística detrás de cualquier "A/B Testing" riguroso.

---

> 💡 *Esta unidad representa el paso de "describir la incertidumbre" a "decidir con evidencia": el corazón de la estadística aplicada a la ingeniería.*

<div align="left">

[![⬅️ Volver al Inicio](https://img.shields.io/badge/⬅️_Volver_al_Inicio-blue?style=for-the-badge)](../README.md)

</div>

---
