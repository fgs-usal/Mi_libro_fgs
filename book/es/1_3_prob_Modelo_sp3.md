<!-- Convertido automáticamente desde PDF. Revisar y corregir formato si es necesario. -->

## Problema resuelto 

Estructura de bandas del silicio en la aproximación tight binding. Modelo sp3 

## Física del Estado Sólido II 

## **Estructura de bandas del silicio en la aproximación tight binding. Modelo sp[3]** 

La aproximación tight binding supone que el electrón está muy ligado al átomo, de forma que su comportamiento está principalmente definido por los orbitales atómicos del propio átomo: 

así pues podemos considerar que las funciones de onda del hamiltoniano atómico forman una buena base para representar nuestro cristal. 

En este caso tenemos un cristal con dos tipos de átomos por celda primitiva, de tipo diamante. 

El resto de los átomos del cristal se podrán obtener por traslación con vectores de red directa: 

2 

en nuestro caso: 

vectores de red de una red FCC: 

Consideraremos sobre cada átomo los orbitales que mejor puedan definir el comportamiento de los electrones del cristal. Se corresponderán con los orbitales de valencia, pues son los que contienen los electrones menos ligados al átomo. 

número de átomos base i€{1,...,m} ae{s,p,d,f,...,n} 

número de orbitales 

que podemos denotar como: 

En el caso del silicio: 

3 

En principio si nuestro cristal tiene N átomos de cada tipo, tendríamos una base de funciones de onda de 

> como en general                    tratar el problema con tantas funciones de onda sería imposible incluso con N ~10” ordenador, pues tendríamos que escribir el hamiltoniano en esta enorme base de funciones de onda. La solución a este problema está en aplicar las propiedades de simetría. En concreto, la simetría de traslación 

Aplicando el teorema de Bloch: 

y por tanto puedo reducir mi análisis al estudio de la función de onda en el espacio recíproco restringido a la 1ª zona de Brillouin. Formamos por tanto una base Bloch: 

## número de átomos base 

## número de orbitales 

LCAO: 

En el caso del silicio: 

4 

Esta para el hamiltoniano 8x8 que se llama hibridación sp[3] . Hemos de destacar que esta base la suponemos ortonormal. 

Ecuaciones para los coeficientes          : clk) 

Como aproximación podemos suponer que el solapamiento es pequeño, y por lo tanto: 

: Conocida ya la base calculamos las componentes del Hamiltoniano 

definimos: 

5 

y por tanto me queda: 

Distingamos entre los casos de interacción entre átomos de la misma base y átomos de distinta base. Hemos de tener en cuenta que los primeros vecinos son átomos de distinta base. 

## _a) Átomos de la misma base_ 

6 

## _b) Átomos de distinta base_ 

donde me quedo con la interacción a primeros vecinos. 

En nuestro caso: 

Para continuar, utilizamos las relaciones de Slater y Koster para integrales de dos centros: 

son los cosenos directores de 

eliminaremos ya los índices 1,2 ya sabemos que se trata de interacción átomo 1 - átomo 2. 

7 

8 

9 

10 

donde: 

11 

12 

## En los puntos de simetría: 

14 

15 

16 

## ¿Cómo obtenemos los parámetros del modelo? 

- Según la ley de Harrison: 

> donde     es la distancia con el vecino más cercano,      es la masa del electrón, y         es un factor que d mM, Nim depende de la simetría del cristal (ver apuntes). 

## • Acudiendo a datos empíricos: 

## Fuentes: 

Chadi and Cohen, "Tight-binding calculations of the valence bands of diamond and zincblende crystals," phys. stat. sol. (b) 68, 405 (1975) Chadi and Qian, Phys. Rev. B 35, 1288 (1987). https://gist.github.com/Mahdisadjadi/62c960d3ccad1ee1868e9370e7567229 

17 

## **Resultados** 

Tras resolver la ecuación secular, la estructura de bandas que obtenemos en la hibridación sp3 es del tipo: 

Fuente: https://gist.github.com/Mahdisadjadi/62c960d3ccad1ee1868e9370e7567229 

18 

## **Discusión** 

## _Ver material adicional: Estructura de bandas de cristales tetrahédricos_ 

## Estructura de bandas en hibridación sp3 para distintos cristales tipo diamante: 

En todos hay 8 electrones de enlace por celda primitiva 

**==> picture [83 x 12] intentionally omitted <==**

**----- Start of picture text -----**<br>
Energía en eV.<br>**----- End of picture text -----**<br>


En todos ellos tenemos un gap entre la 4ª y 5ª banda 

19 

## Discusión 

Comparación con modelos más exactos. 

| aserty FEES Tight-binding stents —_— Pseudopotencial INA 1S, AG RORD Pseudopotencial no local incluyendo interacción spínPseudopotencial no local 20 órbita incluyendo interacción spín-órbita 

## Discusión 

## Conclusiones de nuestro resultado tight binding hibridación sp3: 

- Reproduce aceptablemente las bandas de valencia, pero discrepa bastante en las de conducción. 

- Falla al predecir que estos materiales son de gap directo (el mínimo de la banda de conducción está en el mismo punto que el máximo de la banda de valencia). Los materiales de tipo diamante son de gap indirecto. 

## ¿Cómo mejorar la estructura de bandas? 

- Incrementando la base de orbitales. Si incluimos orbitales d por cada átomo en celda primitiva, la base Bloch sería de dimensión 18x18. 

- Incrementando la aproximación a más vecinos. No incrementaríamos el número de bandas, pero se pueden optimizar. 

21 



---

## Imágenes extraídas


```{image} 1_3_prob_Modelo_sp3_images/page1_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page2_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page2_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page2_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page2_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page2_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page3_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page4_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page5_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page6_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img9.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page7_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page8_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page9_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page10_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page11_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page11_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page11_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page11_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img16.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img17.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img18.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img19.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img20.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img21.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img22.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img23.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img24.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img25.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img26.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img27.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img28.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img29.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img30.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img31.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img32.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img33.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page12_img34.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page13_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page13_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page13_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page14_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img7.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img8.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img10.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img11.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img12.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img13.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img14.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page15_img15.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page16_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page17_img1.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page18_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img6.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img7.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img8.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img9.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_prob_Modelo_sp3_images/page19_img10.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```
