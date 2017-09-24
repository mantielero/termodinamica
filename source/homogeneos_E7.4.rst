Ejercicio 7.4
=============

Calcular las variaciones de entalpia y entropía del metano, debido a un cambio de estado desde 250K y 70 bares hasta 200K y 50 bares haciendo la hipótesis de que el valor de :math:`c_p` permanece constante, siendo su valor :math:`c_p = 2180 Jkg^{-1}K^{-1}`.

Solución
--------

En primer lugar comprobamos si el metano en los estados dados en el enunciado tiene un comportamiento ideal o real, para lo que calculamos el factor de compresibilidad en dichos estados.

En el estado inicial, estado 1, la presión y temperatura reducida tienen un valor

.. math::

   p_{R_1} = \frac{70}{46,4} = 1.51\\
   T_{R_1} = \frac{250}{109.7} = 1.31

con lo que entrando en el diagrama del factor de compresibilidad se obtiene un valor de


.. math::

   Z = 0.78

de lo que se deduce que su comportamiento es como gas real.

En el estado final, estado 2, la presión y temperatura reducida tienen un valor

.. math::

   p_{R_2} &= \frac{50}{46.4} = 1.08\\
   T_{R_2} &= \frac{200}{190.7} = 1.05

y por tanto el valor del factor de compresibilidad es

.. math::

   Z = 0.55

y su comportamiento es como gas real.

De las gráficas generalizadas, las correcciones por compresibilidad para la variación de entalpia tienen un valor de

.. math::

   \left( \frac{h^*-h}{T_c}\right)_1 = 9.3 \frac{kJ}{kmol\cdot K}\\
   \left( \frac{h^*-h}{T_c}\right)_2 = 15.2 \frac{kJ}{kmol\cdot K}


y las correcciones por compresibilidad para la variación de entropía valen

.. math::

   (s^*-s)_1 = 5.5\frac{kJ}{kmol\cdot K}\\
   (s^*-s)_2 = 12.1\frac{kJ}{kmol\cdot K}

La variación de entalpia viene por tanto dada por la expresión

.. math::

   h_2-h_1 = h_2^* - h_1^* + \frac{T_c}{M} \left[ \left( \frac{h^* -h}{T_c}\right)_1 - \left( \frac{h^* -h}{T_c}\right)_2 \right]

o lo que es lo mismo por

.. math::

   h_2-h_1 = \int_1^2 c_p(T) dT + \frac{T_c}{M} \left[ \left( \frac{h^* -h}{T_c}\right)_1 - \left( \frac{h^* -h}{T_c}\right)_2 \right]

y con la hipótesis del enunciado de que :math:`c_p` permanece constante queda

.. math::

   h_2-h_1 = c_p(T_2-T_1) + \frac{T_c}{M} \left[ \left( \frac{h^* -h}{T_c}\right)_1 - \left( \frac{h^* -h}{T_c}\right)_2 \right]\\
   h_2-h_1 = 2.180(200-250) + \frac{190.7}{16.04} (9.3-15.2) = -178.9 \frac{kJ}{kg}

La variación de entropía viene por tanto dada por la expresión

.. math::

   s_2-s_1 = s_2^* -s_1^* + \frac{1}{M}[(s^*-s)_1-(s^*-s)_2]

quedando

.. math::

   s_2 - S_1 = \int_1^2 c_p\frac{dT}{T}- \int_1^2 R \frac{dp}{p}+ \frac{1}{M}[(s^*-s)_1-(s^*-s)_2]

y con la hipótesis del enunciado queda

.. math::

   s_2-s_1 &= c_p\ln \frac{T_2}{T_1}-R\ln\frac{p_2}{p_1}+\frac{1}{M}[(s^*-s)_1-(s^* -s)_2]\\
   s_2-s_1 &= 2180 \ln\frac{200}{250} - 518.3\ln\frac{50}{70}+\frac{1000}{16.04}(5.45-12.05) = -723.6\frac{J}{kg \cdot K}

Se hace notar que la variación de entropía es negativa, lo que no contradice el segundo principio de la termodinámica, ya que el metano no tiene por que ser un sistema aislado.
