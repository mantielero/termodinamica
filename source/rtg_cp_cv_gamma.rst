Relaciones generalizadas para :math:`c_p, c_v \text{ y } \gamma`
----------------------------------------------------------------

En el apartado anterior hemos encontrado dos relaciones de las que pueden deducirse definiciones generalizadas para :math:`c_p` y :math:`c_v`, utilizables en cualquier región monofase en la que sean conocidos datos (s, p, v, T):

.. math::

   c_v = T \left( \frac{\partial s}{\partial T}\right)_v\\
   c_p = T \left( \frac{\partial s}{\partial T}\right)_p

Teniendo en cuenta que:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_v \left( \frac{\partial T}{\partial v}\right)_s \left( \frac{\partial v}{\partial s}\right)_T = -1\\
   \left( \frac{\partial s}{\partial T}\right)_p \left( \frac{\partial T}{\partial p}\right)_s \left( \frac{\partial p}{\partial s}\right)_T = -1

y las relaciones de Maxwell correspondientes, se obtiene:

.. math::

   c_v = -T \left( \frac{\partial v}{\partial T}\right)_s \left( \frac{\partial p}{\partial T}\right)_v\\
   c_p = T \left( \frac{\partial p}{\partial T}\right)_s \left( \frac{\partial v}{\partial T}\right)_p

Un método alternativo para la determinación de valores de :math:`c_p` y :math:`c_v` en un amplio intervalo de presiones y temperaturas está basado en el hecho experimental de que es fácil determinar calores específicos a presiones bajas y no lo es tanto a presiones elevadas. Ya se mencionó la posibilidad de utilizar los métodos espectroscópicos para la determinación de calores específicos de gases a baja presión y la variación de este calor específico con la temperatura. Tales datos se denominan calores específicos a presión cero.

Para hacer que estos datos sean aplicables en cualquier intervalo, no sólo de temperatura, sino también de presión, es preciso que podamos determinar como varían estos calores específicos con la presión a temperatura constante.

Esta evaluación deberá basarse nuevamente en la utilización de datos p, v, T, determinados en el intervalo adecuado de estados de equilibrio.

Desde el punto de vista matemático lo que buscamos es una expresión para :math:`\left( \frac{\partial c_p}{\partial p} \right)_T` y en casos menos frecuentes :math:`\left( \frac{\partial c_v}{\partial v} \right)_T`. Ecuaciones generalizadas para estas dos expresiones se obtienen a partir de las ecuaciones s(T, p) (6.43a) y s (T,v) (6.39) deducidas antes.

Nos centraremos en la primera, ya que la segunda tiene un tratamiento análogo, que se recomienda realizar al alumno.

Teniendo en cuenta (6.43) y aplicando a la misma la condición de diferencial exacta, se obtiene:

.. math::

   \left( \frac{\partial \left( \frac{c_p}{T}\right)}{\partial p} \right)_T = - \left( \frac{\partial ^2 v}{\partial T^2}\right)_p



de donde:

.. math::

   \left( \frac{\partial c_p}{\partial p} \right)_T = - T \left( \frac{\partial ^2 v}{\partial T^2}\right)_p

Para obtener el valor de :math:`c_p` a una presión elevada tendremos que integrar la ecuación anterior a lo largo de una isoterma desde la presión cero al valor deseado. Por lo que:

.. math::

   c_p-{c_p}_o = -T \int_0^p \left( \frac{\partial^2 v}{\partial T^2}\right)_p dp

En esta expresión :math:`{c_p}_o` es el calor específico a presión cero o calor específico de gas ideal. La integración del segundo miembro requiere que dispongamos de información del comportamiento *pvT* de la sustancia en forma analítica o tabular.

Diferencias :math:`c_p` - :math:`c_v`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Otra relación termodinámica de gran interés es la que da la diferencia de los calores específicos a presión constante y a volumen constante. Una razón que justifica este interés es, que como ya hemos dicho, los valores de :math:`c_p` son mucho más fáciles de medir que los de :math:`c_v`. De hecho, los valores de :math:`c_v` sólo pueden evaluarse de forma rigurosa a partir de datos de :math:`c_p` y :math:`pvT`.

Para realizar esta evaluación recordemos que la variación de cualquier propiedad termodinámica (variable de estado) no depende del método de evaluación (camino recorrido), por lo que podremos igualar las dos ecuaciones obtenidas para ds, ecuaciones (6.39) y (6.43), obteniendo:

.. math::

   \frac{c_v}{T}dT+ \left(\frac{\partial p}{\partial T}\right)_v dv = \frac{c_p}{T}dT - \left(\frac{\partial v}{\partial T}\right)_p dp

y de ésta se puede obtener:

.. math::

   \frac{c_p-c_v}{T}dT = \left(\frac{\partial v}{\partial T}\right)_p dp +  \left(\frac{\partial p}{\partial T}\right)_v dv

de donde:

.. math::

   dT = \frac{T}{c_p-c_v} \left[ \left(\frac{\partial v}{\partial T}\right)_p dp + \left(\frac{\partial p}{\partial T}\right)_v dv \right]


Es decir, hemos obtenido una expresión de T considerada como función de p y v. Para esta función debe cumplirse:


.. math::

   dT = \left(\frac{\partial T}{\partial p}\right)_v dp + \left(\frac{\partial T}{\partial v}\right)_p  dv

Identificando coeficiente homólogos, se obtiene:

.. math::

   \left(\frac{\partial T}{\partial p}\right)_v = \frac{T}{c_p-c_v} \left(\frac{\partial v}{\partial T}\right)_p


por lo que:

.. math::

   c_p-c_v = T \left(\frac{\partial p}{\partial T}\right)_v \left(\frac{\partial v}{\partial T}\right)_p


Se hubiese llegado al mismo resultado utilizando la equivalencia de los otros coeficientes.

Si utilizando la relación cíclica sustituimos :math:`\left(\frac{\partial p}{\partial T}\right)_v`:

.. math::

   \left(\frac{\partial p}{\partial T}\right)_v = - \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial p}{\partial v}\right)_T

en (6.55), llegamos a la expresión:

.. math::

   c_p-c_v = -T \left(\frac{\partial p}{\partial v}\right)_T \left(\frac{\partial v}{\partial T}\right)_p^2


De esta ecuación se pueden deducir inmediatamente un conjunto de resultados importantes.

Ante todo y sobre la base de datos experimentales, se sabe que :math:`\left(\frac{\partial p}{\partial v}\right)_T` es siempre negativa para todas las sustancias en todas las fases. Ya que la primera derivada parcial está elevada al cuadrado, se deduce que :math:`c_p-c_v` debe ser siempre positivo o cero.

Esta diferencia se hace cero en dos ocasiones. La primera de estas es, evidentemente, cuando T es el cero de la escala termodinámica, si los restantes términos permanecen finitos en este estado. Consecuentemente, los calores específicos a presión constante y a volumen constante a 0K son idénticos.

El segundo caso en el que se anula la diferencia :math:`c_p-c_v` es cuando se anula la derivada parcial :math:`\left(\frac{\partial v}{\partial T}\right)_p`. Esto ocurre cuando el fluido tiene un valor extremo del volumen específico (máximo o mínimo). Si consideramos como sistema el agua líquida, este caso se presenta en el entorno de 4 °C, por ser a esta temperatura su densidad máxima.

Es importante destacar que cuando se considera el estudio de hablar de calor específico y no se hace referencia a que el proceso considerado sea a presión o a volumen constante. Esto se debe a que los valores de :math:`\left(\frac{\partial v}{\partial T}\right)_p` son pequeños para la mayoría de los estados de equilibrio de las sustancias en estas fases. Generalmente los datos tabulados son valores de :math:`c_p`.

Es frecuente que encontremos expresada la diferencia de calores específicos para sólidos y líquidos en función del coeficiente de dilatación a y del coeficiente de compresibilidad isoterma :math:`k_T`, ya definidos. Sustituyendo en (6.56), se obtiene:

.. math::

   c_p - c_v = -T \frac{(\alpha v)^2}{-k_T v} = T \frac{\alpha^2 v}{k_T}

La utilización de :math:`\alpha` y :math:`k_T` resulta muy cómoda en la mayor parte de los cálculos que tienen que realizarse con estos sistemas, ya que sus valores pueden considerarse prácticamente constantes en casi todos los procesos considerados.

Expresión generalizada de :math:`\gamma`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para determinar :math:`\gamma` a partir de datos *pvT*, sustituyamos :math:`c_p` y :math:`c_v` por sus definiciones generalizadas:

.. math::

   \gamma = \frac{c_p}{c_v} = \frac{ T \left(\frac{\partial p}{\partial T}\right)_s \left(\frac{\partial v}{\partial T}\right)_p  }{ -T \left(\frac{\partial v}{\partial T}\right)_s \left(\frac{\partial p}{\partial T}\right)_v} = - \left(\frac{\partial p}{\partial v}\right)_s \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v


teniendo en cuenta que:

.. math::

   \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v \left(\frac{\partial p}{\partial v}\right)_T = -1\\
   \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v = - \left(\frac{\partial v}{\partial p}\right)_T

Sustituyendo en (6.58) y recordando que :math:`k_T= -\left(\frac{1}{v}\right)\left(\frac{\partial v}{\partial p}\right)_T` y :math:`k_s = -\left(\frac{1}{v}\right)\left(\frac{\partial v}{\partial p}\right)_s`, se obtiene:

.. math::

   \gamma = -\left(\frac{\partial p}{\partial v}\right)_s \left( -\frac{\partial v}{\partial p}\right)_T = \frac{\kappa_T}{\kappa_s}

Es decir, podemos relacionar el cociente de calores específicos con el cociente de las compresibilidades de la sustancia a temperatura y entropía constante.
