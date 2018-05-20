Propiedades molares parciales
=============================

En la presente discusión se introducirá el concepto de propiedad molar parcial y se verá su aplicación. Este concepto juega un papel importante en el análisis de los sistemas multicomponentes.

Una propiedad termodinámica extensiva X de un sistema monocomponente y monofásico es una función de dos propiedades intensivas independientes y de la cantidad de sustancia del sistema. Eligiendo como variables independientes la presión y la temperatura y el número de moles como medida de la cantidad de sustancia, tendremos X = X(T,p,n). Para un sistema monofásico-multicomponente, la propiedad extensiva X será, pues, función de la temperatura, la presión y del número de moles de cada componente, X = X(T,p, ) (i = 1,2, • • • , k)

Si cada número de moles de cada componente se multiplica por un factor a, la cantidad de sustancia del sistema quedará multiplicada por el mismo factor y así también el valor de la propiedad extensiva X. Esto es:

.. math::

   X(T,p,\alpha n_1, \alpha n_2, ... \alpha n_k) = \alpha X(T,p,n_i)
   
   
Esta ecuación nos indica que *X* es una función homogénea de grado uno en los :math:`n_i` de modo que por el teorema de Euler de las funciones homogéneas podemos escribir

.. math::

   \frac{\partial X}{\partial n_1} n_1 + ... + \frac{\partial X}{\partial n_k} n_k = X

o lo que es lo mismo

.. math::

   X = \sum_{i=1}^k n_i \left. \frac{\partial X}{\partial n_i} n_1 \right|_{T,p,n_j}
 
donde el subíndice :math:`n_j` indica que todos los *n* excepto :math:`n_i`se han mantenido fijbs durante la diferenciación.

La propiedad molar parcial :math:`\overline{x_i}` es por definición:

.. math::

   \overline{x_i} = \left. \frac{\partial X}{\partial n_i}  \right|_{T,p,n_j} \hspace{2cm} j \neq i



:math:`\overline{x_i}` es una propiedad de la mezcla y no simplemente una propiedad del componente *i*; es decir, :math:`\overline{x_i}` depende, en general de la temperatura, presión *y* composición de la mezcla, :math:`\overline{x_i}=\overline{x_i}(T,p,n_i)`. Las propiedades molares parciales son propiedades intensivas de la mezcla.

A la vista de la ecuación (9.7), la ecución (9.6) se puede escribir en la forma:

.. math::

   X= \sum_i^k n_i \overline{x_i}

Esta ecuación muestra que la propiedad *X* puede expresarse como una suma ponderada de las propiedades molares parciales :math:`\overline{x_i}`.

Eligiendo que la propiedad extensiva en (9.8) sea el volumen, la energía interna, la entalpia y entropía respectivamente, se tendrá:

.. math::

   V= \sum_i^k n_i \overline{v_i} \\
   U= \sum_i^k n_i \overline{u_i} \\
   H= \sum_i^k n_i \overline{h_i} \\
   S= \sum_i^k n_i \overline{s_i} 
   


donde :math:`\overline{v_i}`, :math:`\overline{u_i}`, :math:`\overline{h_i}` y :math:`\overline{s_i}` representan el volumen, la energía interna, la entalpia y la entropía molar parcial. Expresiones análogas pueden escribirse para la función de Gibbs, *G*, y la función de Helmholtz, *A*.

Las propiedades molares parciales pueden evaluarse de varias formas. 
En primer lugar, si la propiedad *X* puede medirse, :math:`\overline{x_i}`, puede obtenerse extrapolando el gráfico que da :math:`\left( \frac{\Delta X}{\Delta n_i} \right)_{T,p,n_j}` frente a :math:`\Delta n_i`; esto es,

.. math::

   \overline{x_i} = \left. \frac{\partial X}{\partial n_i} \right)_{T,p,n_j} = \lim_{\Delta n_i \rightarrow 0} \left. \frac{\Delta X}{\Delta n_i} \right)_{T,p,n_j} 

Si se conoce una expresión para *X* en función de sus variables independientes, :math:`\overline{x_i}` puede evaluarse por diferenciación. La derivación puede ser analítica si la función viene expresada analíticamente o numérica si la función está dada en forma tabular.

Un procedimiento gráfico de fácil aplicación para evaluar las propiedades molares parciales, cuando se dispone de datos experimentales, es el método-dé las intersecciones. Este método puede aplicarse para la evaluación de cualquier propieddad molar parcial. A título de ejemplo se puede considerar la determinación del volumen molar parcial en el caso de una disolución formada por dos componentes A y B.

La curva experimental que muestra el volumen molar de la disolución en función de la fracción molar del componente B, para una temperatura y presión determinadas, puede ser como la representada en la figura 9.1. En esta curva se representa en ordenadas el volumen molar de la mezcla, v = V/n, y en abscisas la fracción molar del componente B. Como puede verse en la gráfica, el punto de intersección de la curva con el eje en A, representa el volumen molar correspondiente al componente puro A en las condiciones (p, T) de la mezcla, ya que en ese punto xB
Figura 9.1
es igual a cero. Lo mismo se puede decir con la intersección con el eje B, respecto a ese componente.

De acuerdo con (9.9), el volumen de la mezcvla vendrá dado por:
V = nAvA +nBvB
en la que vA y vB son los volúmenes molares parciales de A y B respectivamente.

También se puede dar el volumen de la mezcla en función del volumen molar medio de la misma, representado en la figura 9.1, mediante la expresión:

V = v(nA +nB)

Teniendo en cuenta esta última expresión y la definición de volumen molar parcial, se puede obtener como valor del volumen molar parcial para el componente A, por ejemplo, la expresión:
OV
Va dnt
= v + (nA +nB)
dv
dnt
T,p,n,
" T,PlnB

A fin de poder utilizar la gráfica que se ha mencionado, se tendrá que referir la expresión anterior a la fracción molar del componente B, para lo que se realizan las transformaciones siguientes:

dV
Va dnt
= v+(nA + nB)
dv
T,p,n
dxt
dx.
T,p,n.
dnÁ
T,p,n.
Sistemas multicomponentes. Mezcla no reactiva de gases
5

Téngase en cuenta que aunque nB se mantiene constante, xB también depende de nA. 

Para calcular dxB/dnA |x,p,nB, se parte de la definición de xB:

nc
n, + nF

por lo que:

dxB _	nB
dnA (nA + nB)2

Sustituyendo en vA, se obtiene:

dV
dn.
= V — X-í
dv
T,p,nE

..*\
T,p,nB J

Teniendo en cuenta la figura 9.1 y esta expresión, puede verse con facilidad que vA vendrá dada por la intersección de la tangente en el punto considerado (xB,v) con el eje de ordenadas en A. Para el otro componente se puede obtener una expresión análoga.

Se debe tener en cuenta, como ya se ha indicado y en la gráfica se ve con claridad, que para valores determinados de temperatura y presión, vA y vB dependen de xB y no son iguales a los correspondientes valores molares de A o B puros, representados en la figura por vA y vB respectivamente y que sólo son función de la temperatura y presión.

Vamos a concluir el presente análisis evaluando el cambio en el volumen de una mezcla de componentes puros que están a la misma presión y temperatura, resultado para el que se da una aplicación más adelante. El volumen total de los componentes puros antes de la mezcla es:

I
k
Vcom.puro — ^ ' TliV{
<=1

donde v¡ es el volumen específico molar del componente puro i. El volumen de la mezcla es:

k
Vmezcla = ^ ^ i=l

donde es el volumen molar parcial del componente i en la mezcla. El cambio de volumen debido a la mezcla es:

o
A14
V - V
* m.p.z Y c
comp.puro
k	k
- Y^TliVi Í=l	i=l
k
AVme, = £><(* - *0	(9.10)
-L	¿=i

Resultados análogos pueden obtenerse para otras propiedades extensivas, por ejemplo:

6
Sistemas multicomponentes. Mezcla no reactiva de gases
k
mezcla. — ^ ' Tljjüi ~ U¿) i=l
k
&Hmezcla = ^	~ h{)	(9.11)
1=1 k
ASmezcla — ^ ^ ^i(^t	^t)
t=l

En las ecuaciones (9.11),	/i¿ y s,- representan la energía, entalpia y entropía molar del
componente puro i. Los símbolos ñ¿, y s, representan las respectivas propiedades molares parciales.
