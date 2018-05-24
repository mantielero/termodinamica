Aire húmedo: conceptos y definiciones
=====================================

El caso más importante de las mezclas gas-vapor es el aire húmedo. Los procesos en los que interviene el aire húmedo tienen una importancia suma en Meteorología, así como en acondicionamiento de aire y en procesos de secado. Así pues, en lo restante del tema nos vamos a dedicar al estudio de las propiedades de las mezclas gas-vapor aplicadas al aire húmedo. El aire húmedo es una mezcla de aire seco y agua. El aire seco es el "gas" y el vapor de agua el "vapor".

El intervalo de temperaturas que tiene importancia en las aplicaciones del aire húmedo va desde unos 233K (-40°C) hasta unos 323K (50°C). En los procesos de secado se llegan a alcanzar temperaturas más altas (100-300°C). La temperatura crítica del aire seco es 133K, muy por debajo de la zona de temperaturas de trabajo. Así pues, el aire seco se podrá considerar como gas ideal siempre que su presión parcial no sea superior a 10 ó 20 bar. Como, generalmente, en las apliaciones prácticas la presión del aire húmedo no suele diferir mucho de la presión atmosférica, :math:`p_a` alcanzará unos valores para los que está garantizado el modelo de gas ideal para el aire-seco.

La presión parcial del vapor de agua, por su parte, está limitada por su presión de saturación. Para una temperatura de 50°C p*(50°C) = 12.35kPa lo que nos indica que también para el vapor de agua es aplicable el modelo de gas ideal.

El punto triple del agua está a una temperatura de 0.01°C de manera que si la condensación del vapor de agua tiene lugar a una temperatura menor que ésta, se formará hielo o una niebla de hielo. La presión de saturación del agua, en este caso, será la correspondiente a la de sublimación a esa temperatura. Así pues, se pueden distinguir cuatro tipos de aire húmedo:

* *Aire húmedo no saturado* en el que :math:`p_v<p^*(T)`; contiene agua en estado de vapor
sobrecalentado.

* *Aire húmedo saturado* La presión de vapor es igual a la de saturación a la temperatura de la mezcla, :math:`p_v = p^*(T)`. Contiene agua en estado de vapor saturado.

* *Aire húmedo saturado con condensado líquido*. Contiene vapor de agua saturado y agua en forma de niebla o líquido precipitado.

* *Aire húmedo saturado con condensado sólido*. Además del vapor de agua saturado contiene hielo, generalmente en forma de niebla o escarcha.

El aire húmedo se considera, pues, como una mezcla ideal de gases ideales, de modo que la ecuación térmica de estado para la mezcla es:

.. math::

   p = \frac{m\left( \frac{R}{M}\right) T}{V} = \frac{nRT}{V}
   

donde:

- n: número de moles
- m: la masa
- M: masa molar de la mezcla. 

Se supone para la mezcla ideal el modelo de presiones aditivas (modelo de Dalton), de modo que

.. math::

   p = p_a + p_v

con

.. math::

   p_a = \frac{n_a RT}{V} = \frac{m_a R_a T}{V} \\
   p-v = \frac{n_v RT}{V} = \frac{m_v R_v T}{V}

siendo :math:`n_a` y :math:`n_v` la cantidad de sustancia de aire seco y de vapor de agua, respectivamente, expresada en moles y :math:`m_a`, :math:`m_v` las respectivas masas expresadas en *kg* si :math:`p_a` y :math:`p_v` van, ambas, en pascales, *Pa*. Las unidades de :math:`R_a` y :math:`R_v` habrá que elegirlas adecuadamente. En psicrometría se suele asignar al agua una masa molar igual a 18.015gramos y al aire seco 28.964gramos. Normalmente la cantidad de agua presente es mucho menor que la del aire seco por lo que :math:`n_v`, :math:`m_v` y :math:`p_v` son pequeños frente a :math:`n_a`, :math:`m_a` y :math:`p_a` respectivamente.

Humedad y humedad relativa
--------------------------

El contenido de vapor de agua de una muestra de aire húmedo puede expresarse dando lo que llamaremos humedad :math:`\omega` lo o dando la humedad relativa :math:`\phi`.

La humedad :math:`\omega`, también conocida como relación de humedad, se define como el cociente entre la masa de agua y la masa de aire seco presentes en la muestra; esto es

.. math::

   \omega = \frac{m_{\text{agua}}}{m_a}


Esta forma de expresar la humedad es preferible a la más clásica humedad absoluta, :math:`\frac{m_v}{V}` (masa de vapor por unidad de volumen de mezcla), por ser ésta última muy dependiente de las condiciones locales.

Considerando una muestra de aire húmedo no sobresaturado, en cuyo caso la masa de agua es la de vapor en la mezcla (:math:`m_{\text{agua}} = m_v`), la humedad puede expresarse en términos de las presiones parciales y de las masas molares sin más que despejar :math:`m_v` y :math:`m_a` de las expresiones (10.2) y sustituirlas en (10.3) obteniendo:

.. math::

   \omega = \frac{M_v p_v}{M_a p_a}

Introduciendo :math:`p_a = p — p_v` y teniendo en cuenta que el cociente de masas molares del agua y el aire es aproximadamente 0.622, la última expresión podremos escribirla en la forma:

.. math::

   \omega = 0.622 \frac{p_v}{p-p_v}

La masa de aire húmedo, *m*, puede expresarse en función de la masa de aire seco y de la humedad:

.. math::

   m = m_a(l+\omega)

Las fraciones molares de cada uno de los componentes pueden expresarse también en función de la humedad :math:`\omega`. En efecto:

.. math::

   x_a = \frac{   \frac{m_a}{M_a}}{\frac{m_a}{M_a} + \frac{m_v}{M_v}}

y teniendo en cuenta (10.3) y que :math:`\frac{M_v}{M_a} = 0.622 podemos reescribir la última expresión en la forma:

.. math::

   x_a = \frac{1}{1+\omega}

en la que se ha utilizado la denominada *humedad molar* :math:`\tilde{\omega} = \frac{n_v}{n_a} = \frac{\omega}{0.622}`

Como :math:`x_a+x_v = 1`

.. math::

   x_v = \frac{\tilde{\omega}}{1+\tilde{\omega}}`


También se puede dar el contenido de agua mediante la humedad relativa :math:`\phi` definida como el cociente entre la presión parcial del vapor de agua :math:`p_v` en una muestra dada de aire húmedo y la presión parcial :math:`p_{v,sat}` de la muestra de aire húmedo saturado ambas a la misma presión y temperatura; esto es:

.. math::

   \phi = \left. \frac{p_v}{p^*} \right|_{p,T}


Como :math:`p_v = x_v p` y :math:`p^* = x_{v,sat} p`, una forma alternativa de expresar la humedad relativa es:
 
.. math::

   \phi = \left. \frac{x_v}{x_{v,sat}} \right|_{p,T}


Temperatura de rocío
--------------------

Si el aire húmedo no está saturado y lo enfriamos a :math:`p_v` constante, la primera gota de condensado se formará cuando el aire húmedo alcance la temperatura de saturación, esto es, cuando :math:`p_v = p^*(T_R)`. A la temperatura a la que la presión parcial del vapor es su presión de saturación se la denomina *temperatura de rocío*.

Para calcular analíticamente la temperatura de rocío necesitamos conocer la dependencia funcional de :math:`p^*` con *T*. Una ecuación que se utiliza con frecuencia es de la forma:

.. math::

   \ln p^* = a - \frac{b}{T}

ecuación que se la suele llamar *ecuación de Clapeyron*. Antoine propuso una modificación a esta ecuación en la forma:

.. math::

   \ln p^* = a - \frac{b}{T+c}   


En lo que sigue utilizaremos la ecuación de Clapeyron, con a=13.765 y b=5121, ya que para los intervalos de presión y temperatura que se utilizan en los problemas técnicos de acondicionamiento de aire húmedo resulta una buena aproximación para la presión de vapor.

Así, como de (10.6) podemos poner :math:`p_v = \phi \cdot p^*(T)` y como la temperatura de rocío es aquella para la que :math:`p_v(T) = p*(T_R)`, se tendrá que:

.. math::

   p^*(T_R) = \phi \cdot p^*(T)

Tomando logaritmos en esta expresión y despejando Tr se obtiene:

.. math::

   p^*(T_R) = \frac{T}{1-\frac{T \ln \phi}{b}}


Si de lo que disponemos es de los valores tabulares de propiedades termodinámicas del agua en saturación, de (10.6) con :math:`\phi` y *T* del aire húmedo obtenemos :math:`p_v` y hay que localizar en las tablas la temperatura a la que la presión de saturación coincide con la :math:`p_v` calculada. Si es el diagrama *T-s* del agua de lo que disponemos, obtenida :math:`p_v` de (10.6) simplemente se mira cuál es la temperatura a la que la isóbara :math:`p_v` corta a la curva de vapor saturado y esa será la temperatura de rocío.
