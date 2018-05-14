Teorema de Clausius
===================

Desde un punto de vista histórico, el proceso seguido para introducir el concepto de entropía incluye, como paso fundamental, la demostración del **teorema de Clausius**, también conocido como **desigualdad de Clausius**. Esta nos dice que la relación existente entre las cantidades de calor :math:`Q_i` que intercambian diversas fuentes a temperaturas :math:`T_i` con un sistema determinado en un proceso cíclico o estacionario cumple la desigualdad:

.. math::

   \sum\frac{Q_i}{T_i} \leq 0

Si las cantidades de calor son diferenciales y el proceso es cíclico:

.. math::

    \displaystyle\oint\frac{\delta Q}{T} \leq 0

Demostración
------------

Para demostrar esta desigualdad consideremos el sistema esquematizado en la figura 3.7a
en la que diversas fuentes térmicas, a temperaturas :math:`T_1, T_2,...T_i...T_n`, intercambian calor con un sistema y éste produce un trabajo :math:`W_a` sin que haya incremento de su energía total.

.. figure:: img/2nd_principio_clausius_a.png
   :width: 40%
   :align: center

   Demostración de la desigualdad de Clausius.


.. figure:: img/2nd_principio_clausius_b.png
   :width: 40%
   :align: center

   Demostración de la desigualdad de Clausius.

El conjunto de la figura 3.9a podríamos sustituirlo por otro equivalente, es decir que el sistema intercambie el mismo calor y realice el mismo trabajo, de forma que únicamente hubiese intercambio de calor con una sola fuente térmica, que podría ser el ambiente, a una temperatura :math:`T_o > T_i` (para todo i) según se esquematiza en la figura 3.9b. Es decir, mediante suficientes máquinas de Carnot que funcionan en ciclos elementales infinitesimales, si son infinitas, con intercambios :math:`\delta Q_{oi}`, :math:`\delta Q_{ci}` y :math:`\delta W_{ci}^{(*)}`. Cada una de las fuentes térmicas intercambia calor con la fuente a :math:`T_0`, mediante las máquinas térmicas mencionadas, de forma que recuperan el calor que ceden al sistema por lo que, desde el punto de vista del proceso considerado, no experimentan ninguna alteración, es decir :math:`\delta Q_{ci}+\delta Q_i = 0`.

Haciendo el balance de energía a cada una de la máquinas elementales de Carnot tendremos:

.. math::

   \delta Q_{oi} = \delta Q_{ci}+\delta Q_{ci}

A partir del segundo de los teoremas de Carnot podemos escribir, para cada una de las máquinas elementales:

.. math::

   \frac{\delta Q_{oi}}{T_o} = \frac{\delta Q_{ci}}{T_i} \rightarrow \frac{\delta W_{ci}+\delta Q_{ci}}{T_o} = \frac{\delta Q_{ci}}{T_i}

Aplicando el primer principio a la fuente térmica :math:`T_i`, recuérdese la condición impuesta a las fuentes, tendremos:

.. math::

   \delta Q_{ci}+\delta Q_i = 0 \rightarrow \delta Q_{ci} = -\delta Q_i

.. note::

   (*) Si el número de fuentes es finita los intercambios serán :math:`Q_{oi}`, :math:`Q_{ci}` y :math:`W_{ci}`.


y sustituyendo en (3.10), se obtiene:

.. math::

   \frac{\delta W_{ci} - \delta Q_i}{T_o} = -\frac{\delta Q_i}{T_i}

de donde:

.. math::

   \delta W_{ci} = \left( 1 - \frac{T_o}{T_i} \right) \delta Q_i


Para todos los ciclos:

.. math::

   \sum_{i=1}^n \oint \delta W_{ci}  = \sum_{i=1}^n \oint \left( 1 - \frac{T_0}{T_1}\right) \delta Q_i


Durante el mismo ciclo, en el sistema se verificará:

.. math::

   \oint \delta W_s + \oint \delta Q_i = 0

De (3.11) y (3.12) se obtiene:

.. math::

   \sum_{i=1}^n \oint \delta W_{ci}+\oint\delta W_s = -\sum_{i=1}^n \oint \frac{T_o}{T_i}\delta Q_i

y esta última igualdad puede ser positiva o nula ya que sólo es posible, actuando con una sola fuente térmica, que el sistema reciba tranbajo. Así pues, como :math:`\sum_{i=1}^n \oint \delta W_{ci}+\oint \delta W_s \geq 0`, se cumplirá que:

.. math::

   \oint\frac{\delta Q_i}{T_i} \leq 0

Si en vez de considerar un conjunto de cicles infinitesimales, se consideran intercambios finitos se obtendría:

.. math::

   \sum \frac{Q_i}{T_i} \leq 0


en donde :math:`Q_i` indica calor intercambiado por cada fuente con el sistema y considerado desde el punto de vista del sistema.

Si invertimos el ciclo :math:`Q_i` cambiará de signo (al cambiar de sentido) por lo que el signo igual (=) es para procesos reversibles y el signo menor que (<) para procesos irreversibles.


.. toctree::
   :maxdepth: 1
   :caption: Ejemplos:
   
   segundo_principio_clausius_ejemplo