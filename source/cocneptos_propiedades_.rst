
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

* Sea :math:`x_1, ..., x_n` propiedades de un sistema que lo caracterizan (variables de estado).
* :math:`y=y(x_1, ..., x_n)`: "y" es una nueva propiedad (función de estado). Es una relación entre las propiedades anteriores.


Diremos que "y" es propiedad si y sólo si "y" es diferencial exacta. Esto es, cumple:

1. "y" es diferenciable:

.. math::

   dy = \sum \frac{\partial y }{\partial x_i} dx_i

2. "y" verifica Schwarz (igualdad de derivadas cruzadas):

.. math::

   \frac{\partial^2y}{\partial x_i \partial x_j} = \frac{\partial^2y}{\partial x_j \partial x_i}

Si no es propiedad
''''''''''''''''''

Si "y" no fuese una propiedad no cumpliría (1) y (2).



Para representar un cambio diferencial en una variable que no sea una propiedad se utilizará el símbolo :math:`\partial y`, que podrá expresarse:

.. math::

   \partial y = \sum z_i dx_i
   
donde :math:`z_i` y :math:`x_i` son variables de estado para las que:


.. math::

  \frac{\partial z_i}{\partial x_i} \neq \frac{\partial z_j}{\partial x_i} \Rightarrow \partial y \text{ no es diferencial exacta}
  
La integral de "y" dependerá de la trayectoria (integral de línea).

.. note::

   Observar que con :math:`dy` indicamos que "y" es propiedad, mientras que con :math:`\partial y` indicamos que "y" NO es propiedad.
   
   En el guión usaban :math:`\delta y` en lugar de :math:`\partial y`
