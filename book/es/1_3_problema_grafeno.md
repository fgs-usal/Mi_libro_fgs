<!-- Convertido automáticamente desde PDF. Revisar y corregir formato si es necesario. -->

## **Problema de Tight Binding con grafeno** 

1. Calcula y representa la estructura de bandas en aproximación tight binding (o de enlace fuerte) del grafeno. Para ello, considera una base de orbitales formada el orbital de por pz 

cada átomo. 

_Puntos a valorar:_ 

- _Justificación de la base elegida._ 

- _Cálculo del Hamiltoniano._ 

- _Cálculo de los autovalores._ 

- _Representación de las bandas de energía en algún punto o_ 

- _eje de simetría de la 1ª zona de Brillouin._ 

- _Discusión de resultados y comparación con bibliografía._ 

- _Sugerencias e implementación de mejoras en el modelo_ 

- _utilizado._ 

## Grafeno ~~ee~~ 

Red bidimensional de carbono 

C   [He] 2s2 2p2 

Dos tipos de enlaces s p Vamos a escoger solo los orbitales pz 

## Base atómica y red cristalina ~~ee~~ 

Atomos de la base 

g2 g1 a g3 

**==> picture [149 x 399] intentionally omitted <==**

**----- Start of picture text -----**<br>
𝜏0 = 0,0<br>𝜏1 = 𝜏= a, 0<br>Vectores de la red<br>3 3<br>𝑎 = 𝑎<br>1<br>2  [,] 2<br>O24<br>3 3<br>𝑎 = 𝑎<br>2<br>2  [, −] 2<br>Primeros vecinos<br>𝛾1 = 𝑎(1,0)<br>1 3<br>𝛾2 = 𝑎 −<br>2 [,] 2<br>1 3<br>𝛾3 = 𝑎 −<br>2  [, −] 2<br>**----- End of picture text -----**<br>


## Red reciproca ~~ee~~ 

**==> picture [204 x 353] intentionally omitted <==**

**----- Start of picture text -----**<br>
Vectores de la red recíproca<br>2𝜋 1 1<br>𝑏 =<br>1<br>(7) 𝑎 3  [,] 3<br>2𝜋 1 1<br>𝑏 =<br>2<br>𝑎 3  [, −] 3<br>Puntos de alta simetría<br>2𝜋 1<br>𝑀=<br>𝑎 3  [, 0]<br>6)<br>2𝜋 1 1<br>K=<br>-¢5) 𝑎 3 [,] 3 3<br>**----- End of picture text -----**<br>


- Hamiltoniano Tight Binding 

- ~~a~~ 

## Base Bloch de estados 

> Estados { |1, 𝑝𝑧ۧ, |2, 𝑝𝑧ۧ 

Ecuación secular 

En todos los casos 𝑙 = 0 𝑧 1,2 1,2 1,2 1,2 1,2 𝐸 𝑅= 𝐸 𝑉 + 1 −𝑙 𝑉 = 𝑉 = 𝑉 𝑝𝑧𝑝𝑧 (~) 𝑝𝑧𝑝𝑧 () Ԧ𝛾= 𝑙𝑧[2] 𝑝𝑝𝜎 () 𝑧[2] 𝑝𝑝𝜋 𝑝𝑝𝜋 𝑝𝑝𝜋 

- Hamiltoniano Tight Binding 

- ~~a~~ 

11 𝐻 = 𝐸 + 𝑆𝑒𝑔𝑢𝑛𝑑𝑜𝑠𝑣𝑒𝑐𝑖𝑛𝑜𝑠 𝑝𝑧𝑝𝑧 𝑝𝑧 𝐻12 = 𝑉 𝑒[𝑖] 𝑘𝛾𝑖 + 𝑇𝑒𝑟𝑐𝑒𝑟𝑜𝑠𝑣𝑒𝑐𝑖𝑛𝑜𝑠 𝑝𝑧𝑝𝑧 𝑝𝑝𝜋 ෍ 𝛾𝑖 ~~−~~ 𝑎𝑘𝑥 1 ~~−~~ 𝑎𝑘𝑥 1 3𝑎𝑘 ⅈ 3𝑎𝑘 12 2 ~~[−]~~ 2 𝑦 2[+] 2 𝑦 = 𝐻 = 𝑉 ( ⅇ[ⅈ𝑎𝑘][𝑥] + ⅇ[ⅈ] ~~(=v~~ ) + ⅇ ~~(=~~ v) 𝑉 g( 𝑘 > ) 𝑝𝑧𝑝𝑧 𝑝𝑝𝜋 𝑝𝑝𝜋 No existe solapamiento 𝐸 𝑉 g( 𝑘 ) 𝐻= 𝑝𝑧 𝑝𝑝𝜋 𝑉𝑝𝑝𝜋 𝑔[∗] ( 𝑘 ) 𝐸𝑝𝑧 𝑆𝑖𝑗 = 𝛿𝑖𝑗 

- Hamiltoniano Tight Binding 

- ~~ee~~ 

**==> picture [252 x 26] intentionally omitted <==**

Por simplicidad puedo tomar 𝐸 = 0 𝑝𝑧 

𝐸(𝑘 ) = ±𝑉𝑝𝑝𝜋 | g( 𝑘 ) | 

**==> picture [629 x 153] intentionally omitted <==**

- Representación de las bandas 

- ~~ee~~ 

**==> picture [389 x 16] intentionally omitted <==**

**----- Start of picture text -----**<br>
K G M<br>**----- End of picture text -----**<br>


Representación de las bandas 

## Mejoras al modelo 

- Incluir los orbitales p y s ignorados. Eso da s. 

- lugar a considerar los  enlaces 

- Incluir más vecinos. En ese caso los segundos vecinos son de la misma red. 

- Calcular el solapamiento. 

## Comparación con otros resultados 

Fuente: Alguna página wiki al azar 

## Comparación con otros resultados 

F. Bassani et al., Il Nuovo Cimento B (1965-1970) 50, 95–128 (1967). 

## Comparación con otros resultados 

## **ARPES (Angle-resolved photoemission spectroscopy)** 

M. Sprinkle et al., Phys. Rev. Lett. 103, 226803 (2009). 

D. A. Siegel et al. PNAS 108 , 11365-113 (2011). 



---

## Imágenes extraídas


```{image} 1_3_problema_grafeno_images/page2_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page2_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page2_img3.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page2_img4.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page3_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page3_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page4_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page4_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page5_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page5_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page5_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page5_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page5_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page6_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page6_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page6_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page7_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page7_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page7_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page8_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page8_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page9_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page9_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page9_img3.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page10_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page10_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page11_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page11_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page11_img3.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page12_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page12_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page12_img3.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page12_img4.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page13_img1.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page13_img2.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page13_img3.jpeg
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page13_img4.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```


```{image} 1_3_problema_grafeno_images/page13_img5.png
:alt: Imagen extraída del PDF
:width: 80%
:align: center
```
