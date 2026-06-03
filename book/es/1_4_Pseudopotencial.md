<!-- Convertido automáticamente desde PDF. Revisar y corregir formato si es necesario. -->

## 1. Estados electrónicos en cristales 

1.4 Método del Pseudopotencial 

## Física del Estado Sólido II 

1 

## 1. Estados electrónicos en cristales 

## 1.1 Introducción 

## 1.2 Cálculo de Estructura de Bandas 

1.3 Método de Enlace Fuerte o Tight-Binding 1.4 Método del Pseudopotencial 

2 

## **Recordatorio: aproximación de partícula cuasi libre** 

En la aproximación de electrón cuasi-libre, encontramos que el efecto del potencial periódico es la ruptura de la degeneración en los extremos de la zona de Brillouin. En esta aproximación tratábamos al potencial periódico como una perturbación, tomando una base de ondas planas, de manera que la ecuación secular tomaba la forma: 

siendo            el coeficiente que corresponde a la onda plana       del desarrollo en serie de Fourier del potencial. Dicho de otra manera, la matriz hamiltoniana en la base de ondas planas es: 

Pero en la mayoría de los casos no podemos suponer que el potencial sea débil, de manera que la función de onda no es parecida a una onda plana. 

Ahora bien, la función de onda se puede escribir como una función de Bloch, y hemos de esperar que el factor periódico modulador de dicha función provoque que en las proximidades de los iones la función de u,(7) onda varíe fuertemente con r (como una función de onda atómica), y que entre iones se comporte de forma parecida a una onda plana. 

3 

## **Estados ligados vs Estados no ligados** 

En un gran número de cristales, los estados electrónicos se pueden separar en dos tipos: 

- **Estados ligados** , muy localizados espacialmente. Darán lugar a las bandas más profundas debidas a los electrones ligados a los iones (core electrons), localizados en torno a las posiciones de los núcleos. 

- **Estados de valencia y/o conducción** , deslocalizados. Darán lugar a las bandas de valencia y/o de conducción. 

Las **ondas planas** reproducen bien las funciones de onda electrónicas de valencia, pero fallan a la hora de reproducir las funciones de onda cerca de los núcleos (o dicho de otro modo, se necesitarían muchas ondas planas para reproducirlas correctamente). 

Los **orbitales atómicos** de tipo Bloch reproducen bien las funciones de onda en los núcleos, pero fallan en el resto de posiciones. 

Para considerar ambos aspectos, preparamos la siguiente función de onda: 

donde la suma es sobre todos los niveles ligados (del core) con vector de onda de Bloch 

4 

## **Método del pseudopotencial** 

donde la suma es sobre todos los niveles ligados (del core) con vector de onda de Bloch Los           se pueden asumir LCAO, y cumplen: ¢; (7) 

Las constantes se obtienen imponiendo que sea ortogonal a cada nivel 

Por tanto nuestras nuevas funciones de onda serán del estilo: 

5 

## **Método del pseudopotencial** 

si sustituimos: pero sabemos que las funciones core verifican: 

de manera que hemos encontrado una nueva ecuación de Schrödinger para Teniendo en cuenta que: H=T+V=H)+V **:** Podemos definir un nuevo operador “potencial”, el **pseudopotencial** 

y la ecuación de Schrödinger para queda: 1,(7) {H,+V,,}z,)= (Bla) “pseudo función de onda” Pregunta 1: ¿Es E también una “pseudo-energía”? Pregunta 2: ¿Cuál es la norma de esta pseudo función de onda? 6 

## **Método del pseudopotencial** 

7 

## **Método del pseudopotencial** 

## es positivo puesto que 

ya que el primero corresponde a la energía de los estados de las bandas y el segundo a niveles profundos en el ion. 

> Por otro lado,           al ser atractivo (interacción efectiva de los iones y los demás v(7) electrones sobre un electrón genérico), es negativo. 

> Por tanto,                                    es un potencial que varía más lentamente con V,,.(7,E(k))=V+V, 7 que         : el nuevo hamiltoniano es susceptible de ser tratado en la aproximación V (7) cuasi libre, es decir, parece posible que pueda ser desarrollado en ondas planas. 

8 

## **Método del pseudopotencial** 

**Problema:** es no local. Hay una expresión integral de por medio y aparece como parámetro la energía que queremos calcular. 

¿Qué significa que                      sea no local? v,,(7,£(E)) 

Su efecto sobre una función de onda ya no consiste en simplemente multiplicar por una función de    . . 

Que el pseudopotencial dependa de la energía del nivel que estamos buscando implica que muchos de los teoremas básicos que solemos aplicar (como la ortogonalidad de autofunciones pertenecientes a distintos autovalores) no se pueden aplicar al nuevo hamiltoniano. 

Solución en primera aproximación: sustituir términos no locales por una aproximación local 

9 

## **Método de ondas planas ortogonalizadas** 

Por ejemplo, podemos plantear un desarrollo en ondas planas del tipo: 

Método de ondas planas ortogonalizadas (OPW) 

En ese caso, si queremos resolver la ecuación secular, hemos de calcular las componentes de Fourier del pseudopotencial: 

donde de nuevo tenemos el problema de la no localidad del pseudopotencial. 

10 

## **Aproximación local del pseudopotencial** 

Para hacer la aproximación local del pseudopotencial, basta con hacer la transformada inversa de Fourier: 

Además, en la aproximación local, podemos poner como suma de contribuciones de cada ión, de manera que en el caso general de varios iones por celda tenemos: 

posición del ión de tipo en la celda primitiva vector de red cristalina 

11 

## **Aproximación local del pseudopotencial** 

La transformada de Fourier vendrá dada por: 

Siendo: 

- Factor de forma 

del ion    , siendo 64 @) el volumen de la celda primitiva, con     el número de celdas N primitivas en el volumen , del cristal. 

- Factor de estructura 

## Por tanto el pseudopotencial se aproxima como: 

Si escogemos ondas planas 

12 

## **Factores de forma y de estructura para dos átomos por celda primitiva** 

Pongamos el origen de coordenadas en el punto medio entre los dos iones, que viene dado por: 

- Factor de forma simétrico 

- Factor de forma antisimétrico 

- Factor de estructura simétrico 

- Factor de estructura antisimétrico 

13 

## **Factores de forma y de estructura para dos átomos por celda primitiva** 

Llegados a este punto, y asumiendo que puedo suponer que el pseudopotencial varía lentamente en el espacio, podemos suponer que el número de ondas planas que intervienen en el desarrollo de este es considerar a potencial pequeño, y aquellas correspondientes **vectores de red recíproca pequeños** . Se puede prescindir del término V0 pues los potenciales están definidos salvo constante, o lo que es lo mismo, dicho término da un desplazamiento en energía. Por tanto el potencial viene desarrollado por un número no muy elevado de factores de forma. 

Para resolver la ecuación secular necesitamos los factores de forma. ¿Cómo proceder? 

- Calculando el pseudopotencial a partir de los potenciales verdaderos (Método ab initio). 

- Ajustar los factores de forma a los datos experimentales (Método EPM, Empirical pseudopotential model). 

- Plantear modelos de potencial, es decir, expresiones sencillas dependientes de parámetros que posteriormente se eligen de forma que concuerden adecuadamente a los datos experimentales. No deja de ser una variante del modelo anterior. 

14 

## **Método EPM (Empirical Pseudopotential Method)** 

Inicio: 

Comparar con experimento Modificar 

15 

## **Factores de estructura** 

Ejercicio: Calcula los términos de pseudopotencial para vectores de red recíproca cuyos modulos sean los tres más pequeños distintos de 0 para el NaCl y el CsCl. 

16 

## **Solución: NaCl** 

## **FCC** 

: Los vectores de red recíproca más pequeños son 

17 

## **Solución: CsCl** 

**CS** Los vectores de red recíproca más pequeños son: 

18 

## **Términos del pseudopotencial para semiconductores** 

Extraido de P. Y. Yu y M. Cardona 



---

## Imágenes extraídas


```{image} 1_4_Pseudopotencial_images/page1_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page2_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page3_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page3_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page3_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page3_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page3_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page4_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page4_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page5_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page6_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page7_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page8_img6.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page9_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page9_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page9_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page9_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page10_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page10_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page11_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page12_img11.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page13_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page14_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page15_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page17_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page18_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_4_Pseudopotencial_images/page19_img1.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```
