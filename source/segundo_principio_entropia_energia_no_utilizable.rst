Entropía y energía no utilizable
================================

Consideremos un sistema que evoluciona de forma irreversible en contacto con su ambiente cuya temperatura es :math:`T_a`. El primer principio aplicado al sistema nos dice que

.. math::


   Q+W= \Delta E


siendo Q el calor que el sistema recibe. La variación de entropía del ambiente considerado éste como una fuente térmica, vendrá dada por:

.. math::

   \Delta S_a = -\frac{Q}{T_a}

Imaginemos ahora un proceso reversible que devuelva el sistema, a sus condiciones iniciales. Aplicando nuevamente el primer principio obtendremos

.. math::

   Q_R + W_R = \Delta E_R

donde el subíndice R indica reversibilidad.

La variación de entropía del ambiente asociada al proceso reversible será:

.. math::

   \Delta S_{a_R} = -\frac{Q_R}{T_a}

Para el ciclo completo tendremos que :math:`\Delta E + \Delta E_R = 0` con lo que

.. math::

   Q+Q_R = -(W-W_R)

Como el sistema ha vuelto a sus condiciones iniciales su entropía no habrá experimentado variación alguna, por lo que el cambio de entropía del sistema compuesto por el sistema original más el ambiente vendrá dado, de acuerdo con (3.19) por

.. math::

   \Delta S_{univ} &= - \left( \frac{Q+Q_R}{T_a} \right)\\
   &= \left( \frac{W+W_R}{T_a}\right)\\
   &= \sigma_t


de donde

.. math::

   W+W_R = T_a \sigma_t

La cantidad :math:`(W + W_R)` representa el trabajo que ha sido necesario hacer para devolver el sistema a su estado original. Si el primer proceso hubiera sido reversible esta cantidad sería nula. En conclusión :math:`(W + W_R)` es la energía que no ha podido ser aprovechada en forma de trabajo útil durante el proceso irreversible que va ligada a la producción de entropía del proceso.

Al producto :math:`T_a \sigma` se le denomina **irreversibilidad** y nos indica que cuanto mayor sea ésta, tanto mayor será la cantidad de energía no utilizable en forma de trabajo útil. De todo esto se hablará con más extensión en el tema 5.
