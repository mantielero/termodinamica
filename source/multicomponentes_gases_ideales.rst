Mezcla de gases ideales
=======================

Relaciones p, v, T para mezclas de gases ideales
------------------------------------------------

En la presente sección nos vamos a referir exclusivamente a mezclas de gases ideales y vamos a introducir los dos modelos utilizados al considerar esta idealización: el modelo de Dalton y el de Amagat.

Consideremos un sistema consistente en un determinado número de gases contenidos en un recipiente cerrado de volumen *V*. La temperatura de la mezcla gaseosa es *T* y la presión *p*. La mezcla total se considera como un gas ideal, de modo que *p*, *V*, *T* y el número total de moles de la mezcla, *n*, están relacionados mediante la ecuación:

.. math::

   p = n \frac{RT}{V}

Con relación a este sistema vamos a considerar sucesivamente los modelos de Dalton y Amagat.

Modelo de Dalton
^^^^^^^^^^^^^^^^

Este modelo es consistente con el concepto de gas ideal; esto es un gas compuesto de moléculas que ejercen fuerzas despreciables unas sobre otras por lo que el comportamiento de cada componente no se ve afectado por la presencia del resto de los componentes y que además cada molécula ocupa un volumen despreciable comparado con el que ocupa el gas de modo que puede considerarse que cada componente ocupa todo el volumen disponible. En resumen el modelo de Dalton supone que cada componente de la mezcla se comporta como un gas ideal que estuviera él solo ocupando todo el volumen disponible a la temperatura de la mezcla.

Para cada componente se verifica, pues:

.. math::

   p_1 V = n_1 RT \\
   p_2 V = n_2 RT \\
   ...
   p_k V = n_k RT \\   

Sumando ambos miembros de estas igualdades se obtiene:

.. math::

   (p_1 + p_2 + ... + p_k) V = (n_1+n_2+...+n_k)RT


y teniendo en cuenta (9.4),

.. math::

   (p_1 + p_2 + ... + p_k) V = nRT



Comparando esta última expresión con (9.59), obtenemos que:

.. math::

   p = \sum_{i=1}^k p_i

La relación entre la presión del componente *i* y la presión de la mezcla se obtiene del cociente entre cada una de las ecuaciones (9.60) y la ecuación (9.59):

.. math::

   \frac{p_i}{p} = \frac{n_i}{n} = x_i \rightarrow p_i = x_i p


A :math:`p_i` se le da el nombre de presión parcial del componente :math:`i^*` en la mezcla. Esta presión parcial vemos que es igual al producto de la fracción molar del correspondiente componente por la presión de la mezcla.

Modelo de Amagat
^^^^^^^^^^^^^^^^

La hipótesis que subyace en el modelo de Amagat es que cada componente de la mezcla se comporta , por separado, como un gas ideal a la presión y temperatura de la mezcla. El volumen que los :math:`n_i`moles del componente *i* ocuparían, si ese componente estuviera solo a (*T*, *p*), se llama volumen parcial :math:`V_i` del componente *i*. Este volumen parcial puede calcularse haciendo uso de la ecuación térmica de estado del gas ideal:

.. math::

   V_i = \frac{n_i RT}{p}

Si esta ecuación la dividimos por el volumen total *V*, siendo :math:`V = \frac{nRT}{p}`, obtendremos:

.. math::

   \frac{V_i}{V} = \frac{n_i}{n} = x_i

Así pues, el volumen parcial del componente *i* puede expresarse en función de su fracción molar :math:`x_i` y del volumen total *V*:

.. math::

   V_i = x_i V

Esta relación entre la fracción del volumen y la fracción molar subyace en el uso del término análisis volumétrico cuando una mezcla se especifica por los volúmenes parciales de sus componentes.

Sumando en (9.64) para todos los componentes:

.. math::

   \sum_{i=1}^k V_i = V \sum_{i=1}^k x_i = V

La mezcla ideal de gases ideales es un caso particular de la disolución ideal analizada en 9.4

Propiedades termodinámicas de la mezcla de gases ideales
--------------------------------------------------------

La aplicación del principio de conservación de la energía y/o del segundo principio de la termodinámica a un sistema que consista en una mezcla ideal de gases ideales precisa de la evaluación de las variaciones de energía interna, entalpia y/o de la entropía de la mezcla. Nuestro objetivo en esta sección es desarrollar los medios para evaluar tanto la energía interna, entalpia y entropía de la mezcla como sus variaciones cuando el sistema (la mezcla) experimenta un proceso que la lleva desde un estado termodinámico (:math:`T_1`, :math:`p_1`) a otro (:math:`T_2`, :math:`p_2`).

.. math::

   * Obsérvese que estos resultados ya se han obtenido anteriormente (Cfr 9.3.2)

De las expresiones (9.9), teniendo en cuenta (9.46), se obtiene:


.. math::

   U = \sum_{i=1}^k n_i \overline{u_i} = \sum_{i=1}^k n_i u_i \\
   H = \sum_{i=1}^k n_i \overline{h_i} = \sum_{i=1}^k n_i h_i 

Como cada componente de la mezcla se comporta como gas ideal, tanto U como H serán función sólo de la temperatura. Para la entropía, y únicamente para el tipo de proceso que consideramos en el apartado siguiente, podemos llegar a una expresión análoga a las anteriores.

Procesos de mezclado en los que intervienen gases ideales
---------------------------------------------------------

Consideremos el proceso de mezclado de varios gases que se mantienen a *T* y *p*, separados en sus correspondientes volúmenes parciales. Si el recinto que los contiene está aislado y quitamos los tabiques que los mantienen separados, como la energía total se mantiene constante tendremos que

.. math::

   U_1 = U_2

   

o bien

.. math::

   \sum_i x_i \left. u_i \right|_1 = \sum_i x_i \left. u_i \right|_2

Lo mismo podemos decir de la entalpia. Para analizar la variación de entropía consideremos el caso siguiente:

.. figure:: ./img/fig_9_2.png

Sea un dispositivo en el que mediante émbolos rígidos se confinan dos gases según se muestra en la figura. El émbolo :math:`E_1` es permeable al gas 1, el tabique *A* es permeable al gas 2 y el :math:`E_2` es impermeable.

_Estado 1_: :math:`E_1` adosado a *A*. Los gases 1 y 2 están no mezclados, a la temperatura *T* y presiones respectivas :math:`p_1` y :math:`p_1`-

Estado 2: Gas perfecto mezclado a la temperatura *T*.

Desplazando, tan lentamente como sea preciso, el conjunto E1-E2 de los dos émbolos ligados mediante el vástago 1, se obtiene una zona de mezcla entre las paredes Ei y A; el desplazamiento inverso separa los gases, siendo la operación reversible, por lo que puede imaginarse una sucesión de estados de equilibrio entre los estados inicial y final.

Es importante destacar que los volúmenes ocupados por el gas 1 y 2, no varían durante el proceso, por lo que, al mantenerse la temperatura, tampoco variarán pi y P2-

Si denominamos Ac al área de la sección recta del cilindro, el émbolo Ei está sometido en su cara izquierda a un fuerza p\ Ac dirigida hacia la derecha y en la cara derecha a una fuerza -(pi + P2) Ac dirigida hacia la izquierda. La fuerza resultante sobre Ei es -p2 Ac.

Sistemas multicomponentes. Mezcla no reactiva de gases
25

El sistema ejerce sobre la cara izquierda de E2 una fuerza P2 Ac, por lo que la fuerza resultante sobre el sistema en conjunto de los dos émbolos es nula, como corresponde a una evolución en equilibrio.

De lo que acabamos de ver resulta que el trabajo es nulo, la temperatura es constante durante el proceso por lo que AU = 0, aplicando el primer principio obtenemos

Q 1,2 = 0
Q\i

Al ser la transformación reversible AS = —'1 = 0 por lo que

S - S0 = ns - n¡s0i - 0

Esto es:

ns = V] n,s0¿; s = ^2xíS0í	(9.66)
t	i

En (9.66) s es la entropía molar de la mezcla a T y p y es la entropía del componente i evaluada a T y p¡, es decir en las condiciones iniciales.

Proceso real de mezclado
^^^^^^^^^^^^^^^^^^^^^^^^

Consideremos a continuación el caso esquematizado en la figura adjunta:
Dos depósitos A y B están unidos mediante un con-1	ducto provisto de una llave, en los depósitos hay dos gases
--------- a la misma presión y temperatura, que es la del medio ambiente. Se abre la llave y se espera hasta que se alcanza el -------- *	--------- equilibrio.

La transformación se realiza a T constante y los gases tenderán a difundirse el uno en el otro hasta que llenen todo el depósito, momento en el que alcanzarán, respectivamente, las presiones Pi y P2-

Es importante destacar, en este caso, que en las condiciones iniciales los gases están a la misma temperatura y presión y que en el estado final se mantiene la temperatura, pero las presiones de cada gas son distintas, a diferencia de lo que ocurre en el caso analizado en el apartado anterior.

Para calcular la variación de entropía podremos utilizar la ecuación:

ds = ^dT - R — T	v
ds = -R^-P
al ser la transformación a T constante:

26
Sistemas multicomponentes. Mezcla no reactiva de gases

En el caso del componente i, tendremos que al cambiar su presión de p a la entropía cambia desde s0¿(p, T) a s¿(p¿, T), siendo:

Si
di P*
- s0i = -it ln —
V

esto es:

~ s0i -Rln —
P

El valor de la entropía final será:

S = njSj
X
= Y' n¡(s0i - Rln —)
L—¿	p
i
= n	— l?y^a;t ln X{
. i	i

Esta ecuación, al dividirla entre el número total de moles y reordenarla queda:

^^mezcla — ^	^ ^ ^i^oi — Jí X¿ ln X{	(9.6T)
t	«

en la que s es la entropía molar de la mezcla a T y p y s01- es la entropía molar del componente i a las mismas T y p. Por lo tanto s — x¡sQi representa el incremento de entropía por mol que se produce al mezclar gases a las mismas T y p. Téngase en cuenta que siempre será positiva ya que X{ siempre será menor que la unidad. Sólo en el caso de que todos los gases sean iguales x = 1 y el incremento de entropía sería nulo ( paradoja de Gibbs). No parece ser que tenga sentido hablar de mezcla en el caso de que consideremos gases iguales en las mismas condiciones de T y p.

Se propone como ejercicio el encontrar las condiciones finales en el caso de mezcla de tres gases, contenidos en tres recintos aislados del exterior, y que se encuentran a distinta T y p.

Variaciones de las propiedades termodinámicas
---------------------------------------------

En el trabajo con mezclas más que los valores de estas propiedades, lo que nos interesa es poder evaluar las variaciones de las mismas cuando la mezcla experimenta un proceso durante el cual la composición permanece constante; esto es, tenemos un sistema formado por varios componentes cuyo número de moles permanece constante durante el proceso, y, por lo tanto, también permanece constante el número de moles de la mezcla.

Las variaciones de U, H, y S durante el proceso, apartir de (9.65) y (9.66), serán:

Sistemas multicomponentes. Mezcla no reactiva de gases
27

k
AU = ^n¿(ui2 - m¿i)
¿=i
k
AH = ^n¿(/i¿2 - hn)	(9.68.a)
i—i
k
AS = ^2 ni(Si2 - Sil)
1=1

donde y h{ se calculan a la temperatura de la mezcla (a T2 en el instante final y a Ti en el instante inicial) mientras que se calcula a la temperatura y presión de la mezcla; esto es,

k
AU= £nt[u¿(T2)-u,(Ti)]
t=i
k
AH = Y.	~ hi(Ti)]	(9-68-b)
t=i
k
AS = £n,MT2,p2) - 6¿(Ti,pi)]
i=1

ya que lo que hemos denominado ASmezcia es el mismo para el estado inicial y final puesto que no depende ni de T ni de p, sino sólo de la composición según se ve de (9.67).
du

Finalmente si las expresiones dadas en (9.65) las dividimos por n, como cv —

dT
dh
cr dT

se obtienen las expresiones siguientes de los calores específicos a volumen y presión
constante para una mezcla ideal de gases ideales:

k	r\	k
EOUi
x'~ñr ~ / .x'cv' 1 = 1	" 1=1
A dhi	A
cp - Z_^Xi - / ,XjCpi
(9.69)
i=i
¿=i
