Propiedades
===========

Llamamos **propiedades** (o *Propiedades termodinámicas de un sistema* o *variables termodinámicas* o *variables de estado*) a cualesquiera características macroscópicas observables. Por ejemplo: la masa, el volumen, la presión, la temperatura..., cuyos valores numéricos pueden asignarse en un momento dado sin tener en cuenta la historia del sistema. 


A veces se considera propiedad del sistema a cualquier relación entre las propiedades directamente observables del mismo (ej. producto de la presión y el volumen; producto de la presión y la temperatura, etc). Tales propiedades pueden considerarse *características indirectamente observables* de un sistema. 

Teóricamente pueden definirse un gran número de propiedades, pero como se verá, sólo unas pocas resultan útiles. 

Hay otro tipo de propiedades de un sistema que no son directamente observables y que se deducen de los principios de la termodinámica. En las lecciones correspondientes se verá cómo se introducen la energía interna, la entalpía, la entropía, etc., a partir de estos principios.

En el estudio de la termodinámica también se encuentran magnitudes que no son propiedades, porque sus valores dependen de la trayectoria seguida por el sistema, pudiendo citar entre ellas las transferencias de energía, como son el calor y el trabajo. No son propiedades ni el calor, ni el trabajo pues no es algo que sea propio del sistema, sino que se trata de transferencias energéticas.


Matemáticamente hablando
------------------------

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
^^^^^^^^^^^^^^^^^^

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

Propiedades extensivas, intensivas y específicas
------------------------------------------------

Las propiedades termodinámicas pueden dividirse en dos grandes grupos:

* **Propiedad extensiva**: si su valor para el sistema en conjunto es la suma del valor correspondiente a cada parte en las que el sistema puede dividirse. Entre ellas se pueden citar la masa y el volumen, así como muchas otras que irán apareciendo.
* **Propiedades intensivas**: son aquellas que tienen el mismo valor para cualquier parte del sistema homogéneo que para el sistema en conjunto. La presión, temperatura y densidad son ejemplos de estas propiedades.

Si el valor de una propiedad extensiva se divide entre la masa del sistema, la propiedad resultante es una propiedad intensiva y se denomina propiedad específica. Por ejemplo, el volumen específico se obtiene dividiendo el volumen total del sistema (propiedad extensiva) entre la masa del mismo. Esta relación del volumen a la masa es la misma para cualquier punto de un sistema homogéneo y por tanto es una magnitud intensiva. Para designar una propiedad intensiva se utilizarán letras minúsculas y las propiedades extensivas se designarán mediante letras mayúsculas. Las propiedades específicas se representarán, por tanto, con letras minúsculas. Como excepción, la temperatura termodinámica del sistema se representará con mayúscula y la masa del sistema se suele representar mediante *m* minúscula.

Matemáticamente, se puede formular todo lo dicho recurriendo al concepto de función homogénea. Como se recordará o puede verse en cualquier libro de análisis matemático, una función *Y* se denomina homogénea de grado :math:`\alpha` cuando se verifica:

.. math::

   Y(\lambda X_1, \lambda X_2, ..., \lambda X_n) = \lambda^\alpha Y(X_1, X_2, ..., X_n)

en la que las :math:`X_i` son propiedades extensivas del sistema.

Para estas funciones se cumple el teorema de Euler:

.. math::

   \sum X_i \frac{\partial Y}{\partial X_i} = \alpha Y

También se verifica que si una función es homogénea de grado :math:`\alpha`  su derivada de orden *p* es homogénea de grado :math:`\alpha -p`. En esta expresión *p* es un entero positivo, pero :math:`\alpha` no necesita ser un entero mayor que *p*.

Según lo que acaba de verse, si *Y* es una propiedad de un sistema simple que contiene *n* moles de sustancia, *Y* será intensiva o extensiva según sea proporcional a :math:`n^0` o a :math:`n^1`, respectivamente:

.. math::

   Y \approx n^0 (\alpha = 0), intensiva\\
   y \approx n^1 (\alpha = 1), extensiva

Así, el volumen total *V* es extensiva, ya que si se duplica el número de moles del sistema, conservando constantes todos los parámetros intensivos, el volumen se duplica. Por otro lado, el volumen total dividido entre el número de moles del sistema proporciona el volumen específico molar (:math:`v = \frac{V}{n}`) que es una variable intensiva.

Conviene tener claro que cualquier propiedad extensiva *Y* tiene una variable intensiva correspondiente :math:`\frac{Y}{n}`, pero la inversa no es siempre cierta ya que variables como *T* y *p* no poseen sus correspondientes extensivas.

Para aclarar lo expuesto, supóngase que *Y* es una propiedad extensiva dependiente de otras propiedades extensivas :math:`X_i`. El requisito de que *Y* sea una propiedad extensiva significa que si se duplican las :math:`X_i`, se duplica *Y*, es decir:

.. math::

   Y( 2X_1, 2X_2, ..., 2X_n) = 2 Y(X_1, ..., X_n)

y en general:

.. math::

   Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = \lambda Y(X_1, ..., X_n)

en otras palabras, *Y* es homogénea de grado uno.

Considerando que *Y* sea una propiedad intensiva, al duplicar las *X* se deja sin alterar la *Y*, o en general:

.. math::

   Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = Y(X_1, ..., X_n)


por lo que *Y* es homogénea de grado cero.

Resumiendo, si *Y* es una propiedad que depende de variables extensivas :math:`X_i`, resultará que *Y* será una propiedad extensiva si es homogénea de grado uno, y será intensiva si es homogénea de grado cero. Según se vió antes al considerar la derivada de orden *p* de una función homogénea, si *Y* es extensiva, la primera derivada respecto a una variable extensiva será una propiedad intensiva.

A lo largo del curso se utilizará con frecuencia el criterio de homogeneidad.
