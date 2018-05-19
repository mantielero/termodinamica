Propiedades termodinámicas de las sustancias en la línea de transición de fase. Sistemas de dos fases
-----------------------------------------------------------------------------------------------------

En los cambios de fase considerados hasta ahora, hemos visto que en la línea de saturación en el diagrama *p* , *T*, o bien en la zona de saturación, si consideramos cualquier otro diagrama, las tres propiedades termodinámicas :math:`c_p`, :math:`\alpha` y :math:`\kappa_T` se hacen infinitas. La justificación de este hecho resulta inmediata, ya que al ser:


.. math::

   c_p = T\left( \frac{\partial s}{\partial T} \right)_p \\
   \alpha = \frac{1}{v} \left( \frac{\partial v}{\partial T} \right)_p  \\
   \kappa_T = - \frac{1}{v} \left( \frac{\partial v}{\partial p} \right)_T

como en esta zona tanto *p* como *T* se mantienen constantes y *v* y *s* experimentan un cambio finito, es evidente que las tres propiedades mencionadas se hagan infinito.

Esto que es característico de la fusión, vaporización y sublimación, no es el comportamiento general de los sistemas que experimentan un cambio de fase, por lo que los cambios de fase se suelen clasificar en:

a. Cambios de fase de primer orden, 
b. Cambios de fase de segundo orden
c. Cambios de fase de orden superior.

a) Los cambios de fase de primer orden se caracterizan porque en la curva de saturación, las primeras derivadas de la función de Gibbs:

.. math::

   s = - \left( \frac{\partial g}{\partial T} \right)_p \\
   v = \left( \frac{\partial g}{\partial p} \right)_T

experimentan un cambio finito durante el proceso de paso de una fase a otra. La vaporización, fusión y sublimación, cumplen con esta condición.

b) Hay cambios en los que la entropía y el volumen no experimentan variación durante el proceso (cambios de fase de segundo orden, pero sí :math:`c_p`, :math:`\alpha` y :math:`\kappa_T`, que como sabemos, cumplen con las relaciones:

.. math::

   \frac{c_p}{T} = \left( \frac{\partial s}{\partial T} \right)_p = \frac{\partial}{\partial T} \left( - \frac{\partial g}{\partial T} \right)_p = - \left( \frac{\partial^2 g}{\partial T^2} \right)_p \\
   \kappa_T v = - \left( \frac{\partial v}{\partial p} \right)_T = \frac{\partial}{\partial p} \left( \frac{\partial g}{\partial p} \right)_T = - \left( \frac{\partial^2 g}{\partial p^2} \right)_T \\
   \alpha v = \left( \frac{\partial v}{\partial T} \right)_p = \frac{\partial}{\partial T} \left( \frac{\partial g}{\partial p} \right)_T = \left( \frac{\partial^2 g}{\partial T \partial p} \right)
   

Es decir, se producen variaciones finitas en las derivadas segundas de la función de Gibbs. Para estos cambios de fase la ecuación de Clausius-Clapeyron nos lleva a una indeterminación:

.. math::

  \left[ \frac{dp}{dT} \right]_{I,II} = \frac{s_{II}-s_I}{v_{II}-v_I} = \frac{0}{0}


A fin de salvar esta indeterminación, apliquemos la regla de L’Hôpital. Derivando el segundo miembro de la ecuación anterior respecto a T y respecto a p, se obtiene:

.. math::

  \left[ \frac{dp}{dT} \right]_{I,II} = \frac{\left( \frac{\partial s_{II}}{\partial T} \right)_p - \left( \frac{\partial s_I}{\partial T} \right)_p }{ \left( \frac{\partial v_{II}}{\partial T} \right)_p - \left( \frac{\partial v_I}{\partial T} \right)_p  } = \frac{ \Delta c_p}{T \Delta \left( \frac{\partial v}{\partial T}\right)_p} \\
  \left[ \frac{dp}{dT} \right]_{I,II} = \frac{\left( \frac{\partial s_{II}}{\partial p} \right)_T - \left( \frac{\partial s_I}{\partial p} \right)_T }{ \left( \frac{\partial v_{II}}{\partial p} \right)_T - \left( \frac{\partial v_I}{\partial p} \right)_T  } = - \frac{ \Delta \left( \frac{\partial v}{\partial T} \right)_p }{\Delta \left( \frac{\partial v}{\partial p}\right)_T}  


De estas se deducen las ecuaciones para este tipo de cambios de fase, denominadas ecuaciones de Ehrenfest:

.. math::

   \Delta c_p = T \left[ \frac{dp}{dT} \right]_{I,II} \\
   \Delta \left( \frac{\partial v}{\partial T} \right)_p = -T  \left[ \frac{dp}{dT} \right]_{I,II}^2 \Delta \left( \frac{\partial v}{\partial p} \right)_T
   
   
ya que:

.. math::

   \Delta \left( \frac{\partial v}{\partial T} \right)_p = - \left[ \frac{dp}{dT} \right] \Delta \left( \frac{\partial v}{\partial p} \right)_T

En un principio se creyó que eran muchos los cambios de fase de segundo orden, no obstante la experimentación ha demostrado que sólo se ajusta a estas características el paso de superconductividad a conductividad normal en ausencia de campos magnéticos.

c)	Se denominan transiciones de fase de orden superior a las que, manteniendo la condición :math:`\Delta s = 0` y :math:`\Delta v = 0` como en las transiciones de fase de segundo orden, presentan una discontinuidad infinita en las derivadas de segundo orden o superior. Entre los cambios de fase de orden superior se citan: las transiciones orden-desorden en las aleaciones, los fenómenos ferroeléctricos en ciertas sales cristalinas, el paso de ferromagnetismo a paramagnetismo en el punto de Curie, etc.

De todos ellos el más interesante, por las implicaciones teóricas que conlleva, es la transformación He(I) (líquido) en He(II) (líquido) a una presión y temperatura conocidas como punto :math:`\lambda` y denominada así por el aspecto que presenta, en este punto, la gráfica de :math:`c_p` en función de *T*.
