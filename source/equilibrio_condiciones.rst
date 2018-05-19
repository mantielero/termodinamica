Condiciones de equilibrio de fases
==================================

Acabamos de ver que en un sistema monofásico aislado en equilibrio la presión y la temperatura son idénticas para todas las partes en equilibrio. Veamos ahora qué condición han de cumplir los sistemas multifase.

El procedimiento seguido será el mismo que hemos utilizado antes, pero ahora los subsistemas I y II representarán distinta fase y la cantidad de sustancia que hay en cada una de las mismas podrá cambiar, aunque la cantidad total de materia que hay en el sistema permanezca constante. Por lo tanto, consideraremos un sistema en el que :math:`V_{sis} = \text{ constante}`, :math:`n_{sis} = \text{ constante}`, :math:`U_{sis} = \text{ constante}`, siendo :math:`n_{sis}` la cantidad total de sustancia que hay en el sistema, representada por el número total de moles. Para este sistema:

.. math::
   \left.
   \begin{array}
   V_{sis} = V_I + V_{II} \\
   n_{sis} = n_I + n_{II} \\
   U_{sis} = U_I + U_{II}
   \end{array}
   \right}
   \Rightarrow
   
   dV_I + dV_{II} = 0 \\
   dn_I + dn_{II} = 0 \\
   dU_I + dU_{II} = 0
   
y

.. math::

   dV_I = —dV_{II} \\
   dn_I = -dn_{II} \\
   dU_I = —dU_{II}

Respecto al caso anterior vemos que la única variación es que hemos tenido que fijar la cantidad de sustancia.


De (8.11) aplicada a una especie química, podemos deducir:

.. math::

   dS = \frac{dU}{T} + \frac{p}{T} dV - \frac{\mu}{T} dn


Para el sistema que estamos considerando:

.. math::

   dS_{sis} = dS_I + dS_{II} = 0
   
en donde:

.. math::

   dS_I = \frac{dU_I}{T_I} + \frac{p_I}{T_I}dV_I - \frac{\mu_I}{T_I} dn_I \\
   dS_{II} = \frac{dU_{II}}{T_{II}} + \frac{p_{II}}{T_{II}}dV_{II} - \frac{\mu_{II}}{T_{II}} dn_{II} 
 
Sustituyendo en (8.59), teniendo en cuenta (8.57), obtenemos:

.. math::

   \left( \frac{1}{T_I} - \frac{1}{T_{II}} \right) dU_I + \left( \frac{p_I}{T_I} - \frac{P_{II}}{T_{II}}\right) dV_I - \left( \frac{\mu_I}{T_I} - \frac{\mu_{II}}{T_{II}} \right) dn_I = 0

Por las mismas razones que antes expusimos :math:`dU_I`, :math:`dV_I` y :math:`dn_I` son variables independientes, por lo que:

.. math::

    \frac{1}{T_I} - \frac{1}{T_{II}} = 0\\
    \frac{p_I}{T_I} - \frac{P_{II}}{T_{II}} = 0 \\
    \frac{\mu_I}{T_I} - \frac{\mu_{II}}{T_{II}} = 0

de donde:

.. math::

   T_I = T_{II} \\
   p_I = p_{II} \\
   \mu_I = \mu_{II}
   
Es decir, para que una sustancia que se presenta en dos fases esté en equilibrio, es preciso que presión, temperatura y potencial químico sean iguales en ambas fases.

Procediendo de forma análoga llegaríamos a igual conclusión en un sistema muítifase.
