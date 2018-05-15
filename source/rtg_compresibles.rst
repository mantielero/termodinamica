Relaciones generalizadas para cambios de entropía, energía interna y entalpia, de sustancias compresibles simples
-----------------------------------------------------------------------------------------------------------------

Para el análisis termodinàmico de sistemas es importante disponer de ecuaciones que permitan evaluar los cambios en estas magnitudes a partir de los correspondientes a los valores de las magnitudes que pueden medirse directamente. A continuación deduciremos alguna de estas ecuaciones.

Comencemos con los *cambios de entropía*. Por ser un sistema compresible simple, s podemos expresarla en función de T y v, T y p, ó p y v.

Consideremos el primer par de variables, T y v:

 .. math::

    ds = \left( \frac{\partial s}{\partial T}\right)_v dT +    \left( \frac{\partial s}{\partial v}\right)_T dv


Para conseguir el fin propuesto se deben sustituir las derivadas parciales dadas en función de expresiones que solo contengan p, v, T y los calores específicos. Para ello recordemos que:

.. math::

   Tds &= du +pdv\\
   ds &= \frac{1}{T}(du +pdv) \\
   du &=    \left( \frac{\partial u}{\partial T}\right)_v dT +    \left( \frac{\partial u}{\partial v}\right)_T dv = c_vdT +    \left( \frac{\partial u}{\partial v}\right)_T  dv\\
   ds &= \frac{c_v}{T}dT+    \left( \frac{\partial u}{\partial v}\right)_T dv = c_v dT +    \left( \frac{\partial u}{\partial v}\right)_T dv \\
   ds =  \frac{c_v}{T}dT+\frac{1}{T}\left[ p + \left(  \frac{\partial u}{\partial v}\right)_T \right]


Las ecuaciones (6.36) y (6.37) son expresiones equivalente para ds, por lo que:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_v = \frac{c_v}{T}

y

.. math::

   \left( \frac{\partial s}{\partial v} \right)_T  = \frac{1}{T} \left[ p + \left( \frac{\partial u}{\partial v}\right)_T \right]

De la tercera relación de Maxwell (6.34):

.. math::

   \left( \frac{\partial s}{\partial v}\right)_T  = \left(\frac{\partial p}{\partial T}\right)_v

Sustituyendo en (6.36) la primera de las (6.38) y la (6.34), se obtiene:


.. math::

   ds =  \frac{c_v}{T}dT+ \left(\frac{\partial p}{\partial T}\right)_v dv


Vemos que ds queda en función de magnitudes fáciles de determinar.

De (6.38) y (6.34) también se puede deducir:

.. math::

   \left(\frac{\partial p}{\partial T}\right)_v  = \frac{1}{T} \left[ p + \left(\frac{\partial u}{\partial v}\right)_T \right]

de la podemos obtener :math:`\left( \frac{\partial u}{\partial v} \right)` en función de cualquier ecuación *pvT*, relación que se necesitará utilizar más adelante.

De forma análoga para la expresión en función de *p* y *T* tenemos:

.. math::

   ds = \left( \frac{\partial s}{\partial T}\right)_p dT + \left( \frac{\partial s}{\partial p}\right)_T dp

A partir de:

.. math::

   dh &= Tds + vdp\\
   ds &= \frac{1}{T}(dh -vdp)

y

.. math::

   dh = \left( \frac{\partial h}{\partial T}\right)_p dT + \left( \frac{\partial h}{\partial p}\right)_T  dp = c_p dT + \left( \frac{\partial h}{\partial p}\right)_T  dp

se obtiene:

.. math::

   ds = \frac{c_p}{T}dT + \frac{1}{T} \left[ \left( \frac{\partial h}{\partial p}\right)_T -v\right]dp

Las expresiones (6.40) y (6.41) representan la misma función, por lo que identificando términos equivalentes, se llega a la relación:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_p = \frac{c_p}{T}

De la cuarta relación de Maxwell, ecuación (6.35), se tiene:

.. math::

   \left( \frac{\partial s}{\partial p}\right)_T  = - \left( \frac{\partial v}{\partial T}\right)_p

Algo semejante se puede hacer con la expresión de s en función de p y v. Es conveniente que el alumno realice la deducción completa de esta ecuación y compruebe que se llega a:

.. math::

   ds = \frac{c_v}{T} \left( \frac{\partial T}{\partial p}\right)_v dp + \frac{c_p}{T} \left( \frac{\partial T}{\partial v}\right)_p dv

La metodología utilizada en la deducción de las correspondientes expresiones para las funciones u y h es análoga a la utilizada hasta ahora.

Para obtener la correspondiente a los cambios de energía intema, recordemos que:

.. math::

   du = T ds - p dv

Sustituyendo ds por la expresión (6.39), se obtiene:


.. math::

   du = c_v dT + \left[ T \left( \frac{\partial p}{\partial T}\right)_v -p\right] dv

De la expresión :math:`dh = T ds + v dp`, sustituyendo en ella ds de la primera ecuación (6.43a), se obtiene:

.. math::

   dh = c_p dT + \left[ v-T \left( \frac{\partial v}{\partial T}\right)_p \right] dp

Tanto la expresión de du como la de dh permiten encontrar el valor de :math:`\Delta u` e :math:`\Delta h` para un determinado proceso, sin más que conocer las correspondientes relaciones :math:`c_p(T)`  y :math:`f(p,v,T) = 0`, mediante la integración entre los estados inicial y final correspondientes.

En algunos textos es frecuente dar estas expresiones utilizando :math:`\alpha` y :math:`k_T`, para ello, recuérdese que:

.. math::

   \left( \frac{\partial p}{\partial T}\right)_v = - \frac{  \left( \frac{\partial v}{\partial T}\right)_p  } {\left( \frac{\partial v}{\partial p}\right)_T } = \frac{\alpha v}{k_T v} = \frac{v}{v}

por lo que:

.. math::

   du = c_v dT + \left[ T\frac{\alpha}{k_T} - p\right]dv\\
   dh = c_p dT + [v-T\alpha v] dp = c_p dT + [1-\alpha T]v dp

Como aplicación inmediata de lo que acabamos de ver consideremos el ejercicio siguiente:

:doc:`Ejercicio E6.2 <rpg_E6.2>`

