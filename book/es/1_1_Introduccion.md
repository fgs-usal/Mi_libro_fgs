<!-- Convertido automáticamente desde PDF. Revisar y corregir formato si es necesario. -->

## 1. Estados electrónicos en cristales 

## 1.1 Introducción 

## Física del Estado Sólido II 

1 

## 1. Estados electrónicos en cristales 

## 1.1 Introducción 

- Materiales sólidos cristalinos. Red directa y Red recíproca. 

- Simetrías en un cristal. Estados de Bloch. 

- Propiedades de la energía en sólidos. 

## 1.2 Cálculo de Estructura de Bandas: electrón cuasi-libre 

1.3 Método de Enlace Fuerte o Tight-Binding 

## 1.4 Método del Pseudopotencial 

2 

## **Materiales sólidos cristalinos** 

Constituidos por átomos. 

## Configuración electrónica: 

Los electrones que están fuera de las capas completas son los que serán responsables de las propiedades del sólido, pues se alteran fácilmente. 

## ¿Máximo número de electrones en una subcapa _nilm_ ? 

Ejemplos: configuración electrónica en el estado fundamental: 

He (Z=2) Ne (Z=10) Si (Z=14) Fe (Z=26) Cs (Z=55) 

Los gases nobles terminan con 6 electrones en el último nivel de energía 

3 

## **Simetrías en un sólido cristalino** 

## **Simetría de traslación** 

La regularidad característica de las estructuras cristalinas generalmente se formula en términos de la invarianza del cristal bajo ciertas operaciones de traslación discretas. > _ > Se dice que un sólido es cristalino si existen tres vectores no-coplanares, de manera que para tres valores enteros,                   la traslación de una posición a través del 1 1? 2? sf a,,a,,a, vector 

resulta invariante. 

## **Simetría de grupo puntual** 

Colección de operaciones de simetría que, aplicadas a un punto de la red, mantienen la red. 

4 

## **Vectores primitivos** 

son vectores primitivos si: 

Las traslaciones obtenidas mediante los enteros _m1_ , _m2_ , _m3_ reproducen todas las posiciones del cristal que son equivalentes a 

5 

## **Vectores primitivos** 

son vectores primitivos si: 

Las traslaciones ” obtenidas mediante los enteros _m1_ , _m2_ , _m3_ reproducen todas las posiciones — — del cristal que son equivalentes a 

6 

## **Red cristalina** 

## Red directa. Red de Bravais 

Un conjunto de puntos forma una red de Bravais si puedo extraer dos vectores (o tres, dependiendo de si es 2D o 3D) linealmente independientes de tal forma que todas las posiciones de la red se puedan obtener como combinación lineal de ellos con números enteros. 

Vectores primitivos 

Ejemplos de redes que no son de Bravais: 

7 

## **Red cristalina** 

## **Celda primitiva** 

En su volumen sólo hay un punto de red. 

Paralelepípedo formado por los factores primitivos, que, trasladado a lo largo de sus aristas me genera toda la red. 

Primitiva 

## **Celda elemental** 

Simetría del sistema. 

Primitiva 

## **Celda de Wigner-Seitz** 

Tiene el volumen de la celda primitiva y las propiedades de simetría de la celda elemental. 

Región de puntos más cercanos a un punto de red que cualquier otra. 

Wigner-Seitz 

Elemental 

8 

## **Red cristalina** 

## **Celda primitiva** 

En su volumen sólo hay un punto de red. 

Paralelepípedo formado por los factores primitivos, que, trasladado a lo largo de sus aristas me genera toda la red. 

Primitiva 

## **Celda elemental** 

Simetría del sistema. 

Primitiva 

## **Celda de Wigner-Seitz** 

Tiene el volumen de la celda primitiva y las propiedades de simetría de la celda elemental. 

Región de puntos más cercanos a un punto de red que cualquier otra. 

Wigner-Seitz 

Elemental 

9 

## **Periodicidad de los observables en una red** 

Una función periódica es desarrollarle en serie Fourier: 

**==> picture [52 x 14] intentionally omitted <==**

**----- Start of picture text -----**<br>
donde<br>**----- End of picture text -----**<br>


ha de cumplir la condición de periodicidad de la red de Bravais: 

Dada una red cristalina, existe otra red que cumple . y a ese conjunto de puntos del dual lo llamamos _**red recíproca**_ 

10 

## **Espacio real Espacio recíproco** 

**==> picture [17 x 19] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>**----- End of picture text -----**<br>


b 

**==> picture [250 x 39] intentionally omitted <==**

**----- Start of picture text -----**<br>
0 Vw . kx<br>0<br>**----- End of picture text -----**<br>


a 

y x 

11 

b 

## **Espacio real** 

## **Espacio recíproco** 

**==> picture [250 x 241] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>0 NYS_ NY kx<br>0 2π/a<br>**----- End of picture text -----**<br>


a y x 

12 

b 

## **Espacio real** 

## **Espacio recíproco** 

**==> picture [250 x 241] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>0 kx<br>0 2π/a 4π/a<br>**----- End of picture text -----**<br>


a 

y x 

13 

b a 

## **Espacio real** 

## **Espacio recíproco** 

**==> picture [266 x 241] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>2π/b<br>0 kx<br>0 2π/a 4π/a<br>**----- End of picture text -----**<br>


y x 

14 

**==> picture [88 x 90] intentionally omitted <==**

**----- Start of picture text -----**<br>
b<br>a<br>**----- End of picture text -----**<br>


## **Espacio real** 

## **Espacio recíproco** 

**==> picture [266 x 241] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>4π/b<br>2π/b<br>0 kx<br>ae<br>0 2π/a 4π/a<br>**----- End of picture text -----**<br>


y x 

15 

## **Espacio real Espacio recíproco** 

**==> picture [837 x 303] intentionally omitted <==**

**----- Start of picture text -----**<br>
k<br>y<br>a<br>4π/b<br>2π/b<br>0 kx<br>SS b NO |<br>0 2π/a 4π/a<br>a<br>**----- End of picture text -----**<br>


y x 

La frecuencia espacial mide con qué frecuencia se repiten las componentes sinuosidades de una estructura por unidad de distancia. 

Pregunta: ¿Cómo podemos medir experimentalmente la red directa y la red recíproca de un cristal? 

16 

## **Transformada de Fourier** 

17 

## **Planos cristalográficos** 

Existe una relación entre los vectores de la red recíproca y los planos de la red directa. 

Sea una familia de planos de red separados por una distancia $d$, existen una serie de vectores recíprocos perpendiculares a los planos, de tal manera que el más pequeño de ellos tiene una longitud de $2\pi/d$. 

Del mismo modo, para cualquier vector de red recíproca $\vec{K}$ existe una familia de planos de red normales a $\vec{K}$ y separados por una distancia $d$, donde $2\pi/d$ es la longitud del vector de red recíproca más pequeño paralelo a $\vec{K}$. 

Familia de planos atómicos: 

El vector de red recíproca más pequeño que cumple la condición de perpendicularidad nos define la distancia entre planos atómicos.

Pregunta: ¿encuentras alguna relación con la definición de onda plana en Electromagnetismo? 

18 

## **Planos cristalográficos: índices de Miller** 

Los índices de Miller de un plano de una red cristalina son las coordenadas del vector de red recíproca más corto normal al plano, con respecto a los vectores primitivos de la red recíproca, es decir: 

El plano es normal a 

https://lampz.tugraz.at/~hadley/ss1/skriptum/outline.php 

19 

## **Red recíproca (dual)** 

Dada una red de Bravais: 

Vectores primitivos 

Base primitiva recíproca: 

**==> picture [111 x 18] intentionally omitted <==**

Red recíproca: 

Si      es el volumen de la celda primitiva directa, el volumen de la celda primitiva recíproca viene dado por: 

Dada una red cristalina, existe otra red que cumple y a ese conjunto de puntos del dual lo llamamos red recíproca. 

20 

## **Zona de Brillouin** 

n-ésima zona de Brilloiun de la red directa: n-ésima zona de Wigner-Seitz de la red recíproca 

Las celdas de Wigner-Seitz del espacio recíproco son las zonas de Brillouin del espacio directo 

Espacio recíproco. Cualquier vector del espacio recíproco se puede expresar como: 

Cualquier vector de onda lo puedo expresar como un vector de la 1ª zona de Brillouin más un vector de red recíproca. 

Referencia: Kittel 

21 

## **Zona de Brillouin** 

Ejemplo: definición de las zonas de Brillouin en una red hexagonal. 

22 

## **Tipos de redes cristalinas (2D)** 

## Redes de Bravais 

## Celdas de Wigner-Seitz 

23 

## **Tipos de redes cristalinas (3D)** 

## **3D** 

24 

## **Sistema de red recíproca vs Sistema de red directa** 

25 

## **Posiciones atómicas** 

La estructura cristalina está determinada por la red de Bravais y su base. 

Posiciones cristalinas: 

No podrá haber un cristal en el que unos átomos tengan la simetría de una red y otros de otra: esencia de la traslacionalidad. 

Cristales con distinta estructura pueden compartir la misma red de Bravais. 

26 

## **Hamiltoniano de un sólido** 

Consideremos un sistema físico formado por electrones de enlace y por iones: 

27 

## **Hamiltoniano de un sólido** 

Consideremos un sistema físico formado por electrones de enlace y por iones: 

Cálculo de la energía: 

28 

## **Hamiltoniano de un sólido** 

Idea: Si separamos el H como suma de los H de cada partícula, 

podríamos expresar la energía total, y la función de onda del sistema como: 

pudiendo resolver para cada partícula: 

Pregunta: ¿podemos separar el H como suma de los H de cada partícula en nuestro sólido? 

29 

## **Hamiltoniano de un sólido** 

Pregunta: ¿podemos separar el H como suma de los H de cada partícula en nuestro sólido? 

no es separable 

Primera aproximación: realizar un planteamiento perturbativo 

La solución a orden cero: 

donde: 

y como las coordenadas electrónicas e iónicas son separables: 

30 

## **Hamiltoniano electrónico** 

El hamiltoniano electrónico tampoco es separable, pues tenemos un término de acoplamiento: 

## Hamiltoniano monoelectrónico: 

con 

donde este último término se puede obtener mediante distintas aproximaciones (Hartree, Hartree-Fock, etc.) 

31 

## **Hamiltoniano electrónico en un cristal** 

Hamiltoniano monoelectrónico: 

En un cristal, _V_ va a tener todas las propiedades de simetría del mismo, por tanto ha de ser invariable a perturbaciones del vector de red: 

Estudiando las propiedades de simetría de un cristal podré deducir sus estados y las propiedades de sus observables. 

_Idea_ : Nos valdremos de las simetrías para encontrar las funciones de onda 

## Simetría traslacional 

Simetría de grupo puntual 

32 

## **Simetría traslacional. Funciones de Bloch** 

Derivemos qué expresión debe de tomar 

Las funciones exponenciales cumplen esa propiedad, por tanto elegimos: 

**==> picture [447 x 23] intentionally omitted <==**

33 

## **Teorema de Bloch** 

Cualquier función propia del operador traslación se puede poner como una onda plana por una función periódica con vector de red 

**==> picture [52 x 14] intentionally omitted <==**

Esto quiere decir que un estado electrónico del cristal (propio de _H_ ), tiene que ser función de Bloch (pues ) 

Nota: a partir del teorema de Bloch se puede deducir fácilmente que 

Casos límites: 

1. Si             varía lentamente con u; (7) 2. Si             está muy localizada u; (7) 

**==> picture [93 x 18] intentionally omitted <==**

estados atómicos 

35 

## **Cristal finito. Condiciones de Born-Von Karman** 

La simetría de traslación se rompe al considerar un cristal finito. Esto nos va a restringir los valores permitidos para k 

Consideremos una red cúbica de lado 

Condición de frontera periódica: 

En tres dimensiones: 

Si asumimos una onda plana: 

La condición de periodicidad requiere: 

De modo que: 

enteros 

Los valores de _ki_ que cumplen las condiciones de frontera son aquellos múltiplos de 

36 

## **Cristal finito. Condiciones de Born-Von Karman** 

En dos dimensiones: 

Al aplicar la condición de periodicidad: 

**==> picture [59 x 11] intentionally omitted <==**

**----- Start of picture text -----**<br>
enteros<br>**----- End of picture text -----**<br>


Aplicando la condición de frontera a una red cúbica de lado L, obtenemos un _k_ permitido en la 1ª zona de Brillouin: 

**==> picture [403 x 524] intentionally omitted <==**

**----- Start of picture text -----**<br>
y<br>x<br>3<br>L<br>k<br>e dl y ° °<br>° ° ° °<br>kx<br>+0 * ° °<br>2π/L<br>**----- End of picture text -----**<br>


37 

## **Cristal finito. Condiciones de Born-Von Karman** 

**==> picture [11 x 16] intentionally omitted <==**

**----- Start of picture text -----**<br>
y<br>**----- End of picture text -----**<br>


Si consideramos cuatro redes cuadradas de lado L: 

Al aplicar la condición de periodicidad: 

**==> picture [10 x 12] intentionally omitted <==**

**----- Start of picture text -----**<br>
x<br>**----- End of picture text -----**<br>


**==> picture [7 x 10] intentionally omitted <==**

**----- Start of picture text -----**<br>
L<br>**----- End of picture text -----**<br>


enteros 

k y 

Obtenemos cuatro _k_ permitidos en la 1ª zona de Brillouin: 

kx 

2π/L 

38 

## **Cristal finito. Condiciones de Born-Von Karman** 

La simetría de traslación se rompe al considerar un cristal finito. Esto nos va a restringir los valores permitidos para k 

Consideremos un cristal finito formado por N celdas primitivas donde 

Condición de frontera periódica: 

Aplicando el teorema de Bloch: 

de donde: 

El número de valores de _k_ permitidos es el número de celdas consideradas en el cristal 

39 

## **Propiedades de la energía a partir de la simetría de traslación** 

Ya sabemos que podemos considerar un H monoelectrónico: 

Hemos de resolver la ecuación de Schrödinger: 

Una función que cumpla la condición de Born-Von Karman se puede expandir en ondas planas: 

donde la suma es sobre los vectores de onda permitidos por Born-Von Karman 

Como el potencial es periódico con la red, su expansión en ondas planas sólo contendrá las que tengan la periodicidad de la red, es decir, los vectores de red recíproca : 

donde la suma es sobre todos los vectores de red recíproca 

donde: 

y para cristales con simetría de inversión: 

40 

## **Propiedades de la energía a partir de la simetría de traslación** 

Podemos entonces reescribir la ecuación de Schrödinger como: 

donde 

resultando 

Como la base formada por las ondas planas que cumplen las condiciones de Born-Von Karman es ortogonal: 

Si escribimos de modo que 

41 

## **Propiedades de la energía a partir de la simetría de traslación** 

y haciendo un cambio de variable: 

Para               el sistema de ecuaciones resultante para todos los vectores de red recíproca acopla sólo los keV coeficientes                            cuyo vector de onda difiere de     en un vector de red recíproca. CECeg Cg k 

Hemos simplificado el problema original en un sistema de N ecuaciones: una para cada Cada una de estas ecuaciones tiene soluciones que son superposiciones de ondas planas que contienen a    y k vectores de onda que difieren de     en un vector de red recíproca. k 

Podemos escribir ahora nuestra función de onda como: 

¿Podemos reescribirla como una función de Bloch? 

42 

## **Propiedades de la energía a partir de la simetría de traslación** 

Dado un               existen infinitas soluciones de la ecuación de Schrödinger. keV,., Aunque ya lo hemos visto antes, podemos verlo también si directamente partimos de una función tipo Bloch: 

Sustituyendo en la ecuación de Schrödinger. 

- Se trata de un sistema de N ecuaciones (según la condición de Born-Von Karman). 

- Cada una de ellas tiene una familia infinita de soluciones, donde los autovalores dependen de un n. 

- índice discreto, el índice de banda, 

Los estados propios vienen caracterizados por: 

45 

## **Propiedades de la energía a partir de la simetría de traslación** 

Dado un _n_ , las autofunciones y autovalores son funciones periódicas en con la red recíproca 

Para cada _n_ banda de , el conjunto de estados electrónicos especificado por            recibe el nombre de E,(k) energía. Al tratarse de una función periódica y continua, está acotada, teniendo un límite inferior y otro superior. 

Se puede demostrar que: 

Si se tratase al electrón como una partícula clásica, la velocidad para ese estado de energía sería: 

en los extremos de la 1ª zona de Brillouin la energía es extremal en    . i 

46 

## **Simetría del grupo puntual** 

Todos los estados obtenidos aplicando la operación de simetría de grupo puntual tienen los mismos valores de energía. 

Se demuestra que: 

> es decir, los valores de energía en un punto    y en otro resultante de aplicar las propiedades de simetría del k grupo puntual tienen los mismos valores de energía. 

**No es necesario calcular la estructura de bandas en la 1ª zona de Brillouin, sino en la zona irreducible.** 

1ª zona de Brillouin 1ª zona de Brillouin de la red fcc de la red bcc 

1ª zona de Brillouin de la red hexagonal 

Referencia: Marder 

47 

## **Consideraciones generales sobre bandas** 

El número de puntos en cada banda (N) depende del número de celdas consideradas. 

El número de bandas depende del número de _k_ considerados. 

**==> picture [342 x 12] intentionally omitted <==**

**----- Start of picture text -----**<br>
5 celdas 40 celdas<br>**----- End of picture text -----**<br>


## Representación en zona repetida 

## Representación en zona extendida 

48 

## **Superficie de Fermi** 

- Si tenemos **N electrones libres** , su estado fundamental se construye ocupando todos los niveles con energías 

donde _EF_ se determina exigiendo que el número total de niveles monoelectrónicos con energías menores que _EF_ sea igual al número total de electrones. 

• Si tenemos **N electrones de Bloch** , la construcción de su estado fundamental es similar, excepto que los niveles monoelectrónicos se etiquetan con n y   ,           no sigue la función sencilla de electrón libre, y k E,(k) kev, (si cada nivel se cuenta sólo una vez). Pueden ocurrir dos cosas: 

1. Que unas bandas queden totalmente llenas y otras vacías. La diferencia de energías entre el nivel más alto ocupado y el más bajo desocupado, se conoce como banda prohibida o gap. Dependiendo de la temperatura, es el caso de **aislantes o semiconductores** . 

2. Las bandas quedan parcialmente llenas. En este caso, la energía del nivel más alto ocupado, _EF_ , cae en el rango de una o más bandas. Para cada una de las bandas parcialmente ocupadas, existirá una superficie en el espacio recíproco que separa los niveles ocupados de los desocupados. El conjunto de esas superficies se conoce como superficie de Fermi. Se trata del caso de **metales** . 

49 

## **Superficie de Fermi** 

Ejemplos de superficies de Fermi: 

50 

## **Densidad de Estados** 

Nos puede interesar calcular cantidades observables que se correspondan con sumas sobre los distintos niveles electrónicos, del tipo: 

> _n_ k donde para cada , tenemos la suma sobre todos los     dentro de la celda primitiva. 

En el límite de un cristal muy grande: 

donde la integral es sobre la celda primitiva. _n_ Si            depende de y     solamente a través de la energía,          , podemos definir una densidad de estados por unidad de volumen,          , de manera que: 0, (z) k a(e) E,(k) q = | ¢(Z)O(£)aE donde                                  y por tanto la densidad de niveles en la banda n viene dada por: s(E)= de, (2) 

51 

## **Estructura de bandas** 

**==> picture [22 x 25] intentionally omitted <==**

**----- Start of picture text -----**<br>
L<br>52<br>**----- End of picture text -----**<br>


Referencia: Marder 

## **Estructura de bandas: Metales** 

## Aluminio: 

Bandas calculadas con el método de pseudopotencial Aprox. electrón libre Comportamiento de cuasielectrón libre 

## Cobre: 

Comportamiento híbrido entre electrones 3d (más ligados) y los 4s (más libres) Método de calculo de bandas más usado: método de pseudopotencial 

Referencia: Marder 

53 

## **Estructura de bandas: Aislantes** 

## Krypton: 

Método de calculo de bandas más usado: método de tightbinding 

Referencia: Marder 

En los gases nobles todos los electrones están en capas cerradas, impidiendo su transporte. El sólido se puede describir de dos maneras: 

- Como un conjunto de átomos prácticamente independientes. 

- Como bandas estrechas completas. 

Un sólido se suele considerar aislante si Egap>2 eV 

54 

## **Estructura de bandas: Semiconductores** 

**==> picture [74 x 14] intentionally omitted <==**

**----- Start of picture text -----**<br>
Grafeno:<br>**----- End of picture text -----**<br>


Método de calculo de bandas más usado: método de tightbinding o pseudo potencial 

## Característica interesante del grafeno: estado degenerado en el nivel de Fermi en el punto K. 

**==> picture [51 x 14] intentionally omitted <==**

**----- Start of picture text -----**<br>
Silicio:<br>**----- End of picture text -----**<br>


Método de calculo de bandas más usado: método de tightbinding o pseudo potencial 

Un sólido se suele considerar aislante si Egap<2 eV 

Referencia: Marder 

55 

## **Bibliografía recomendada:** 

Neil W. Ashcroft, N. David Mermin, “Solid State Physics”, Holt-Saunders International Editions. Jenö Sólyom, “Fundamentals of the Physics of Solids, Volume 1 - Structure and Dynamics”, Springer. Michel P. Marder, “Condensed Matter Physics”, John Wiley & Sons. C. Kittel, “Introduction to Solid State Physics”, John Wiley & Sons. G. Grosso, G. P. Parravicini, “Solid State Physics”, Academic Press. W. Harrison, “Electronic Structure and the properties of Solids”, Dover. 

P. Hoffman, “Solid State Physics”, Wiley-VCH. 

56 



---

## Imágenes extraídas


```{image} 1_1_Introduccion_images/page1_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page2_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page3_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page4_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page4_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page4_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page4_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img49.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img50.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img51.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img52.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img53.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img54.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img55.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img56.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img57.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img58.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img59.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img60.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img61.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img62.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img63.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page5_img64.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img49.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img50.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img51.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img52.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img53.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img54.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img55.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img56.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img57.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img58.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img59.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img60.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img61.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img62.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img63.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img64.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img65.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img66.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img67.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img68.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img69.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img70.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img71.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img72.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img73.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img74.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img75.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page6_img76.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page7_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page7_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page7_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page8_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img49.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img50.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img51.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img52.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img53.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img54.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img55.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page9_img56.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page10_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page11_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page12_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page13_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page14_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page15_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page16_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page17_img1.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page17_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page17_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img49.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img50.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img51.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img52.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img53.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img54.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img55.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img56.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img57.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page18_img58.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page19_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page19_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page19_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page20_img10.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page21_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page21_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page21_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page21_img4.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page22_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page23_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page23_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page23_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page24_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page24_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page25_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page26_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page26_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page26_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page26_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page26_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page27_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page28_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page28_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page28_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page29_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page29_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page29_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page29_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page30_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page30_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page30_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page30_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page30_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page31_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page32_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page33_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page34_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page35_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page36_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img35.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img36.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img37.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img38.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img39.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img40.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img41.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img42.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img43.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img44.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img45.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img46.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img47.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img48.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img49.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img50.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img51.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img52.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img53.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img54.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img55.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img56.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img57.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img58.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img59.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img60.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img61.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img62.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img63.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img64.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img65.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img66.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img67.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img68.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img69.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img70.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img71.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img72.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img73.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img74.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img75.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img76.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img77.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img78.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img79.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img80.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img81.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img82.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img83.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img84.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img85.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img86.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img87.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img88.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img89.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img90.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img91.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img92.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img93.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img94.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img95.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img96.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img97.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img98.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img99.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img100.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page37_img101.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page38_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page39_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page40_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page41_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page42_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page43_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page44_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page45_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page45_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page46_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page46_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page46_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page46_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page47_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page48_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page49_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page49_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page49_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page50_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page50_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page51_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page52_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_1_Introduccion_images/page52_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```
