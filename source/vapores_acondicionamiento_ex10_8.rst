Ejercicio 10.8
^^^^^^^^^^^^^^

Un día de verano las condiciones atmosféricas son:

a)	Presión atmosférica 985bar.
b)	Temperatura 32°C.
c)	Humedad relativa 70%

A partir de estas condiciones se desea obtener aire a 22°C y una humedad relativa del 45%. Para ello se dispone de una unidad de refrigeración y otra de calentamiento que proporcionan aire er 'as condiciones deseadas.

Determinar:

a)	La cantidad de agua eliminada en :math:`kg/kg_{\text{aire seco}}`
b)	El calor extraído por la unidad de refrigeración en :math:`kJ/kg_{\text{aire seco}}`
c)	La cantidad de calor cedido en la sección de calentamiento en :math:`kJ/kg_{\text{aire seco}}`

Solución
''''''''

El proceso seguido por el aire será como el representado en la Fig.27. En la solución del problema se seguirá la nomenclatura de dicha figura.

a) De la ecuación (10.4) y (10.6) se obtiene

.. math::

   \omega = 0.622 \frac{p^* \phi}{p - p^* \phi}

De las tablas de propiedades termodinámicas del agua en saturación

.. math::

   p^*(32°C) = 47.59mbar \\
   p^*(22°C) = 26.45mbar 
   

y por tanto

.. math::

   \omega_1 = 0.622 \frac{0.7 \cdot 47.59}{985 - 0.7 \cdot 47.59} = 2.18 \cdot 10^{-2} \frac{kg}{kg} \\
   \omega_2 = 0.622 \frac{0.45 \cdot 26.45}{985 - 0.45 \cdot 26.45} = 7.61 \cdot 10^{-3} \frac{kg}{kg} 
   
La cantidad de agua eliminada es

.. math::

   \Delta \omega = \omega_4 - \omega_1 = -1.42 \cdot 10^{.2} \frac{kg}{kg}


b)	De la ecuación (10.53)

.. math::

   \dot{Q} = \dot{m}_a (h_3 - h_1) + \dot{m}_a (\omega_1 - \omega_3) h_l \\
   \dot{q} =  (h_3 - h_1) + (\omega_1 - \omega_3) h_l


Necesitamos conocer la temperatura en el punto 3 y para ello sabemos que la temperatura en el punto 3 se corresponde con la temperatura de rocío correspondiente al punto 4. De la ecuación (10.8)

.. math::

   T_R(K) = \frac{T_4(K)}{1 - \frac{T_4(K) \ln \phi_4}{5121}} = \frac{295}{1 - \frac{295\cdot \ln 0.45}{5121}} = 282K \\
   \theta_R = 9.03°C \\
   \theta_3 = \theta_l = \theta_R = 9.03°C 
   
Además

.. math::

   \omega_3 = \omega_4 = 7.61 \¢dot 10^{-3} \frac{kg}{kg} \\
   \dot{q} = c_{p_a} (\theta_3 - \theta_1) + h_{lv}(\theta_{ref})(\omega_3 -\omega_1)  + c_{p_v} (\omega_3 \theta_3 - \omega_1 \theta_1) + (\omega_1 - \omega_3) c_l \theta_l \\
   \dot{q} = 1.005(9.03 - 32) + 2501.4(7.61 \cdot 10^{-3} -2.18 \cdot 10^{-2}) + 1.82 (7.61 \cdot 10^{-3} \cdot 9.03 - 2.18 \cdot 10^{-2} \cdot 32) + (2.18 \cdot 10^{-2} - 7.61 \cdot 10^{-3} ) \cdot 4.18 \cdot 9.03 \\
   \dot{q} = -59.19 \frac{kJ}{kg}
   

c)	De la ecuación (10.61)

.. math::

   \dot{Q} = \dot{m}_a (h_4 - h_3) \\
   \dot{q} = h_4 - h_3 \\
   \dot{q} = c_{p_a} (\theta_4 - \theta_3) + h_{lv}(\theta_{ref}) (\omega_4 -\omega_3) + c_{p_v} (\omega_4 \theta_4 - \omega_3 \theta_3)
   
y puesto que :math:`\omega_4 = \omega_3` queda

.. math::

   \dot{q} = c_{p_a} (\theta_4 - \theta_3) + c_{p_v} \omega_3 (\theta_4 - \theta_3)  \\
   \dot{q} = (c_{p_a}  + c_{p_v} \omega_3) (\theta_4 - \theta_3) \\
   \dot{q} = (1.005 + 1.82 \cdot 7.61 \cdot 10^{-3})(22-9.03) \frac{kJ}{kg} \\
   \dot{q} = 13.2\frac{kJ}{kg}

El problema se puede resolver fácilmente utilizando el diagrama de Mollier, obteniendo resultados análogos.

