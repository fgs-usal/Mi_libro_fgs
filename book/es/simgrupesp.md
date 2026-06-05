---
title: "**REPRESENTACIONES DEL GRUPO ESPACIAL**"
---

# INTRODUCCIÓN

Recordemos que el grupo de simetrías de un cristal es el grupo espacial
$\mathbf{G}=\mathbf{T}\otimes\mathbf{G_{0}}$ siendo $\mathbf{G_{0}}$ el
grupo puntual del cristal y $\mathbf{T}$ el grupo de traslaciones. Hemos
visto que si tenemos un cristal con N celdas primitivas e introduciendo
las condiciones de periodicidad de Born-Von Kàrman, que las funciones de
Bloch pertenecen a las representaciones irreducibles de
$\mathbf{T^{*}}$, grupo cíclico de traslaciones con N elementos; que la
energía de los estados monoelectronicos se clasifican de acuerdo con las
representaciones irreducibles de ese grupo de traslaciones, que se
identifican por los N puntos internos de la primera zona brillouinera y
por tanto, los estados propios del hamiltoniano pertenecen a dichas
representaciones irreducibles. Resumamos las conclusiones que se extraen
de las propiedades de las representaciones irreducibles de dicho grupo:

-   Los autovalores se clasifican de acuerdo con las representaciones
    irreducibles de $\mathbf{T^{*}}$

-   Como $\mathbf{T^{*}}$ es cíclico, es abeliano y por tanto hay N
    representaciones irreducibles unidimensionales, luego los
    autovalores son no degenerados

-   Cada representación y, por ende, cada función está caracterizada por
    un vector de espacio recíproco, luego estados de diferente $\vec{k}$
    son ortogonales y asociados a energías distintas

-   Dentro de cada representación $\vec{k}$ hay estados correspondientes
    a energías distintas, por ello caracterizamos los autovalores y los
    estados por un índice n y la etiqueta de la representación
    irreducible: el vector $\vec{k}$

-   Basta con considerar N vectores de primera zona Brillouinera, pues
    $\vec{k}$ y $\vec{k}+\vec{G}$, siendo $\vec{G}$ vector de red
    recíproca dan lugar a la misma representación, luego
    $E_{n}(\vec{k})=E_{n}(\vec{k}+\vec{G})$ y los estados propios
    $|\psi_{n\vec{k}}>$ y $|\psi_{n\vec{k}+\vec{G}}>$ son iguales. Ello
    no empece que haya funciones $\{\psi_{\vec{k}+\vec{G}}(\vec{r})\}$,
    que deben pertenecer necesariamente a la representación $\vec{k}$,
    que sean distintas; lo que estamos diciendo es que un estado propio
    $|\psi_{n\vec{k}}>$ debe ser combinación lineal de estados
    $|\psi_{\vec{k}+\vec{G}}>$

-   Podemos construir una base irreducible de estados propios que
    pertenezcan a las representaciones irreducibles de $\mathbf{T^{*}}$
    . En principio esa base es completa y será el punto de partida para
    construir bases de representaciones irrreducibles del grupo espacial
    $\mathbf{G}$ y, por tanto poder deducir propiedades de los
    autoestados y de los autovalores de energía monoelectrónicos,
    teniendo en cuenta toda la simetría del cristal.

Como las representaciones irreducibles de $\mathbf{T^{*}}$ no tienen por
qué ser irreducibles por $\mathbf{G}$, deberemos modificar alguna de las
conclusiones que hemos deducido de las propiedades traslacionales.

# OPERADORES DEL GRUPO ESPACIAL Y FUNCIONES DE BLOCH

La primera cosa que debemos hacer para pasar del grupo de traslaciones
hacia el grupo espacial es encontrar cómo operan los elementos del grupo
espacial sobre las funciones de Bloch. Como el grupo puntual
$\mathbf{G_{0}}$ es grupo de simetría del cristal, debe cumplirse que si
$M=\{M|T_{0}\}\in \mathbf{G_{0}}$

$$\psi_{\vec{k}}(\vec{r})=0$$

(Por cuestiones de comodidad, prescindimos del índice de banda), por
tanto $M\psi_{\vec{k}}$ es un estado que pertenece a la representación
irreducible asociada a $E_{k}$, debe de ser un estado Bloch y nos
preguntamos cuál es.

En notación de Seitz un elemento del grupo espacial
$\mathbf{G}=\mathbf{T}\otimes\mathbf{G_{0}}$ se representa por
$\{M|T_{R}\}$, $M\in \mathbf{G_{0}}$ y $T_{R}\in \mathbf{T}$ y opera de
la siguiente guisa sobre las coordenadas:

$$\{M|T_{R}\}\vec{r}=M\vec{r}+\vec{R}$$

de lo cual podemos se deduce que:

$$\begin{aligned}
 \{M|T_{R}\}\{M'|T_{R'}\}&=&\{MM'|T_{MR'+R}\} \\
 \{M|T_{R}\}^{-1}&=&\{M^{-1}|T_{-M^{-1}R}\} \\
 \{E|T_{R'}\}\{M|T_{R}\}&=&\{M|T_{R}\}\{E|T_{M^{-1}R'}\}
 \label{ecge1}
\end{aligned}$$

Siendo $E$ el operador identidad de $\mathbf{G_{0}}$

luego también no es menos cierto que si $f(\vec{r})$ es una función:

$$\{M|T_{R}\}f(\vec{r})=f(\{M|T_{R}\}^{-1}\vec{r})
  =f(M^{-1}\vec{r}-M^{-1}\vec{R})$$

Basándonos en estos resultados nos proponemos encontrar a quién es igual
$\{M|T_{R}\}\psi_{k}$, siendo $\psi_{k}$ una función Bloch que, por
tanto podemos expresar como
$\psi_{k}(\vec{r})=\exp[i\vec{k}.\vec{r}]u_{\vec{k}}(\vec{r})$. Se puede
hacer una deducción rigurosa teniendo en cuenta
([\[ecge1\]](#ecge1){reference-type="ref" reference="ecge1"}) pues:

$$\begin{aligned}
 \{E|T_{R'}\}\{M|T_{R}\}\psi_{k}&=&
 \{M|T_{R}\}\{E|T_{M^{-1}\vec{R}'}\}\psi_{k} \mbox{ ; }
 \Rightarrow \nonumber \\
 \{E|T_{R'}\}\{M|T_{R}\}\psi_{k}(\vec{r})&=&
 \{M|T_{R}\}\exp[-i\vec{k}.M^{-1}\vec{R'}]
 \exp[-i\vec{k}.\vec{r}]
 .u_{\vec{k}}(\vec{r}-M^{-1}\vec{R'}) \nonumber \\
 &=&\{M|T_{R}\}\exp[-i\vec{k}.M^{-1}\vec{R'}]\psi_{k}(\vec{r})
\end{aligned}$$

y como el producto escalar se mantiene por las operaciones del grupo
puntual:

$$\vec{k}.M^{-1}\vec{R'}=M\vec{k}.MM^{-1}\vec{R'}=
 M\vec{k}.\vec{R'}$$

luego:

$$\begin{aligned}
 \{E|T_{R'}\}\{M|T_{R}\}\psi_{k}
  &=&\exp[-iM\vec{k}.\vec{R'}]\{M|T_{R}\}\psi_{\vec{k}}
  \mbox{ ; } \Rightarrow \nonumber \\
  &=&\chi_{M\vec{k}}(R')\{M|T_{R}\}\psi_{\vec{k}}
\end{aligned}$$

luego es $M\psi_{\vec{k}}$ una función Bloch perteneciente a la
representación $M\vec{k}$,

(Creo que hay una demostración menos liosa, aunque puede presentar
algunas complicaçoes al final. En principio nos preguntamos cómo se
transforma $\{M|T_{R}\}\psi_{\vec{k}}(\vec{r})$:

$$\begin{aligned}
 \{M|T_{R}\}\psi_{\vec{k}}(\vec{r})&=&
 \psi_{k}(M^{-1}\vec{r}-M^{-1}\vec{R}) \nonumber \\
 &=&\exp[-i\vec{k}.M^{-1}\vec{R}]\exp[i\vec{k}.M^{-1}\vec{r}]
  .u_{\vec{k}}(M^{-1}\vec{r}-M^{-1}\vec{R}) \nonumber \\
  &=&\exp[-iM\vec{k}.\vec{R}]\exp[iM\vec{k}.\vec{r}]
  .u_{\vec{k}}(M^{-1}\vec{r})
\end{aligned}$$

Pues $M^{-1}\vec{R}=\vec{R}'$. Teniendo en cuenta que
$u_{\vec{k}}(\vec{r})$ es periódica y por tanto

$$u_{\vec{k}}(\vec{r})=\sum_{\vec{G}}c_{\vec{G}}(\vec{k})
  \exp[i\vec{G}\vec{r}]$$

y que $MG=G'$ creo que podemos llegar a la conclusión que
$T_{\vec{R}}M\psi_{\vec{k}}=\{M|T_{R}\}\psi_{k}$ pertenece a la
representación $M\vec{k}$)

Luego si particularizamos a $T_{\vec{R}}=T_{0}$ deducimos que:

$$|M\psi_{\vec{k}}>=|\psi_{M\vec{k}}>$$

y por tanto, todos los estados $|\psi_{nM_{i}\vec{k}}>$ tienen los
mismos autovalores $E_{n}(\vec{k}_{i})$ (He recuperado de nuevo el
índice de la bandita para que quede bonito)

Un caso particular importante surge para la inversión $i=\{i|T_{0}\}$.
La inversión cambia el signo de las coordenadas, tanto en el espacio
directo como en el espacio recíproco, por tanto $i\vec{k}=-\vec{k}$
Entonces:

$$\{i|T_{0}\}\psi_{\vec{k}}=\psi_{i\vec{k}}=\psi_{-\vec{k}}$$

# BASES DEL GRUPO ESPACIAL

Conectemos con el final de la sección anterior. Todos los estados
$|\psi_{nM_{i}\vec{k}}>$ tienen los mismos autovalores $E_{n}(\vec{k})$,
luego pertenecen a la misma representación irreducible del grupo
espacial. Recapitulemos teniendo en cuenta las conclusiones obtenidas de
la simetría traslacional: Dado un cristal con N celdas primitivas, hay N
representaciones irreducibles unidimensionales caracterizadas por
$\vec{k}$. A partir de las mismas construyo una base de estados Bloch
$\psi_{n\vec{k}}$. Esta base es un buen punto de partida para obtener
una base de estados propios de grupo espacial. Al considerar el grupo
espacial y tener en cuenta el efecto del grupo puntual observo que la
base Bloch se divide en bases disjuntas (Ver demostración en Altmann)
$\{\psi_{nM\vec{k}}\}$ asociadas al mismo autovalor $E_{n}(\vec{k})$,
luego los subconjuntos $\{\psi_{nM\vec{k}}\}$ se transforman entre sí
por las operaciones del grupo espacial y son un buen punto de partida
para obtener las funciones de las representaciones irreducibles de
$\mathbf{G}$. Sin embargo, no significa que este conjunto constituya una
base irreducible y veremos, al contrario, que en ciertos casos contiene
redundancias o bien que no están correctamente simetrizadas respecto de
las representaciones del grupo espacial. Dado $\vec{k}$ nos interesa
saber cuántos elementos hay en el (ya muchas veces citado) subconjunto
$\{\psi_{nM\vec{k}}\}$ y deducir si son también funciones de las
representaciones irreducibles de $\mathbf{G}$ o en caso negativo, cómo
generarlas y, por tanto deducir propiedades de las autofunciones y de
los autovalores.

# ESTRELLA DE $\vec{k}$, GRUPO PUNTUAL Y REPRESENTACIÓN PEQUEÑA

Bueno, pues a lo nuestro y a lo de siempre: Consideremos un cristal con
N celdas primitivas y grupo puntual $\mathbf{G_{0}}$. Basándonos en las
condiciones de Born-Von Kàrman [^1] construimos en la primera zona de
Brillouin N vectores $\vec{k}$. Vamos a introducir unos conceptos
relacionados con la aplicación de las transformaciones del grupo puntual
$\mathbf{G_{0}}$ a dichos vectores :

-   [Estrella $S_{\vec{k}}$]{.underline} de un punto $\vec{k}$. Dado un
    punto $\vec{k}$ de primera zona de Brillouin y el grupo puntual
    $\mathbf{G_{0}}$ del cristal, la estrella
    $S_{\vec{k}}=\{\vec{k}=\vec{k}_{1},\vec{k}_{2},..,\vec{k}_{n}\}$ de
    $\vec{k}$ el conjunto de puntos de primera zona de Brillouin
    obtenidos de la siguiente guisa:

    $$\begin{aligned}
     M_{i}\vec{k}&=&\vec{k}_{i} \hspace{1cm} \forall M_{i}\in 
     \mathbf{G_{0}} \\
     M_{i}\vec{k}& \neq &\vec{k} + \vec{G} 
    \end{aligned}$$

    Es decir, el conjunto de puntos de primera zona de Brillouin
    obtenidos al aplicar las transformaciones del grupo puntual que no
    sean equivalentes por vectores de red recíproca $\vec{G}$

-   [Grupo $G_{\vec{k}}$]{.underline} del punto $\vec{k}$. Dado un punto
    $\vec{k}$ de primera zona brillouinera, el grupo
    $G_{\vec{k}}=\{M_{i}\}$ es el conjunto de transformaciones de
    $\mathbf{G_{0}}$ que cumple:

    $$M_{i}\vec{k} = \vec{k} + \vec{G}$$

    es decir el conjunto de transformaciones de $\mathbf{G_{0}}$ que
    mantienen el punto invariante o lo transforma en otro que difiere en
    un vector de red recíproca $\vec{G}$. Tiene estructura de grupo.

-   [Representaciones irreducibles pequeñas del grupo de
    $\vec{k}$]{.underline}. Son las representaciones irreducibles del
    grupo $G_{\vec{k}}$ Designemos sus caracteres por
    $\chi^{\nu}_{\vec{k}}(M_{i})$

Obsérvese que si $g_{0}$ es la dimensión del grupo puntual $G_{0}$ y $g$
la del grupo $G_{\vec{k}}$, se cumple $g_{0}=g.\mathtt{dim}S_{\vec{k}}$.
Se denomina punto general al punto $\vec{k}$ cuyo grupo puntuales sólo
$\{E\}$, es decir, la estrella $S_{\vec{k}}$ tiene dimensión $g_{0}$.
$\vec{k}$ será punto de simetría si el grupo $G_{\vec{k}}$ es mayor que
$\{E\}$. Eje de simetría es la recta de puntos $\vec{k}$ que tienen el
mismo grupo puntual $G_{\vec{k}}$ y, logicamenete, definimos de forma
análoga plano de simetría.

A continuación presentamos unos ejemplitos ilustrativos del asunto

## Funciones y representaciones irreducibles de $G_{\vec{k}}$. La base de $\mathbf{G}$

Resumamos lo que tenemos hasta ahora: Partimos de estados Bloch, que
tienen la simetría traslacional, en principio distintos, base de las
representaciones irreducibles del grupo de traslacional y por tanto,
ortogonales entre sí y asociados a autovalores de energía distintos
entre sí. Al tener en cuenta el grupo puntual deducimos que, dado un
victor $\vec{k}$, los estados $|\psi_{M\vec{k}}>$ tienen la misma
energía (prescindo del índice de banda para no liar más las cosas), que
parece que hay estados redundantes, pues si tengo en cuenta el grupo
puntual $G_{\vec{k}}=\{M_{i}\}$ de $\vec{k}$, $|\psi_{k}>$ y
$|\psi_{Mi\vec{k}}>$ deben ser el mismo estado, pues
$M_{i}\vec{k}=\vec{k}+\vec{G}$, pero en principio, por construcción, son
distintos estados Bloch. ¿Prescindo de estos estados?. Por otra parte,
si tenemos en cuenta la estrella $S\vec{_{k}}=\{\vec{k}_{i}\}$, parece
que sólo debo considerar como distintos los estados $|\psi_{\vec{k}i}>$
\.... pero ¿Tienen dichos estados la simetría del grupo espacial?. En
principio no, son funciones Bloch y, por tanto sólo tienen la simetría
del grupo de traslaciones.

Este pequeño lío se resuelve con las representaciones irreducibles
pequeñas de $G_{\vec{k}}$. En efecto, procedamos de la siguiente guisa:
Dado un estado Bloch $|\psi_{k}>$ y el grupo $G_{\vec{k}}=\{M_{i}\}$,
construyamos funciones de las representaciones irreducibles pequeñas de
$G_{k}$ aplicando el teorema de la proyección:

$$\psi^{\nu}_{\vec{k}}(\vec{r}) = \frac{l_{\nu}}{g_{0}}\sum_{i}\chi^{\nu}_{\vec{k}}(M_{i})^{*} M_{i}\psi_{\vec{k}}(\vec{r}) \label{elas4}$$

$$= \frac{l_{\nu}}{g_{0}}\sum_{i}\chi^{\nu}_{\vec{k}}(M_{i})^{*} \psi_{Mi\vec{k}}(\vec{r}) \label{elas2}$$

$$= \frac{l_{\nu}}{g_{0}}\sum_{i}\chi^{\nu}_{\vec{k}}(M_{i})^{*} \psi_{\vec{k}}(M_{i}^{-1}\vec{r}) \label{elas3}$$


Estas funciones tienen la simetría traslacional, pues son funciones
Bloch de la representación irreducible $\vec{k}$, y tienen la simetría
del grupo puntual por construcción, luego pertenecen a las
representaciones irreducibles del grupo espacial. Este proceso hay que
realizarlo con todos los puntos de la estrella $S_{k}$. Obsérvese en
([\[elas2\]](#elas2){reference-type="ref" reference="elas2"}) que dicha
función simetrizada puede ser combinación de funciones Bloch de vectores
equivalentes por vector de red recíproca, pues al ser $M_{i}\in G_{k}$,
$M_{i}\vec{k}=\vec{k}+\vec{G}$; luego en estas funciones simetrizadas se
cumple que $|\psi_{\vec{k}}^{\nu}> = |\psi_{\vec{k}+\vec{G}}^{\nu}>$,
entendiéndolo en el sentido de estados de la Mecánica cuántica, c'est à
dire: las funciones $\psi_{\vec{k}}^{\nu}(\vec{r})$ y
$\psi_{\vec{k}+\vec{G}}^{\nu}(\vec{r})$ pueden diferir en una fase
(Recordemos las desaforadamente juiciosas palabras de L.J.B: (Luis
Joaquín Boya Valet, portentoso Catedrático de Física Teórica de la
Universidad CesarAugustana de descomunal valía y maestro mío): Un estado
de un sistema es un elemento del espacio proyectivo (un rayo) de
Hilbert). Por ello, al aplicar la simetrización unas veces interesará
utilizar ([\[elas2\]](#elas2){reference-type="ref" reference="elas2"}) y
otras ([\[elas3\]](#elas3){reference-type="ref" reference="elas3"}),
como veremos en algún ejemplito

Luego deducimos que la estrella $S_{\vec{k}}$ y el grupo $G_{\vec{k}}$
permiten obtener una base irreducible de estados que está simetrizada
respecto de las representaciones irreducibles del citado grupo.
Aclaremos alguna cosa más

-   Consideremos un punto general: su estrella
    $S_{\vec{k}}=\{\vec{k}_{i}\}$, $i=1,g_{0}$, contiene $g_{0}$
    elementos y como $G_{\vec{k}}=\{E\}$ es solamente la identidad, hay
    una sola representación irreducible y por tanto
    $\chi({E})\psi_{\vec{k}i}=\psi_{\vec{k}i}$, luego (para cada banda,
    recuérdese que por comodidad hemos prescindido del índice de banda)
    las funciones Bloch provenientes de la simetría traslacional son
    también funciones de las representaciones del grupo espacial y se
    ratifica que son estados no degenerados.Por supuesto se cumple que
    todos los puntos de la estrella tienen la misma estructura de
    bandas, pero los estados son diferentes, aunque puedo obtenerlos a
    partir de los de uno de los elementos de la estrella; en efeto:

    $$\begin{aligned}
     E_{n}(M\vec{k})&=&E_{n}(\vec{k}) \hspace{1cm} \forall M \in G_{0} \\
     \psi_{M\vec{k}}(\vec{r})&=&M\psi_{\vec{k}}(\vec{r}) 
      = \psi_{\vec{k}}(M^{-1}\vec{r})
    \end{aligned}$$

-   En el caso de un punto de simetría $G_{k}=\{M_{i}\} \neq \{E\}$,
    luego por lo menos tiene dos elementos y tiene más de una
    representación irreducible; luego las energías
    $E_{n}^{\nu}(\vec{k})$ se etiquetan (se caracterizan) con un índice
    n (índice de banda), el vector $\vec{k}$, todo ello proveniente de
    la simetría traslacional y, además con la etiqueta $\nu$ de la
    correspondiente representación irreducible. Los estados tienen las
    propiedades Bloch asociadas a $\vec{k}$, pero además, las
    propiedades de las funciones asociadas a la representación
    irreducible $\nu$ de $G_{\vec{k}}$. Es decir, los estados
    electrónicos se caracterizan por el índice de banda n, el vector
    $\vec{k}$ y deben pertenecer a alguna de las representaciones
    irreducibles de $G_{\vec{k}}$. Como ya se ha dicho, dichas funciones
    se pueden obtener a partir de las funciones Bloch traslacionales
    aplicando el teorema de la proyección, ecs
    ([\[elas4\]](#elas4){reference-type="ref"
    reference="elas4"}-[\[elas3\]](#elas3){reference-type="ref"
    reference="elas3"}). Y podemos sacar una consecuencia enriquecedora
    más: Si la representación $\nu$ es n dimensional; id est (que dirían
    los latinos) $\chi^{\nu}(E)=n$, la energía $E_{n}^{\nu}(\vec{k})$
    estará n veces degenerada.

Para aclarar mejor estas (humildes) ideas vamos a aplicarlas al caso de
una red bidimensional cuadrada, cuya primera zona brillouinense es la de
la figura [\[fig1\]](#fig1){reference-type="ref" reference="fig1"}

-   Punto general $\vec{k}$. La estrella $S_{\vec{k}}=\{\vec{k}_{i}\}$,
    $i=1,8$ contiene 8 elementos, luego las ocho funciones Bloch
    $\psi_{n\vec{k}i}(\vec{r})$ tienen la simetría del grupo espacial,
    son linealmente independientes, y los autovalores de energía
    $E_{n}(k_{i})$ son no degenerados.

-   Punto Z. En principio tenemos 8 puntos $\vec{Z}_{i}$, ver figura
    [\[fig2\]](#fig2){reference-type="ref" reference="fig2"} y por tanto
    ocho funciones Bloch para cada n, pero como
    $\vec{Z}_{5}=\vec{Z}_{2}+\vec{G}$,
    $\vec{Z}_{6}=\vec{Z}_{1}+\vec{G}$, \..., la estrella tiene sólo
    cuatro puntos; parece que de las ocho funciones cuatro son
    redundantes ¿Es así?, ¿Que cuatro estados elegimos?. Veamos; tomemos
    el punto $\vec{Z}_{1}$, cuyo grupo es
    $G_{\vec{Z}1}=\{E,\sigma_{x}\}$ y la tabla de caracteres con alguna
    función de la representación es:

    ::: {#tabelas1}
      $Z$         $E$   $\sigma^{x}$ 
      --------- ----- -------------- ---------
      $A_{1}$       1              1   $p_{y}$
      $A_{2}$       1             -1   $p_{x}$

      : Taula de caracteres del grupo puntual de $Z$
    :::

    []{#tabelas1 label="tabelas1"}

    luego los estados debidamente simetrizados o bien pertenecen a la
    representación $A_{1}$ o a la $A_{2}$. Apliquemos el th de la
    proyección ([\[elas4\]](#elas4){reference-type="ref"
    reference="elas4"}):

    $$\begin{aligned}
    \psi_{Z1}^{A1}(\vec{r})&=&\frac{1}{2}[\chi^{A1*}(E)
      E\psi_{Z1}(\vec{r}) + \chi^{A1*}(\sigma_{x})
      \sigma_{x}\psi_{Z1}(\vec{r})] \nonumber \\
      &=&\frac{1}{2}[\psi_{Z1}(\vec{r}) + \psi_{\sigma_{x}Z1}(\vec{r})]
      \nonumber \\
      &=&\frac{1}{2}[\psi_{Z1}(\vec{r}) + \psi_{Z6}(\vec{r})] \\
    \psi_{Z1}^{A2}(\vec{r})&=&\frac{1}{2}[\chi^{A2*}(E)
      E\psi_{Z1}(\vec{r}) + \chi^{A2*}(\sigma_{x})
      \sigma_{x}\psi_{Z1}(\vec{r})] \nonumber \\
      &=&\frac{1}{2}[\psi_{Z1}(\vec{r}) - \psi_{Z6}(\vec{r})]
    \end{aligned}$$

    Luego las funciones de Bloch $\psi_{Z1}(\vec{r})$ y $\psi_{Z6}(r)$
    son necesarias para obtener la adecuada simetrización. Y el mismo
    proceso seguiremos para los demás puntos de la estrella; dedúcese de
    eio que obtenemos 8 estados debidamente simetrizados:
    $\{\psi_{Zi}^{A1}(\vec{r}),\psi_{Zi}^{A2}(\vec{r})\}$, $i=1,4$.
    Luego en este caso los estados o bien pertenecen a $A_{1}$ o a
    $A_{2}$. Se deja para el (ingenioso y avispado) lector demostrar que
    $|\psi^{Aj}_{\vec{Z}i}> = |\psi^{Aj}_{\vec{Z}i+\vec{G}}>$, que son
    funciones Bloch de vector $\vec{k}=\vec{Z}_{i}$ y que
    $\psi_{Zi}^{A1}(\vec{r})$ y $\psi_{Zi}^{A2}(\vec{r})$, difieren en
    la parte periódica de la función de Bloch, $u^{A1}_{\vec{Z}i}$ y
    $u^{A2}_{\vec{Z}i}$. Entonces, dichos estados son diferentes, están
    asociados a valores propios distintos (ojo, pueden coincidir por lo
    que se llama degeneración accidental) ¿En qué difieren?. En las
    propiedades de las funciones de la representación. Volvamos a la
    tabla de caracteres: En efeto: las funciones de la representación
    $A_{1}$ son invariantes bajo reflexión $\sigma_{x}$, es decir son
    pares en $x$, en cambio las funciones de la representación $A_{2}$
    cambian de signo por reflexión $\sigma_{x}$; son impares en $x$; por
    eso en el caso de que haya estados de que se comporten como estados
    $p$, el estado $p_{y}$ pertenece a la representación irreducible
    $A_{1}$ y el estado $p_{x}$ a la $A_{2}$

    Como las representaciones irreducibles de Z son unidimensionales,
    los estados son, salvo degeneración accidental, no degenerados.

-   Sease un punto $\Delta$. (Ver figura
    [\[fig2\]](#fig2){reference-type="ref" reference="fig2"})
    $S_{\Delta}=\{\Delta_{i}\}$, $i=1,4$,
    $G_{\Delta1}=\{E,\sigma_{x}\}$, luego la taula de caracteres es la
    misma que para $Z_{1}$ (ver tabla
    [1](#tabelas1){reference-type="ref" reference="tabelas1"}).
    Apliquemos todo lo anterior

    $$\begin{aligned}
    \psi_{\Delta1}^{A1}(\vec{r})&=&
      \frac{1}{2}[\psi_{\Delta1}(\vec{r}) + 
      \sigma_{x}\psi_{\Delta1}(\vec{r})]
      \nonumber \\
      &=&\frac{1}{2}[\psi_{\Delta1}(\vec{r}) + 
      \psi_{\Delta1}(\sigma_{x} \vec{r})] \\
    \psi_{\Delta1}^{A2}(\vec{r})&=&\frac{1}{2}[\psi_{\Delta1}(\vec{r}) 
      -\psi_{\Delta1}(\sigma_{x}\vec{r})]
    \end{aligned}$$

    Recordemos: los estados (quánticos) son iguales, las funciones de
    onda pueden diferir en una fase

    [Nota:]{.underline} En el caso del punto $\Delta$, las
    representaciones se denominan $\Delta_{1}$ y $\Delta_{2}$, en lugar
    de $A_{1}$ y $A_{2}$, pero este (humilde) escribidor no ha querido
    liar más las cosas.

-   Punto $\Gamma$ o $M$, el grupo puntual es $\mathbf{C_{4v}}$, con
    cinco representaciones irreducibles, según se puede observar en la
    taula de caracteres adjunta (Ver taula
    [2](#tabelas2){reference-type="ref" reference="tabelas2"})

    ::: {#tabelas2}
      $C_{4v}$     $E$   $C_{2}$   $\{C_{4}^{1},C_{4}^{3}\}$   $\{\sigma^{x},\sigma^{y}\}$   $\{\sigma^{d1},\sigma^{d2}\}$ 
      ---------- ----- --------- --------------------------- ----------------------------- ------------------------------- -----------------------
      $A_{1}$        1         1                           1                             1                               1 $r$,z, $3z^{2}-r^{2}$
      $A_{2}$        1         1                           1                            -1                              -1 
      $B_{1}$        1         1                          -1                             1                              -1 
      $B_{2}$        1         1                          -1                            -1                               1 
      $E$            2        -2                           0                             0                               0 $x$,$y$,$xz$,$yz$

      : Tabla de caracteres de $\mathbf{C_{4v}}$ con algunas funciones
      de alguna de las representaciones
    :::

    Luego los estados y las energías que correspondan a las
    representaciones irreducibles de dimensión 1 serán no degenerados;
    pero hay una representación irreducible de dimensión 2, E (¡no
    confundir con la operación identidad!) (llamada $\Gamma_{5}$ para el
    punto $\Gamma$ o $M_{5}$ para el punto $M$), luego las energías y
    los estados correspondientes a esta representación están doblemente
    degenerados. Por exiemplo, es muy fácil comprobar mediante el
    teorema de la proyección que las funciones $x$ e $y$ (y por tanto
    orbitales $p_{x}$ y $p_{y}$) pertenecen a dicha representación;
    luego, si al calcular la estructura de bandas se hubiera partido de
    orbitales $s$ y $p_{i}$, $i=x,y,z$ podríamos predicar (otra cosa es
    dar trigo) que los estados correspondientes a la representación E
    son doblemente degenerados y deben tener las propiedades de
    orbitales $p_{x}$ o $p_{y}$ (o combinación lineal). En este mismo
    caso podemos afirmar que los estados de la representación totalmente
    simétrica $A_{1}$ ($\Gamma_{1}$ o $M_{1}$) son no degenerados y
    serán o de tipo $s$, o de tipo $p_{z}$ o combinación lineal. Ojo:
    este es un ejemplito particular, si incluimos estados $d$,
    $d_{3z^{2}-r^{2}}$ pertenece a $A_{1}$ y $d_{xz}$ y $d_{yz}$
    pertenecen a la representación doble, el abanico de posibilidades se
    abre.

Aparte de todo lo anterior podemos sacar otra concluçao: En general
habrá una sucesión de bandas en orden ascendiente de energía para cada
$\vec{k}$ de la primera zona brillouinera. A medida que $\vec{k}$ varía,
así lo hace su grupo puntual $G_{\vec{k}}$; si para un $\vec{k}$ (por
exiemplo un punto general) las representraciones irreducibles son
unidimensionales, las bandas serán non degeneratas, pero si pasamos a
otro $\vec{k}$ cuyo grupo puntual tenga representaciones irreducibles
multidimensionales (id est, hay autovalores degenerados), necesariamente
varias bandas en número igual a la dimensión de la representación
multidimensional deben coincidir en un valor al alcanzar este último
punto de más simetría

# REPRESENTACIONES IRREDUCIBLES DEL GRUPO ESPACIAL Y LA ENERGÍA

Unamos principio con final: Supongamos que tenemos un cristal de volumen
$V=N\Omega$ y un grupo espacial $G=T\otimes G_{0}$. El hamiltoniano
monoelectrónico debe cumplir que

$$=0$$

luego los autovalores y los estados propios del hamiltoniano están
caracterizados y tienen las propiedades de las funciones de las
representaciones irreducibles del grupo espacial (Dicho en plan más
pedante: Los subespacios invariantes asociados a los autovalores del
hamiltoniano coinciden con los subespacios generados por las
representaciones irreducibles del grupo espacial). Consecuencias:

-   Las energías se caracterizan por un índice de banda $n$, el vector
    de red recíproca k (consecuencia de la simetría traslacional) y un
    índice $\nu$ correspondiente a las representaciones irreducibles de
    $G_{\vec{k}}$.

-   $E_{n}^{\nu}(\vec{k})= E_{n}^{\nu}(\vec{k}+\vec{G})$. Consecuencia
    de la simetría traslacional. Luego basta calcular la estructura de
    bandas en la primera zona de Brillouin

-   Hay N vectores $\vec{k}$ permitidos en primera zona brillouinera,
    consecuencia de las condiciones de Born-Von Kàrman (que eran dos
    científicos \... bla, bla, bla \... puente de Tacoma \...)

-   Los estados propios son estados Bloch (simetría traslacional)
    pertenecientes a las representaciones irreducibles de $G_{\vec{k}}$
    (simetría del grupo puntual), cumpliéndose que los ESTADOS que
    difieran en un vector de red recíproca son iguales
    $|\psi_{n\vec{k}}^{\nu}>= |\psi_{n\vec{k}+\vec{G}}^{\nu}>$. Dichos
    estados se pueden obtener a partir de estados Bloch, en principio
    diferentes, aplicando el teorema de la proyección para las
    representaciones irreductibles (como los habitantes de una aldea de
    la Galia) de $G_{\vec{k}}$ para cada $\vec{k}$

-   Pero además se cumple que
    $E_{n}^{\nu}(\vec{k})=E_{n}^{\nu}(\vec{Mk})$ pa to M de $G_{0}$. Por
    tanto basta con calcular la estructura de bandas en $1/g_{0}$ de
    primera zona de Brillouin, conocida como zona irreducible de
    Brillouin. Dicha zona está delimitada por los planos de simetría en
    la primera zona del Brillouin debidos al grupo puntual de $G_{0}$. A
    este respecto debemos recordar que $G_{0}$ es el grupo puntual del
    cristal, que NO NECESARIAMENTE coincide con el grupo puntual de la
    red, $G_{R}$; en general $G_{0}\subseteq G_{R}$. La primera zona de
    Brillouin tiene la simetría del grupo puntual de la red $G_{R}$,
    pero la zona irreducible de Brillouin del cristal NO se determina
    con dicho grupo, sino con $G_{0}$, luego la zona irreducible de
    Brillouin del cristal es mayor o igual que la zona irreducible
    asociada al grupo puntual de la red $G_{R}$. (ahora bien, puede
    ocurrir que lo que sale por la puerta entre por la ventana: recordar
    el asunto de grupos synmórficos y no synmórficos: En un grupo
    espacial no synmórfico ocurre que el grupo puntual "de verdad" es
    $G_{0} \subset G_{R}$, por tanto parecería que la zona irreducible
    fuere mayor que la correspondiente a $G_{R}$, pero si al considerar
    ejes helicoidales y planos de deslizamiento $\{M_{i}|T_{\tau}\}$,
    con $M_{i}\notin G_{0}$ ocurriere que $G0\cup\{M_{i}\}=G_{R}$, es
    decir el grupo puntual ampliado ("de mentira") es $G_{R}$, resulta
    que la zona irreductible del cristal tiene volúmen $1/g$ y está
    generada por los planos de simetría debidos a $G_{R}$. esto es lo
    que pasa en Silicio: su grupo puntual "de verdad" es
    $T_{d} \subset O_{h}$, dim$T_{d}=24$, dim$O_{h}=48$, luego la zona
    irreducible asociada a $T_{d}$ es 1/24 de la primera zona
    brillouinera y la de $O_{h}$ es 1/48, pero el grupo puntual "de
    mentiras" de Si es $O_{h}$, luego la zona irreducible es 1/48 de la
    primera zona brillouinense)

-   La degeneración de los autovalores $E_{n}^{\nu}(k)$ viene dada por
    la dimensión $\chi^{\nu}_{\vec{k}}(E)$ de la representación
    irreducible $\nu$ de $G_{\vec{k}}$. Luego si las representaciones de
    $G_{\vec{k}}$ son unidimensionales, no puede haber intersección de
    bandas en ese punto (coincidencia de dos autovalores), salvo
    degeneración accidental, cual es el caso de un punto $\vec{k}$
    general,

-   Podemos predecir qué correspondencia hay entre autovalores y cómo se
    rompe su degeneración (si la hay) al pasar de un punto más simétrico
    a otro de menor simetría. En efeto: Supongamos que en un punto
    $\vec{k}_{1}$ de la primera zona brillouinera el grupo de simetría
    es $G_{\vec{k}1}$. La degeneración de un autovalor es igual a la
    dimensión de la correspondiente representación irreducible.
    Supongamos que un autovalor $E_{n}^{\nu}(\vec{k}_{1})$ corresponde a
    la representación $\nu$, con caracteres $\chi_{\vec{k}1}^{\nu}(M)$,
    $\forall M \in G_{\vec{k}1}$. Al pasar a otro punto $\vec{k}_{2}$ de
    menor simetría, cuyo grupo puntual es
    $G_{\vec{k}2} \subset G_{\vec{k}1}$, las representaciones
    irreducibles de $G_{\vec{k}1}$ no tienen por qué serlo para
    $G_{\vec{k}2}$, por tanto la posible ruptura de la degeneración y
    correspondencia de representaciones se consigue obteniendo cúantas
    veces las representaciones irreductibles (como los habitantes de
    \...) $\nu$ de $G_{\vec{k}1}$ están en las representaciones
    irreductibles (como \...) $\mu$ de $G_{\vec{k}2}$

    $$a_{\mu}=\frac{1}{g_{\vec{k}2}}\sum_{i}
     \chi^{\nu}_{\vec{k}1}(M_{i}).\chi^{\mu}_{\vec{k}2}(M_{i})^{*} 
     \hspace{1cm} \forall M_{i}\in G_{\vec{k}2}$$

    Siendo $g_{\vec{k}2}$ la dimensión de $G_{\vec{k}2}$. Cuando las
    tablas de caracteres de los grupos no son muy complicadas es fácil
    encontrar esta descomposición por simple inspección

Veamos este asunto con nuestro caso particular del cristal bidimensional
de red cuadrada:

-   Supongamos que variamos $\vec{k}$ desde el origen $\Gamma$ a lo
    largo de una línea de puntos generales hasta un punto $\vec{Z}_{2}$
    y que hemos calculado un autovalor $E_{n}^{\Gamma 5}(\Gamma)$ en
    $\Gamma$ correspondiente a la representación $\Gamma_{5}$. De la
    taula de caracteres de $G_{\Gamma}=C_{4v}$ (Ver taula
    [\[tabes3\]](#tabes3){reference-type="ref" reference="tabes3"})

    ![Bandas de energía para una cristal basado en una red bidimensional
    cuadradra desde el punto $\Gamma$ al $Z$ a lo largo de un punto
    general $\vec{k}$. Lógicamenete, las bandas deben ser non
    degeneratas](bangen.eps){#figes1}

    deducimos que dicho autovalor es doblemente degenerado; supongamos
    que sus autofunciones son de tipo $p_{x}$ y $p_{y}$ respectivamente,
    al pasar de $\Gamma$ a $k$, como $G_{\vec{k}}=\{E\}$, debe romperse
    la degeneración, luego a lo largo del eje $\vec{k}$ hay dos bandas.
    Al llegar a $Z$, como $G_{Z}=\{E,\sigma_{x}\}$ tendremos dos
    autovalores, uno $E_{n}^{Z1}(Z)$, cuya función, par en $x$ será
    $p_{y}$ y otro $E_{n}^{Z2}(Z)$, cuya función, impar en $x$ será
    $p_{x}$ Por simple inspección o aplicando el teorema de
    descomposición de representaciones irreducibles, vemos que
    $\Gamma_{5}=Z1+Z2$, tabla [3](#tabcom1){reference-type="ref"
    reference="tabcom1"}.

-   De $\Gamma$ a $X$ a lo largo de $\Delta$, de $X$ a $M$ lo largo de
    $Z$ y de $M$ a $\Gamma$ a lo largo de $\Sigma$

    ![Ejemplo de bandas a lo largo de la zona irreducible de la primera
    zona del Brillouin para una cristal basado en una red bidimensional
    cuadradra. Hemos supuesto que en $\Gamma$ hay dos bandas de energía,
    una de tipo $\Gamma_{5}$, por tanto duplemente degenerata y otra de
    tipo $\Gamma_{1}$, virtuosa, non degenerata](banirred.eps){#figes2}

    Partamos de lo mismo: $E_{n}^{\Gamma 5}(\Gamma)$ en $\Gamma$ y
    admitamos que sus funciones de onda son de tipo $p_{x}$ o $p_{y}$.
    Al pasar al eje $\Delta$ la degeneración se rompe pues en
    $G_{\Delta 1}$ (Ver taula [\[tabes1\]](#tabes1){reference-type="ref"
    reference="tabes1"}) la representaciones irreducibles son
    unidimensionales; por el teorema de descomposición (Ver taula
    [3](#tabcom1){reference-type="ref" reference="tabcom1"})
    $\Gamma_{5}=\Delta_{1} + \Delta_{2}$ luego habrá una banda
    $\Delta_{1}$ cuyas autofunciones son simétricas en $x$ ($p_{y}$, por
    exiemplo) y otra $\Delta_{2}$ con función antisimétrica en $x$
    ($p_{x}$, por exiemplo). Al llegar al punto $X$, $\Delta_{1}$ se
    convierte en $X_{1}$ y $\Delta_{2}$ en $X_{2}$. Al caminar a lo
    largo de $Z$, $X_{1}$ es $Z_{1}$ y $X_{2}$ es $Z_{2}$, pero en $M$
    ambas dos están englobadas en la representación irreducible $M_{5}$
    (Ver taula [3](#tabcom1){reference-type="ref" reference="tabcom1"}),
    doble, luego tengo degeneración; al pasar de $M$ a $\Gamma$ por
    $\Sigma$ se rompe la degeneración, pues
    $M_{5}=\Sigma_{1} + \Sigma_{2}$ y en $\Gamma$ ambas dos vuelven a
    estar degeneratas.

    En la tabla [3](#tabcom1){reference-type="ref" reference="tabcom1"}
    se dan las compatibilidades entre representaciones y la
    descomposición de las representaciones dobles por grupos de menos
    simetría, (consecuencia del teorema de descomposición ya tantas
    veces mentado).

    ::: {#tabcom1}
      ----------------------------------------------------------- ----------------------------------------------------
                                            Relaciones de compat. 
                                                       Represent. Compatible con
                                                     $\Delta_{1}$ $\Gamma_{1},\Gamma_{3},
                                                                                       \Gamma_{5};X_{1},X_{3}$
                                                     $\Delta_{2}$ $\Gamma_{2},\Gamma_{4},
                                                                                       \Gamma_{5};X_{2},X_{4}$
                                                     $\Sigma_{1}$ $\Gamma_{1},\Gamma_{4},
                                                                                       \Gamma_{5};M_{1},M_{4},M_{5}$
                                                     $\Sigma_{2}$ $\Gamma_{2},\Gamma_{3},
                                                                                       \Gamma_{5};M_{2},M_{3},M_{5}$
                                                          $Z_{1}$ $X_{1},X_{4},M_{1},M_{3},M_{5}$
                                                          $Z_{2}$ $X_{2},X_{3},M_{2},M_{4},M_{5}$
                              $\Gamma_{5}$ se reduce $\Delta_{1}+ 
                            \Delta_{2}$ o $\Sigma_{1}+\Sigma_{2}$ 
        $M_{5}$ se reduce $\Sigma_{1}+\Sigma_{2}$ o $Z_{1}+Z_{2}$ 
      ----------------------------------------------------------- ----------------------------------------------------

      : tabla de compatibilidades de representaciones irreducibles de
      los grupo $G_{\Delta}$, $G_{Z}$ y $G_{\Sigma}$ con $G_{\Gamma}$,
      $G_{X}$, $G_{M}$ para el caso del cristal con red bidimensional
      cuadrada
    :::

# LA ENERGÍA EN k Y -k. EL OPERADOR DE CONJUGACIÓN

Si el cristal tiene simetría de inversión, es inmediato demostrar que
$E_{n}(k)=E_{n}(-k)$, pues $i\psi_{\vec{k}}=\psi_{-\vec{k}}$; pero si no
la tiene parecería que ya no tiene por qué cumplirse dicha propiedad en
los autovalores, sin embargo ello se cumple teniendo en cuenta otras dos
circunstancias: A) Que el operador hamiltoniano es hermítico y, por
tanto, una autofunción $\psi_{n\vec{k}}$ y su conjugada
$\psi_{n\vec{k}}^{*}$ tienen el mismo autovalor B) Que las
transformaciones de simetría no transforman al vector $\vec{r}$ en un
complejo, c'est à dire, $M\vec{r}$ es real $\forall M\in G$. El operador
de conjugación convierte una función en su complejo conjugada:

$$j\psi(\vec{r})=\psi^{*}(\vec{r})$$

Vamos a demostrar que $j\psi_{n\vec{k}}(\vec{r}) \rightarrow 
 \psi_{n\vec{k}}^{*}(\vec{r})$. Operaremos en dos etapas:

-   El operador de conjugación conmuta con las transformaciones de
    simetría. En efeto:

    $$\begin{aligned}
      Mj\psi(\vec{r})&=&M\psi^{*}(\vec{r}) = \psi^{*}(M^{-1}\vec{r})
      \nonumber \\
      jM\psi(\vec{r})&=&j\psi(M^{-1}\vec{r})= 
      \psi^{*}(M^{-1}\vec{r})  
    \end{aligned}$$

    Pues $M^{-1}\vec{r}$ es real

-   Séase un estado propio del hamilton, demostremos que
    $j\psi_{n\vec{k}}(\vec{r}) = \psi_{n\vec{k}}^{*}(\vec{r})$ pertenece
    al subespacio invariante $-\vec{k}$. Como $E_{n}(\vec{k})$ es un
    autovalor, $\psi_{n\vec{k}}(\vec{r})$ es una función de las
    representaciones irreducibles del grupo de transleisions:
    $T_{\vec{R}}\psi_{n\vec{k}}(\vec{r}) 
     = \exp[-ikR]\psi_{n\vec{k}}(\vec{r})$ luego:

    $$\begin{aligned}
     \{E|T_{\vec{R}}\}j\psi_{nk}(\vec{r})&=& 
      T_{\vec{R}}j\psi_{n\vec{k}}(\vec{r})= 
      T_{\vec{R}}\psi_{nk}^{*}(\vec{r}) \nonumber \\
        &= &jT_{\vec{R}}\psi_{n\vec{k}}(\vec{r})
       = j\exp[-i\vec{k}\cdot \vec{R}]\psi_{n\vec{k}}(\vec{r})
       = \exp[i\vec{k}\cdot \vec{R}]\psi_{n\vec{k}}^{*}(\vec{r})
      \nonumber \\
        &=&\chi_{-\vec{k}}(\vec{R})\psi_{n\vec{k}}^{*}(\vec{r})
    \end{aligned}$$

Ergo $j\psi_{n\vec{k}}(\vec{r})=\psi_{n\vec{k}}^{*}(\vec{r})$ debe de
ser una función propia perteneciente al subespacio invariante $-\vec{k}$
luego debe de ser el ESTADO $|\psi_{n-\vec{k}}>$, pero como
$\psi_{n\vec{k}}(\vec{r})$ y $\psi_{n\vec{k}}^{*}(\vec{r})$ tienen el
mismo autovalor $E_{n}(\vec{k})$, dedúcese que
$E_{n}(\vec{k})=E_{n}(-\vec{k})$ (Let us observe que tenemos dos
autofunciones ortogonales asociadas al mismo autovalor:
$\psi_{n\vec{k}}(\vec{r})+\psi_{n\vec{k}}^{*}(\vec{r})$, que es real,
como la vida misma y
$\psi_{n\vec{k}}(\vec{r})-\psi_{n\vec{k}}^{*}(\vec{r})$, que es
puritamente imaginaria). To esto está relacionado con la invariancia de
las leyes de la Phýsica bajo inversión temporal.

[^1]: Max Born, alemán y Premio Nobel de Física, que tomó la juiciosa
    decisión de salir por piennas de la Alemania nazi, pues Hitler y sus
    amiguetes tenían un peculiar "interés" personal en él bastante
    perjudicial para su integridad física, moral e intelectual. Max Born
    fue amigo personal de Don Alberto Einstein. Teodoro Von Kàrman,
    nacido en Jozsefvaros, distrito de Budapest (Hungría); aparte de sus
    trabajos en mecánica cuántica fué unos de los mejores especialistas
    en Física de fluidos, con portentosas aplicaciones a la aviación.
    Puede considerársele uno de los más importantes responsables del
    desarrollo de la Fuerza Aérea Norteamericana a partir de la segunda
    Guerra Mundial, tanto en el impulso de diseño de aviones a reacción
    como en la estrategia de intervención. Además fué el científico que
    explicó por qué se hundió el puente de Tacoma (efectos no lineales
    en fluidos). En relación con este asunto, al principio más de un
    listillo menospreció dicha explicación ("Otra locura teórica de Von
    Kàrman"), que, al fin y a la postre resultó ser totalmente correcta
