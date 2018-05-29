Aplicación del primer principio a sistemas simples cerrados
===========================================================

Se ha visto que la aplicación del primer principio a un sistema cerrado conduce a las expresiones :

.. math::

   \delta Q + \delta W = dE \\
   Q_{12} + W_{12} = \Delta E

Según se considere un proceso elemental o un proceso finito. En el caso de querer referir el es­ tudio a la unidad de masa del sistema, se tendría:

 
.. math::

   \delta q + \delta w = de \\
   q_{12} + w_{12} = \Delta e
 
En  un  principio. considerremos únicamete la posibilidad  de trabajo  reversible  y  para
el caso de que se considere un sistema compresible slillple, el trabajo :math:`\delta w = -p dv` y :math:`w_{12} = \int_1^2 -pdv`; si además se supone que la única forma de energía importante es la variación de energía interna, *u*, las expresiones anteriores tomarán la forma:


.. math::

   \delta q - pdv = du \\
   q_{12} - \int_1^2 pdv = \Delta u

Por la frecuencia con que se presentan  es conveniente considerar la aplicación de ( 2. 5) L Y (2.6) a procesos que se realizan a volumen constante y a presión constante.

Si el proceso se realiza a **volumen constante** (isocoro):

.. math::

   \delta q_v -0 = d u_v
   

Por ser *u* una propiedad termodinámica del sistema se podrá expresar en función de dos variables termodinámicas del mismo . Se suelen escoger *T* y *v* como variables adecuadas para expresar esta función, por lo que:

.. math::

   du = \left( \frac{\partial u}{\partial T} \right)_v dT +  \left( \frac{\partial u}{\partial v} \right)_T dv
   

 
y para un proceso a volumen constante:

.. math::

   du_v = \left( \frac{\partial u}{\partial T} \right)_v dT_v
 

Por definición se hace:

.. math::

   c_v =  \left( \frac{\partial u}{\partial T} \right)_v 


y  se  le  denomina  calor específico a volumen constante.  Sus unidades  son  :math:`\frac{kJ}{kg \cdot K}` o :math:`\frac{kJ}{kmol \cdot K}`, según se refiera a la unidad de masa o a la unidad de sustancia.

Sustituyendo en (2.9) e igualando con (2.7), se obtiene:

.. math::

   du_v = c_v dT = \delta q_v

por lo que otra forma de expresar :math:`c_v`  es hacerlo mediante la equivalencia:	

.. math::

   c_v = \frac{\delta q_v}{dT}

Esta forma de expresar :math:`c_v` sirve de base a la determinación calorimétrica de :math:`c_v`. Para realizar esta determinación experimental se mide la cantidad de calor transferida a volumen constante a un determinado sistema, :math:`q_{12(v)}`,  necesaria para conseguir un incremento de temperatura  :math:`\Delta T_v`, y :math:`c_v` será igual a :math:`\frac{q_{12(v)}}{\Delta T_v}` 


Teniendo en cuenta la posibilidad  de determinar :math:`c_v`, se puede dar una expresión de *du*, para un sistema compresible simple, mediante la expresión:


.. math::

   du_v = c_v dT +  \left( \frac{\partial u}{\partial v} \right)_T dv
 

'· Para analizar la aplicación del primer principio a un sistema que experimenta una transformación a presión constante, utilicemos la ecuación ( 2. 5 ).

.. math::
   
   \delta q_p -p dv_p = du_p

 
de donde
 
.. math::
   
   \delta q_p = p dv_p + du_p = d(u+pv)_p
 

El conjunto de propiedades (u + pv ) se presenta de esta forma con la suficiente frecuencia para que merezca la pena adscribirle un nombre especial y un símbolo especial: se le denomina entalpía y se representa por la letra *h*:

.. math::

   H &\equiv U + pV\\
   h &\equiv u + pv
 


Por ser una combinación de propiedades termodinámicas , también es una propiedad termodinámica  y para un  sistema simple podrá expresarse en función  de dos propiedades  termodinámicas cualesquiera. Para sistemas compresibles es frecuente escoger *T* y *p*, por lo que
*h(T, p)*, será:

.. math::

   dh = \left( \frac{\partial h}{\partial T} \right)_p dT + \left( \frac{\partial h}{\partial p} \right)_T dp
   

por definición :

.. math::
  
   c_p = \left( \frac{\partial h}{\partial T} \right)_p

y


.. math::

   dh = c_p dT + \left( \frac{\partial h}{\partial p} \right)_T dp


para una transformación a *p constante*:

.. math::

   dh_p = c_p dT
 
Sustituyendo en (2. 12), *h = u + pv* y teniendo en cuenta (2. 14), se obtiene:
 
.. math::

   \delta q_p = c_p dT


 
r. ¡..J;.
 

 
Esta, análogamente a lo que ocurrió con :math:`c_v`, proporciona la base para un posible método experimental de determinación de :math:`c_p` midiendo el calor transferido a presión constante a un sistema y el correspondiente  incremento de *T*.

En general:

.. math::

   q_{p(1,2)} = \int_1^2 c_p dT


La integración del segundo miembro es, en general, fácil de hacer, aunque con frecuencia haya que recurrir a métodos gráficos o numéricos.

Cómo es fácil  ver, :math:`c_p` se mide en las mismas unidades que :math:`c_v`.

Conviene destacar que, tanto en el caso de una transformación  a volumen constante como a presión constante, el calor transferido en el proceso es posible darlo como diferencia del valor  de propiedades  termodinámicas  del  sistema correspondientes  a los estados extremos (*u* y *h* respectivamente),  es decir:

.. math::
   
   q_{v(1,2)} = u_2 - u_1 \\
   q_{p(1,2)} = h_2 - h_1 

 
Consideremos ahora qué ocurre cuando, además de trabajo	reversible hay una aportación de trabajo irreversible al sistema, como podría ser la agitación mediante paletas, aporte de carga eléctrica a través de una resistencia eléctrica, etc.. La ecuación del primer principio para un sistema compresible simple, para transformaciones a volumen constante y a	presión constante, toma las formas siguientes:

.. math::

   \delta q_v + \delta w_{irre} -p \cdot 0 = du_v \\
   \delta q_p + \delta w_{irre} -p \cdot dv = du_p 


de donde se obtiene:	

.. math::

   \delta q_v + \delta w_{irre} &= du_v \\
   \delta q_p + \delta w_{irre} &= dh_p 

Para un proceso finito tendríamos:

.. math::

   q_{v(1,2)} + w_{irre} &= \Delta u_v \\
   q_{p(1,2)} + w_{irre} &= \Delta h_p 

Vemos que, para un  determinado cambio de estado, independientemente de que la transformación en conjunto sea reversible o no lo sea, tanto la variación de *h* como la de *u* estarán perfectamente definidas, por lo que conociendo alguno de los otros dos datos, es posible determinar el tercero.
