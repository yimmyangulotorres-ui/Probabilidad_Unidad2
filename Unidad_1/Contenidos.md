# 📖 Contenidos de la Unidad 1

* En este documento se presenta un breve resumen de lo visto dentro de las semanas de la Unidad 1 en la asignatura
  de Teoría de la Distribución y Probabilidad. Si quiere profundizar más en los diferentes temas, ejercicios y
  prácticas realizadas dentro de esta Unidad, puede dirigirse al índice de contenido. En este apartado encontrará
  la información desglosada desde el primer tema visto en la asignatura hasta el último tratado en clase, con una
  estructura apta para la comprensión del lector: desde los fundamentos de probabilidad y espacios muestrales,
  pasando por variables aleatorias y sus distribuciones, hasta las distribuciones muestrales que preparan el
  terreno para la inferencia estadística de la Unidad 2. *

### 🔹 Temas Principales
- Experimentos aleatorios, espacio muestral y eventos
- Operaciones entre eventos y probabilidad condicional
- Enfoques clásico, empírico y subjetivo de la probabilidad
- Variables aleatorias discretas y continuas
- Funciones de Masa (PMF), Densidad (PDF) y Distribución Acumulada (CDF)
- Esperanza matemática, varianza y momentos estadísticos
- Distribuciones discretas notables: Binomial y Poisson
- Distribuciones muestrales, Teorema del Límite Central, t de Student y Chi-cuadrado

---
## 📘 **Temas de la Unidad**

| 📂 **Tema** | 🧾 **Descripción del Contenido** |
|:--------------------------------------------|:-------------------------------------------------------------|
| [🎲 Fundamentos de Probabilidad y Espacios Muestrales](../Temas/Fundamentos_de_Probabilidad.md) | Experimento aleatorio, espacio muestral, eventos, operaciones entre conjuntos y enfoques de probabilidad. |
| [📊 Variables Aleatorias y Distribuciones de Probabilidad](../Temas/Variables_Aleatorias_y_Distribuciones.md) | Variables discretas y continuas, PMF, PDF, CDF, y una primera mirada a las distribuciones Binomial y Normal. |
| [➗ Esperanza Matemática y Momentos](../Temas/Esperanza_Matematica_y_Momentos.md) | Esperanza, varianza, desviación estándar y estimadores muestrales insesgados. |
| [🎯 Distribuciones Discretas Notables](../Temas/Distribuciones_Discretas_Notables.md) | Distribución Binomial, distribución de Poisson y su aproximación mutua. |
| [🔔 Distribuciones Muestrales y TLC](../Temas/Distribuciones_Muestrales_y_TLC.md) | Teorema del Límite Central, error estándar, distribución t de Student y Chi-cuadrado. |

---

## 📓 **APES de la Unidad 1**

📌 Enlaces directos a los notebooks (`.ipynb`) trabajados durante los Aprendizajes Prácticos Experimentales (APE) de esta unidad.

| 📓 **Actividad** | 📝 **Tema de la Práctica** | 🔗 **Enlace** |
|:----------------|:---------------------------------------------------------------------------|:----------------------------------------------|
| APE 00 | Fundamentos de Probabilidad y Espacios Muestrales | [Abrir](./APES/APE00.ipynb) |
| APE 01 | Variables Aleatorias y Distribuciones de Probabilidad | [Abrir](./APES/APE01%282%29.ipynb) |
| APE 02 – Grupal | Variables Aleatorias Discretas y Continuas | [Abrir](./APES/APE02_Grupal%281%29%281%29.ipynb) |
| APE 03 – Grupo D | Variables Aleatorias Discretas y Continuas | [Abrir](./APES/APE03_GrupoD.ipynb) |
| APE 04 – Grupo D | Distribuciones Discretas Notables: Modelado y Simulación de Procesos de Bernoulli y Eventos Raros | [Abrir](./APES/APE_04__GrupoD%282%29.ipynb) |
| APE 05 – Grupo D | Distribuciones Continuas Notables: Modelado Gaussiano, Estandarización y Pruebas de Normalidad | [Abrir](./APES/APE_05__GrupoD%282%29.ipynb) |

---

## 🧩 **Otros apartados de la unidad**

- [📂 Tareas Entregadas](./Tareas_Entregadas.md)  
- [📖 Contenidos de la Unidad](./Contenidos.md)  
- [💬 Reflexión Personal](./Reflexion.md)  
- [🧾 Evidencias](../Evidencias/)
---
### 🧠 Concepto General
La **Unidad 1** se enfoca en los fundamentos de la **teoría de la probabilidad**, introduciendo al estudiante en el razonamiento bajo incertidumbre, el modelado de fenómenos aleatorios y las bases matemáticas que sostienen toda la estadística inferencial que se desarrolla en la Unidad 2.

En esta etapa se busca que el estudiante comprenda que **todo fenómeno incierto puede describirse mediante un modelo probabilístico**, y que dominar los conceptos de espacio muestral, variable aleatoria y distribución de probabilidad es esencial para tomar decisiones informadas a partir de datos.

El objetivo principal es **transformar la incertidumbre de un problema real en un modelo matemático manejable**, capaz de generar predicciones, calcular riesgos y validar afirmaciones con evidencia [1].

---

### 🎲 Fundamentos de Probabilidad
Un **experimento aleatorio** es un proceso cuyo resultado no puede predecirse con certeza. El conjunto de todos sus resultados posibles se llama **espacio muestral**, y cualquier subconjunto de interés dentro de él es un **evento**.

Existen tres enfoques para asignar una probabilidad a un evento: el **clásico** (resultados igualmente probables), el **empírico** (basado en la frecuencia relativa observada al repetir el experimento) y el **subjetivo** (basado en el juicio o experiencia de quien la estima).

#### 🔸 Conceptos clave:
- **Probabilidad condicional:** la probabilidad de un evento dado que otro ya ocurrió.
- **Independencia:** dos eventos son independientes si la ocurrencia de uno no afecta la probabilidad del otro.
- **Eventos mutuamente excluyentes:** no pueden ocurrir al mismo tiempo (su intersección es vacía).

> 💬 *La probabilidad es el lenguaje matemático con el que se describe formalmente la incertidumbre.*

---

### 📊 Variables Aleatorias y sus Distribuciones
Una **variable aleatoria** asigna un número a cada resultado de un experimento, permitiendo tratar la incertidumbre de forma numérica y cuantitativa.

- Las variables **discretas** se describen con una **Función de Masa de Probabilidad (PMF)**.
- Las variables **continuas** se describen con una **Función de Densidad de Probabilidad (PDF)**.
- Ambas comparten la **Función de Distribución Acumulada (CDF)**, que acumula probabilidad hasta un punto dado.

Las distribuciones **Binomial** (para conteos de éxito/fracaso) y **Normal** (para fenómenos continuos con forma de campana) son los dos modelos de referencia más utilizados en ingeniería.

#### 🔹 Aplicaciones reales:
- Control de calidad de componentes electrónicos.
- Tiempos de respuesta de sistemas y servidores.
- Modelado de mediciones físicas y ambientales.
- Estimación de riesgos en procesos industriales.

---

### ➗ Esperanza Matemática y Dispersión
La **esperanza matemática** (E[X]) resume el valor "central" esperado de una variable aleatoria, mientras que la **varianza** cuantifica qué tan dispersos están sus valores alrededor de ese centro. Ambas se estiman, en la práctica, mediante la **media muestral** y la **varianza muestral** de un conjunto de datos, usando la corrección de grados de libertad (n−1) para obtener estimadores insesgados.

---

### 🎯 Distribuciones Discretas Notables
La distribución **Binomial** modela un número fijo de ensayos independientes de éxito/fracaso, mientras que la distribución de **Poisson** modela el número de eventos raros ocurridos en un intervalo de tiempo o espacio. Cuando el número de ensayos es grande y la probabilidad de éxito es pequeña, la Binomial se aproxima a la Poisson.

---

### 🔔 Del Teorema del Límite Central a la Inferencia
El **Teorema del Límite Central** es, quizás, el resultado más importante de esta unidad: garantiza que la distribución de las medias muestrales tiende a una Normal sin importar la forma de la población original. Este resultado, junto con las distribuciones **t de Student** y **Chi-cuadrado**, sienta las bases para construir intervalos de confianza y pruebas de hipótesis, temas centrales de la Unidad 2.

---

> 💡 *Esta unidad representa el paso del razonamiento probabilístico puro hacia la estadística inferencial: de describir la incertidumbre, a usarla para tomar decisiones basadas en evidencia.*


 <div align="left">

[![⬅️ Volver al Inicio](https://img.shields.io/badge/⬅️_Volver_al_Inicio-blue?style=for-the-badge)](../README.md)

</div>

---
