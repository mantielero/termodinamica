Propiedades, estados, procesos y equilibrio
===========================================

Introducción
------------

Para estudiar un determinado sistema lo primero que debe hacerse es proceder a su descripción y ello requiere el conocimiento de sus características propias, es decir, sus propiedades.

También la predicción de la evolución del mismo requiere el conocimiento de las propiedades del sistema y de cómo estas se relacionan.

.. toctree::
   :maxdepth: 1
   :caption: Contenido:
   
   conceptos_propiedades_
   conceptos_estado




Proceso
-------

Cuando cambia el estado del sistema diremos que éste ha experimentado un proceso.

Estado estacionario (equilibrio): secuencia de procesos experimentados por un sistema de forma que comienza y termina en el mismo estado.

Propiedad: una magnitud determinada es una propiedad, sí y solo si, la variación de su valor al pasar de un estado a otro es independiente del proceso seguido.

Como se ha dicho antes, en un estado dado cada propiedad tiene un valor definido que puede ser asignado sin saber cómo el sistema ha llegado a ese estado. Por lo tanto, el cambio en el valor de una propiedad, cuando el sistema es alterado para pasar de un estado a otro, se determina únicamente por los estados extremos y resulta independiente de la trayectoria particular seguida por el sistema en el cambio de estado. Es decir, el cambio es independiente de los detalles, o historia, del proceso. Recíprocamente, si la variación en el valor de una magnitud es independiente de la trayectoria del proceso entre dos estados, entonces aquella magnitud es una propiedad. Esto proporciona la prueba necesaria y suficiente para determinar si una magnitud es una propiedad: una magnitud determinada es una propiedad si, y solo si, la variación de su valor al pasar de un estado a otro es independiente del proceso seguido. Se sigue de esto que si el cambio en el valor de una magnitud depende de los detalles del proceso y no solamente de los estado extremos, la mencionada magnitud no es una propiedad termodinámica.

Propiedades extensivas, intensivas y específicas
''''''''''''''''''''''''''''''''''''''''''''''''

Las propiedades termodinámicas pueden dividirse en dos grandes grupos: propiedades extensivas y propiedades intensivas.

A una propiedad se le denomina extensiva si su valor para el sistema en conjunto es la suma del valor correspondiente a cada parte en las que el sistema puede dividirse. Entre ellas se pueden citar la masa y el volumen, así como muchas otras que se irán definiendo a lo largo del curso.

Las propiedades intensivas son aquellas que tienen el mismo valor para cualquier parte del sistema homogéneo que para el sistema en conjunto. La presión, temperatura y densidad son ejemplos de estas propiedades.

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
