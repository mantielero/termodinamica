Propiedades termodinámicas del aire húmedo
==========================================

Al estudiar procesos que involucren al aire húmedo y tener que aplicar tanto el primer principio como el segundo bien a sistemas abiertos bien a sistemas cerrados, nos encontramos con que hay que evaluar variaciones tanto de energía interna como de entalpia y/o entropía. Por ello en esta sección vamos a ver cómo se pueden evaluar estas propiedades termodinámicas además de dar la expresión de la densidad del aire húmedo. En general, todas estas propiedades se dan por unidad de masa de aire seco que es el componente de la mezcla que se mantiene constante en, prácticamente, todos los procesos. Al final de la sección se dirá cómo se pasa de la unidad de aire seco a la unidad de mezcla.


Densidad del aire húmedo
------------------------


La densidad del aire húmedo depende de la temperatura *T*, de la presión *p* y de la humedad :math:`\omega`. De la definición de densidad tenemos que:

.. math::

   \rho = \frac{m_a+m_v}{V}
   

Si sustituimos en (10.9) el valor de *V* obtenido de las ecuaciones (10.2), :math:`V = \frac{(m_a R_a + m_v R_v)T}{p}`, se obtiene:

.. math::
 
   \rho = \frac{m_a + m_v}{m_a R_a + m_v R_v} \frac{p}{T}


y de la definición de humedad (ec. 10.3) podremos escribir:

.. math::
 
   \rho = \frac{1 + \omega}{1 + \tilde{\omega}} \frac{p}{R_a T}

Como :math:`(1 + \omega)` es siempre menor que :math:`(1 + \tilde{\omega})`, al aumentar la humedad del aire disminuye la densidad del mismo.

En vez de la densidad, a menudo se trabaja con su inversa el volumen específico del aire húmedo. Cuando se maneja esta propiedad suele usarse como magnitud de referencia la cantidad de aire seco :math:`m_a`. Por definición, el volumen específico con referencia a la cantidad de aire seco, es:

.. math::

   v_a = \frac{\text{volumen de aire húmedo}}{\text{masa de aire seco}} = \frac{V}{m_a} = (1+\tilde{\omega}) \frac{R_a T}{p}

El volumen específico así definido difiere de la definición corriente, en la que la magnitud
de referencia es la masa de la mezcla:

.. math::

   v_a = \frac{\text{volumen de aire húmedo}}{\text{masa de aire húmedo}} = \frac{V}{m_a+m_v}


Entre :math:`v_a` y *v* existe la relación:

.. math::

  v_a = (l + \omega)v
  

siendo  :math:`(1 + \omega)` la relación  :math:`\frac{\text{masa de aire húmedo}}{\text{masa de aire seco}}`. Evidentemente entre :math:`\rho` y :math:`v_a` existe la relación:

.. math::
   
   v_a = \frac{(1 + \omega)}{\rho}


Entalpia, energía interna y entropía del aire húmedo
----------------------------------------------------

De manera análoga al volumen específico, cuando se utilizan valores específicos de estas propiedades termodinámicas se hace por unidad de aire seco y no por unidad de masa de mezcla.

El estado de referencia elegido para poder evaluar estas propiedades, mejor dicho sus variaciones, es un estado de equilibrio termomecánico, pero no de equilibrio químico. Es un estado en el que la temperatura :math:`\theta_{ref} = 0.01°C` y :math:`p_{ref} = 100 kPa` el aire seco y el agua líquida están separados y para los cuales :math:`h_a(\theta_{ref}) = 0`, :math:`h_l(\theta_{ref},p_{ref}) = 0`, :math:`s_a(\theta_{ref},p_{ref}) = 0` y :math:`s_l(\theta_{ref}) = 0` (Hay que hacer notar que al dar estos valores se está suponiendo comportamiento perfecto para el gas y para el líquido).

De acuerdo con (9.65), la entalpia del aire húmedo podemos expresarla como:

.. math::

   H = n_a \overline{h_a} + n_v \overline{h_v}

que, por unidad de sustancia de aire seco, toma la forma:

.. math::

   \overline{h} = \overline{h_a} + \tilde{\omega} \overline{h_v}

en la que :math:`\overline{h_a}` y :math:`\overline{h_v}` son, respectivamente, las entalpias molares del aire seco y del vapor a la temperatura de la mezcla. Teniendo en cuenta que :math:`\frac{n_a}{n_v} = \tilde{\omega}` y que :math:`\frac{M_v}{M_a}= 0.622`, al pasar a valores específicos por unidad de masa de aire seco se obtiene:

.. math::
 
   h = h_a + \omega h_v

En (10.15.b) la entalpia del aire húmedo, *h*, viene expresada por unidad de aire seco.

Con el estado de referencia mencionado anteriormente y en la consideración de comportamiento de gas perfecto (aire y vapor de agua) y de líquido incompresible (agua líquida), la entalpia del aire húmedo (ecuación (10.15)) que está a una temperatura *T(K)* y a una presión *p (kPa)* se expresa en la forma:

.. math::

   h = c_{p_a} \theta + \omega \left( \frac{p^*\left(\theta_{ref}\right) -p_{ref}}{\rho_l} +h_{lv}(0.01°C) + c_{p-v} \theta \right)



En la expresión anterior el término :math:`\frac{p^*\left(\theta_{ref}\right) -p_{ref}}{\rho_l}` es despreciable (su valor es :math:`0.099\frac{kJ}{kg}`) frente a cualquiera de los otros dos términos ( :math:`h_{lv}(\theta_{ref}=2501.4\frac{ kJ}{kg}` y :math:`c_{p_v} \theta  = 1.82 \frac{kJ}{kg}` si :math:`\theta = 1°C`), por lo que para el aire húmedo no saturado y saturado puede ponerse:

.. math::

   h = c_{p-a} \theta + \omega \left[ h_{lv}(\theta_{ref}) + c_{p_v}\theta \right]

Para el aire húmedo sobresaturado, distinguiremos dos casos según que :math:`\theta` sea mayor o menor que :math:`0.01°C`; esto es, según que el condensado sea líquido o sólido.

Para el primer caso (:math:`\theta > 0.01°C`):

.. math::

   h = h_a + \omega_{sat} h_g + (\omega - \omega_{sat})h_l


donde :math:`h_l` es la entalpia del líquido a la temperatura y presión (*T*, *p*) del aire húmedo saturado y :math:`h_g` es la entalpía del vapor saturado a la temperatura (*T*); esto es, la expresión que nos da el valor de esta entalpia, teniendo en cuenta el estado de referencia elegido, es:

.. math::

   h_l = c_l \theta + \frac{p-p_{ref}}{\rho_l}

y si despreciamos el término de la presión en la evaluación de la entalpia del líquido nos quedará:


.. math::

   h = c_{p-a}\theta + \omega_{sat} \left[ h_{lv}(\theta_{ref}) + c_{p_v}\theta \right] + (\omega - \omega_{sat})c_l \theta

Y para el segundo caso (:math:`\theta < 0.01°C`)

.. math::

   h = h_a + \omega_{sat} h_g + (\omega-\omega_{sat}) h_s

siendo :math:`h-s` la entalpia del condensado sólido a la temperatura y presión (*T*, *p*) del aire húmedo saturado y que podemos evaluarla con:

.. math::

   h_s = \frac{p^*(\theta_{ref}) - p_{ref}}{\rho_l} + h_{ls}(\theta_{ref}) + c_s \theta + \frac{p-p^*(\theta_{ref})}{\rho_s} 

Y si, como hemos hecho hasta ahora, también en este caso despreciamos la contribución de la presión a la entalpia del sólido nos quedará finalmente:

.. math::

   h = c_{p-a}\theta + \omega_{sat}\left[ h_{lv}(\theta_{ref}) + c_{p_v}\theta \right] +  (\omega-\omega_{sat}) \left[ h_{ls}(\theta_{ref}) + c_s \theta \right]

Los valores numéricos de los calores específicos, dado el intervalo de temperaturas utilizado en los problemas de aire húmedo, y los de las entalpias de cambio de fase son:

.. math::

   c_{p_a} = 1.005 \frac{kJ}{kg \cdot K} \\
   c_{p_v} = 1.82 \frac{kJ}{kg \cdot K} \\
   c_{l} = 4.18 \frac{kJ}{kg \cdot K} \\
   c_{s} = 2.05 \frac{kJ}{kg \cdot K} \\
   h_{lv}(\theta_{ref}) = 2501.4 \frac{kJ}{kg} \\
   h_{ls}(\theta_{ref}) = -333.4 \frac{kJ}{kg} \\   
   

El término (:math:`\omega-\omega_{sat}`) que aparece en las ecuaciones anteriores representa, respectivamente, la cantidad de condensado líquido y sólido existente en la mezcla.

Vamos a evaluar, ahora, la energía interna de una muestra de aire húmedo. Con el estado
de referencia elegido, :math:`u_{ref}` no es nulo, sino que vale :math:`u_{ref} = u_{a_{ref}} + \omega u_{v_{ref}}` siendo :math:`u_{a_{ref}} = -p_{ref} v_{a_{ref}} = R_a T_{ref}` y :math:`u_{v_{ref}} = - \frac{p_{ref}}{\rho_l}` ya que, por definición, :math:`h_{ref} = u_{ref} + (pv)_{ref} = 0`. Con
esto la expresión de la energía interna será:

.. math::

   u = u_a + \omega u_v = h_a - R_a T + \omega (h_v-R_v T)

Una forma alternativa, y quizás más sencilla, de evaluar la energía interna del aire húmedo es partiendo de :math:`u = h — pv por la que:

.. math::

   u = u_a + \omega u-v = h_a - R_a T + \omega (h_v-R_v T)
   
que puede reagruparse para escribir:

.. math::

   u = h_a +\omega h-v - R_a ( 1 +\tilde{\omega}) T \\
   = c_{p_a}\theta + \omega \left[ h_{lv}(\theta_{ref}) + c_{p_v}\theta \right] - R_a (1 +\tilde{\omega}) T

Puede verse fácilmente que ambas expresiones, (10.24) y (10.25), coinciden.

Cuando el aire húmedo está sobresaturado las expresiones de la energía interna del mismo
son:

* si :math:`\theta > 0.01°C`:

.. math::

   u = h_a + \omega_{sat} h_g - R_a (1 +\tilde{\omega}_{sat}) T + (\omega-\omega_{sat}) \left[ h_f(T) - \frac{p^*(T)}{\rho_l} \right]
   
* si :math:`\theta < 0.01°C`:

.. math::

   u = h_a + \omega_{sat} h_g - R_a (1 +\tilde{\omega}_{sat}) T + (\omega-\omega_{sat}) \left[ h_s(T) - \frac{p^*(T)}{\rho_s} \right]   
   
La entalpia del líquido saturado :math:`h_f(T)` se calcula de (10.19) sin más que poner las condiciones de saturación y de manera análoga, a partir de (10.22) se obtiene la entalpia para el condensado sólido (hielo) :math:`h_s(T)`.

Para evaluar la entropía de una muestra de aire húmedo utilizaremos la expresión :math:`S=\sum_{i=1}^k n_i s_i(T,p_i)`. Así pues, para el aire húmedo, y por unidad de masa de aire seco, teniendo en ¿=i
cuenta el estado de referencia se tendrá:

.. math::

   s = s_a +\omega s_v

con

.. math::

   s_a = c_{p_a} \ln \frac{T}{T_{ref}} - R_a \ln \frac{p_a}{p_ref}
   
y

.. math::

   s_v = \frac{h_{lv}(T_{ref})}{T_{ref}} + c_{p_v} \ln \frac{T}{T_{ref}} - R_v \ln \frac{p_v}{p^*(T_{ref}}

Esta última expresión puede ponerse, sin más que sumar y restar :math:`R_v \ln p^*(T)` y teniendo en cuenta (10.7), en la forma:

.. math::

   s_v &= \frac{h_{lv}(T_{ref})}{T_{ref}} + c_{p_v} \ln \frac{T}{T_{ref}} - R_v \ln \frac{p^*(T)}{p^*(T_{ref})} - R_v\ln \phi \\
   &= s_g(T) - R_v \ln \phi

Así, pues, podremos escribir para la entropía del aire húmedo:

.. math::

   s = c_{p_a} \ln \frac{T}{T_{ref}} - R_a \ln \frac{p_a}{p_{ref}} + \omega \left[ \frac{h_{lv}(T_{ref})}{T_{ref}} + c_{p_v} \ln \frac{T}{T_{ref}} - R_v \ln \frac{p^*(T)}{p^*(T_{ref})} - R_v\ln \phi \right]

Si el aire húmedo está sobresaturado las expresiones de la entropía para ese aire serán: 

Si :math:`\theta  > 0.01°C`

.. math::

   s = s_a + \omega_{sat} s_g + (\omega - \omega_{sat}) s_l

donde :math:`s_a` viene dado por (10.28.a), :math:`s_g` se obtiene de (10.28.c) haciendo :math:`\phi = 1` y :math:`s_l` es:

.. math::

   s_l = c_l \ln \frac{T}{T_{ref}} = s_f(T)

Si :math:`\theta  < 0.01°C`

.. math::

   s = s_a + \omega_{sat} s_g +  (\omega - \omega_{sat}) s_s

:math:`s_a`, en este caso, también viene dada por (10.28.a) y :math:`s_g` es la misma que en el caso anterior. La expresión de :math:`s_s` es:

.. math::

   s_s = \frac{h_{ls}}{T_{ref}} + c_s \ln \frac{T}{T_{ref}}
   

_Aire húmedo en equilibrio con agua líquida_

Habrá ocasiones en las que el aire húmedo se encuentre en equilibrio con agua líquida, y para esos casos conviene analizar la influencia que sobre la presión de saturación del agua tiene la presencia del aire seco.

Partimos del hecho de que el aire seco no está, prácticamente, disuelto en el agua líquida(*); esto es, podemos considerar el agua líquida, en presencia de aire húmedo saturado, como una sustancia pura. Como hay equilibrio entre el agua en fase líquida y fase vapor se debe verificar que:

.. math::

   \mu_l(T,p) = \mu_v(T, p_{v,sat})
   

y como ya vimos en el tema anterior, para un sistema monocomponente :math:`\mu = h — Ts`, luego tendremos para el agua líquida y para el agua vapor los valores:

.. note::

   (*) De la ley de Henry se obtiene que las fracciones molares de Oí y Ni disueltas en el agua liquida son %o2 — 4.76 • 10-6 y xjv2 = 9.14 • 10~6, lo cual supone que hay 8,5 gramos de Oí y 14,1 gramos de Ni disueltos en 1 m3 de agua. Estas cantidades son lo suficientemente pequeñas como para poder considerar el agua como una sustancia pura


.. math::

   \mu_l &= h_l - T s_l \\
   &= h_f(T) + \frac{p-p^*(T)}{\rho_l} - T s_f(T)
   
.. math::
   
   \mu_v = h_v-T s_v(T,p_{v,sat}) \\
    = h_g(T) - T \left[ s_g(T) - R_v \ln \frac{p_{v,sat}}{p^*}\right] 
    
En la que :math:`p^*` es la presión de saturación del agua como sustancia pura. Y como :math:`h_g(T) — h_f(T) = T\left[s_g(T) — s_f(T)\right]`, la condición de igualdad de los potenciales químicos implica:

.. math::

   \frac{p- p^*(T)}{\rho_l} = R_v T \ln \frac{p_{v,sat}}{p^*}


esto es:

.. math::

   \frac{p_{v,sat}}{p^*} = \exp{ \frac{p- p^*(T)}{R_v T \rho_l} } \approx 1 + \frac{p- p^*(T)}{R_v T \rho_l} 
   
si :math:`\frac{p- p^*(T)}{R_v T \rho_l} \ll 1`, cosa que sucede si, en el intervalo de temperaturas normales de trabajo, :math:`p \ll 140MPa`. Y si ponemos que :math:`p_{v,sat} = p^*(T)` el error que se comete es del orden de :math:`\frac{p- p^*(T)}{R_v T \rho_l} \times 100`. Así pues, en todos nuestros análisis de procesos de aire húmedo, cuando tengamos el aire en equilibrio con agua líquida tomaremos como presión de saturación la correspondiente al agua como sustancia pura.
