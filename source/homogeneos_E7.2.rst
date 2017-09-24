Ejercicio 7.2
=============

En un recipiente de :math:`3m^3` hay metano (:math:`CH_4`) a una temperatura de 250K y una presión de 70bar. Calcular:

a)	Las constantes de la ecuación de Redlich y Kwong, sabiendo que la presión y temperatura críticas del metano son respectivamente, :math:`p_c = 46,4bar` y :math:`T_c = 190,7K`
b)	La masa contenida en el recipiente aplicando la ecuación de gas ideal y la ecuación de Redlich y Kwong.
c)	Lo mismo que en el apartado anterior, pero suponiendo que la presión del metano es lóar y su temperatura es 650K.


Solución
--------

a) El valor de las constantes a y b de la ecuacion de Redlich y Kwong viene dado por

.. math::

   a = 0,4275\frac{R^2T_c^{2,5}}{p_c}

y

.. math::

   b = 0,08664 \frac{RT_c}{p_c}

quedando

.. math::

   a = 0,4275 \frac{518,3^2\cdot 190,7^{2,5}}{46,4 \cdot 19^5} = 12429,6 \frac{Pa m^6 K^{0,5}}{kg^2}

y

.. math::

   b = 0,08664 \frac{518,3 \cdot 190,7}{46,4\cdot 10^5} = 1,846 \cdot 10^{-3}\frac{m^3}{kg}


b) Utilizando la ecuación de gas ideal

.. math::

   pv = RT

se obtiene que

.. math::

   v = \frac{RT}{p} = \frac{518,3 \cdot 250}{70\cdot 10^5} = 0,0185\frac{m^3}{kg}


y por tanto, la masa contenida en el recipiente es

.. math::

   m = \frac{V}{v} =  \frac{3}{0,0185} = 162,16kg

Utilizando la ecuación de Redlich y Kwong

.. math::

   p = \frac{RT}{v-b}- \frac{a}{ T^{\frac{1}{2}}v(v+b) }


queda

.. math::

   70\cdot 10^5 = \frac{518,3\cdot 250}{ v - 1,846\cdot 10^{-3} } - \frac{12429,6}{ 250^\frac{1}{2}v(v+1,846\cdot 10^{-3})}


ecuación que resuelta por cualquier método numérico da

.. math::

   v = 0,01429 \frac{m^3}{kg}


siendo la masa

.. math::

   m = 209,94 kg

Se observa una gran diferencia entre los resultados obtenidos por los dos procedimientos. Esto se debe a que cuando la presión es alta y la temperatura es baja, el gas no tiene un comportamiento ideal.

c) Si la presión es de 1 bar y la temperatura es 650K, procediendo de forma análoga al apartado anterior se obtiene, utilizando la ecuación de gas ideal

.. math::

   v = 3,37\frac{m^3}{kg}

y por tanto

.. math::

   m = 0,89kg

Utilizando la ecuación de Redlich y Kwong se obtiene

.. math::

   v = 3,37\frac{m^3}{kg}


y una masa de

.. math::

   m = 0,89kg

Se puede observar que en este caso, en el que la presión es baja y la temperatura es alta, y por tanto el gas tiene un comportamiento ideal, las masas calculadas mediante los dos procedimientos coinciden, al contrario de lo que ocurría en el caso anterior.
