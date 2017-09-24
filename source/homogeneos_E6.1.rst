Ejercicio 7.1
=============


En un recipiente de :math:`3m^3` hay metano (:math:`CH_4`) a una temperatura de 250K y una presión de 70bar. Calcular:

a)	Las constantes de la ecuación de Van der Walls, sabiendo que la presión y temperatura críticas del metano son respectivamente, :math:`p_c = 46,4 bar` y :math:`T_c = 190,7K`.

b)	La masa contenida en el recipiente aplicando la ecuación de gas ideal y la ecuación de Van der Walls.

c)	Lo mismo que en el apartado anterior, pero suponiendo que la presión del metano es 1bar y su temperatura es 650K

Solución
--------

a) De las ecuaciones anteriores tenemos que las constantes de la ecuación de Van der Walls vienen dadas en función de la presión y temperatura crítica por

.. math::

   a = \frac{27}{64}\frac{R^2T_c^2}{p_c}


y

.. math::

   b = \frac{RT_c}{8p_c}

quedando en este caso

.. math::

   a = \frac{27}{64} \frac{518,3^2 \cdot 190,7^2}{46,4\cdot 10^5} = 888,24\frac{Pa\cdot m^6}{kg^2}

y

.. math::


   b = \frac{518,3\cdot 190,7}{8\cdot 46,4 \cdot 10^5} = 0,00266\frac{m^3}{kg}



b) Utilizando la ecuación de gas ideal se obtiene que

.. math::

   pv = RT

se obtiene que

.. math::

   v = \frac{RT}{p} = \frac{518,3 \cdot 250}{70 \cdot 10^5} = 0,0185 \frac{m^3}{kg}


y por tanto, la masa contenida en el recipiente es

.. math::

   m = \frac{V}{v} = \frac{3}{0,0185} = 162,16kg

Utilizando la ecuación de Van der Walls

.. math::

   \left( p + \frac{a}{v^2} \right) \cdot (v-b) = RT

queda

.. math::

   \left(  70\cdot 10^5 + \frac{888,24}{v^2}\right) \cdot (v-0,00266) = 518,3 \cdot 250



es decir

.. math::

   \left(  70\cdot 10^5 + \frac{888,24}{v^2}\right) \cdot (v-0,00266) = 129575

que resolviendo por el método de prueba y error u otro cualquiera da

.. math::

   v = 0,01371 \frac{m^3}{kg}


y la masa es

.. math::

   m = 218,8kg


Se observa una gran diferencia entre los resultados obtenidos por los dos procedimientos. Esto se debe a que cuando la presión es alta y la temperatura es baja, el gas no tiene un comportamiento ideal.

c) Si la presión es de 1bar y la temperatura es 650K, procediendo de forma análoga al apartado anterior se obtiene, utilizando la ecuación de gas ideal

.. math::

   v = 3,37 \frac{m^3}{kg}

y por tanto

.. math::

   m= 0,89kg


Utilizando la ecuación de Van der Wails se obtiene

.. math::

   v=3,37\frac{m^3}{kg}

y la masa contenida sale

.. math::

   m = 0,89kg

Se puede observar que en este caso, en el que la presión es baja y la temperatura es alta, y por tanto el gas tiene un comportamiento ideal, las masas calculadas mediante los dos procedimientos coinciden, al contrario de lo que ocurría en el caso anterior.
