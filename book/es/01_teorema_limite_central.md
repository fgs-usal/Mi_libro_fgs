(cap-teorema-limite-central)=
# El Teorema del Límite Central

El **Teorema del Límite Central (TLC)** es uno de los resultados más importantes y sorprendentes de la teoría de la probabilidad y la estadística. Este teorema explica por qué la distribución normal (o campana de Gauss) aparece con tanta frecuencia en la naturaleza, la ciencia y la ingeniería.

En este capítulo exploraremos su definición formal, sus implicaciones prácticas y veremos cómo se comporta cuando aumentamos el tamaño de la muestra.

---

## Definición Formal

```{admonition} Teorema del Límite Central
:class: tip

Sean $X_1, X_2, \dots, X_n$ variables aleatorias independientes e idénticamente distribuidas (i.i.d.) con media poblacional finita $\mu$ y desviación estándar finita $\sigma > 0$.

Si definimos el promedio muestral como:

$$
\bar{X}_n = \frac{1}{n} \sum_{i=1}^n X_i
$$

Entonces, a medida que el tamaño de la muestra $n$ tiende a infinito ($n \to \infty$), la distribución de la variable estandarizada $Z_n$ converge en distribución a una distribución normal estándar $\mathcal{N}(0, 1)$:

$$
Z_n = \frac{\bar{X}_n - \mu}{\sigma / \sqrt{n}} \xrightarrow{d} \mathcal{N}(0, 1)
$$ (eq-clt-es)
```

Como se observa en la ecuación {eq}`eq-clt-es`, la distribución del promedio muestral se aproxima a una distribución normal con media $\mu$ y varianza $\sigma^2 / n$, sin importar cuál sea la distribución de probabilidad original de las variables aleatorias $X_i$ individuales.

---

## Implicaciones Didácticas

¿Por qué es tan importante este teorema en la práctica docente y científica?

1. **Inferencia Estadística**: Permite aproximar e inferir parámetros poblacionales (como medias y proporciones) utilizando la distribución normal, incluso si la población original no es normal.
2. **Intervalos de Confianza**: Da soporte teórico para el cálculo de intervalos de confianza y pruebas de hipótesis tradicionales para muestras suficientemente grandes (usualmente $n \ge 30$).
3. **Simplicidad**: Simplifica modelos matemáticos complejos al aproximar sumas de efectos aleatorios independientes mediante una distribución Gaussiana única.

---

## ¿Cómo se comporta en la práctica?

```{admonition} Pregunta de Reflexión: ¿Qué tan grande debe ser la muestra $n$?
:class: dropdown

El ritmo de convergencia hacia la distribución normal depende directamente de la simetría de la distribución original de las variables aleatorias:
- **Distribuciones Simétricas** (como la distribución uniforme): Convergen de forma extremadamente rápida. Incluso con muestras pequeñas como $n = 5$ o $n = 10$, el promedio ya tiene una forma muy similar a la normal.
- **Distribuciones Asimétricas o Sesgadas** (como la exponencial o la de Pareto): Requieren muestras significativamente más grandes ($n \ge 30$ o incluso $n \ge 100$) para que la asimetría original desaparezca en el promedio muestral.

Esta diferencia es fundamental al diseñar experimentos y análisis estadísticos en el aula de ciencias.
```

---

## Visualización Conceptual del Teorema

Imaginemos que lanzamos un dado común de 6 caras. La distribución de probabilidad de obtener cualquier puntuación del 1 al 6 es uniforme (todos los resultados tienen una probabilidad de $1/6$).

- **Si lanzamos 1 dado ($n = 1$)**: La distribución es completamente plana (uniforme).
- **Si lanzamos 2 dados y promediamos sus valores ($n = 2$)**: La distribución del promedio tiene forma triangular (el 3.5 es el valor más probable).
- **Si lanzamos 10 dados y promediamos ($n = 10$)**: La distribución resultante es una campana suave, casi indistinguible de una distribución normal perfecta.
