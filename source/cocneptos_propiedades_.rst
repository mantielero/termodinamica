
Describe your Changes
Commit

mantielero / termodinamica
Review your changes:
Additions are highlighted in green. Deletions are crossed out.

Propiedades
-----------

Llamamos **propiedades** (o *Propiedades termodinámicas de un sistema* o *variables termodinámicas* o *variables de estado*) a cualesquiera características macroscópicas observables. Por ejemplo: la masa, el volumen, la presión, la temperatura..., cuyos valores numéricos pueden asignarse en un momento dado sin tener en cuenta la historia del sistema. 


A veces se considera propiedad del sistema a cualquier relación entre las propiedades directamente observables del mismo (ej. producto de la presión y el volumen; producto de la presión y la temperatura, etc). Tales propiedades pueden considerarse *características indirectamente observables* de un sistema. 

Teóricamente pueden definirse un gran número de propiedades, pero como se verá, sólo unas pocas resultan útiles. 

Hay otro tipo de propiedades de un sistema que no son directamente observables y que se deducen de los principios de la termodinámica. En las lecciones correspondientes se verá cómo se introducen la energía interna, la entalpía, la entropía, etc., a partir de estos principios.

En el estudio de la termodinámica también se encuentran magnitudes que no son propiedades, porque sus valores dependen de la trayectoria seguida por el sistema, pudiendo citar entre ellas las transferencias de energía, como son el calor y el trabajo. No son propiedades ni el calor, ni el trabajo pues no es algo que sea propio del sistema, sino que se trata de transferencias energéticas.


Matemáticamente hablando
^^^^^^^^^^^^^^^^^^^^^^^^

Sean:

* Sea :math:`x_1, ..., x_n` propiedades de un sistema que lo caracterizan.
* :math:`y=y(x_1, ..., x_n)`: "y" es una nueva propidad (función de estado).


Diremos que "y" es propiedad si y sólo si "y" es diferencial exacta. Esto es, cumple:

1. "y" es diferenciable:

.. math::

   dy = \sum \frac{\partial y }{\partial x_i} dx_i

2. "y" verifica Schwarz:

.. math::

   \frac{\partial^2y}{\partial x_i \partial x_j} = \frac{\partial^2y}{\partial x_j \partial x_i}

Si no es propiedad
''''''''''''''''''

Si "y" no fuese una propiedad no cumpliría (1) y (2).

Cambio diferencial en una variable que no es una propiedad: 

.. math::

   \partial y = \sum z_i dx_i
   
donde :math:`z_i` y :math:`x_i` son variables de estado para las que:


.. math::

  \frac{\partial z_i}{\partial x_i} \neq \frac{\partial z_j}{\partial x_i} \Rightarrow \partial y \text{ no es diferencial exacta}
  
La integral de "y" dependerá de la trayectoria (integral de línea).

.. note::

   Observar que con :math:`dy` indicamos que "y" es propiedad, mientras que con :math:`\partial y` indicamos que "y" NO es propiedad.

Todo lo dicho anteriormente podría sintetizarse utilizando un lenguaje matemático de la forma siguiente.

Supóngase un conjunto de propiedades de un sistema:

.. math::

   x_1, x_2, ..., x_n

que pueden ser utilizadas para su caracterización. Desde este punto de vista, serían entonces variables de estado. Cualquier relación entre estas propiedades conduce a otra propiedad termodinámica que puede expresarse por la función:

.. math::

   y = y(x_1, x_2, ..., x_n)

siendo *y* la nueva propiedad, que por la forma de definirla se denomina función de estado.


Si esto es así, *y* es diferenciable:

.. math::

   dy = \sum_i \frac{\partial y}{\partial x_i} dx_i


y los coeficientes de esta expresión satisfacen la relación de las derivadas cruzadas (teorema de Schwarz):

.. math::

   \frac{\partial^2 y}{\partial x_j \partial x_i} = \frac{\partial^2 y}{\partial x_i \partial x_j}

es decir, *dy* es una diferencial exacta. Esta condición se utilizará con frecuencia posteriormente.

Si *y* no fuese una propiedad del sistema, es decir, su valor en cada punto dependiera de la trayectoria seguida para alcanzar ese punto, entonces las ecuaciones (1.1) y (1.2) no se cumplirían.

Para representar un cambio diferencial en una variable que no sea una propiedad se utilizará el símbolo :math:`\delta y`, que podrá expresarse:

.. math::

   \delta y = \sum z_i dx_i

donde :math:`z_i` y :math:`x_i` son variables de estado para las que:

.. math::

   \frac{\partial z_i}{\partial x_j} \neq \frac{\partial z_j}{\partial x_i}

por lo que :math:`\delta y` no es una diferencial exacta y su integral depende de la trayectoria (integral de línea).

Prose
