Ejercicio 10.1
^^^^^^^^^^^^^^

Para cierto proceso se necesita tener aire saturado con una humedad de :math:`0.007\frac{kg}{kg}`. Se utiliza :math:`0.5\frac{kg}{s}` de aire atmosférico a 25°C y con una humedad relativa del 60%.

Calcular la cantidad de calor que se necesita extraer del aire para obtener las condiciones deseadas.

La presión atmosférica es 1 bar.

Solución
''''''''

El calor que hay que extraer se calcula a partir de la ecuación (10.53)

.. math::
   
   \dot{Q} = \dot{m}_a (\dot{h}_2 - \dot{h}_1  )+ \dot{m}_a (\omega_2 - \omega_1) h_l
   
Se necesita conocer el valor de :math:`\dot{m}_a`, y puesto que

.. math::

   \dot{m} = \dot{m}_a + \dot{m}_v = \dot{m}_a (1+\omega)
   
resulta que

.. math::

   \dot{m}_a = \frac{\dot{m}}{1+\omega_2} = \frac{0.5\frac{kg}{s}}{1+0.007\frac{kg}{kg}} = 0.4965\frac{kg}{s}
   

De la ecuación (10.6)

.. math::

   p_v = \phi_1 \cdot p^*(25°C) \\
   p_{v_1} = 0.6 \cdot 0.03169bar = 0.019014bar

y de la ecuación (10.4)

.. math::

   \omega_1 = 0.622 \frac{p_{v_1}}{p-p_{v_1}} \\
   \omega_1 = 0.622 \frac{0.019014}{1-0.019014} = 0.012\frac{kg}{kg}
   

También es preciso calcular :math:`\theta_2`. Como a la salida el aire está saturado, de la ecuación (10.4)

.. math::

   p_2^* = \frac{p \cdot \omega_2}{0.622 - \omega_2} = \frac{1 \cdot 0.007}{0.622-0.007} = 0.01138bar


Con este valor y la tabla de propiedades termodinámicas del agua en saturación

.. math::

   \theta_2 = 8.9°C

El valor de la entalpia es

.. math::

   h_2 &= c_{p_a} \theta_2 + \omega_2[ h_{l_v}(\theta_{ref}) + c_{p_v} \theta_2] = 1.005\cdot 8.9 + 0.007 [2501.4 +  1.82 \cdot 8.9] = 26.57\frac{kJ}{kg} \\
   h_1 &= c_{p_a} \theta_1 + \omega_1[ h_{l_v}(\theta_{ref}) + c_{p_v} \theta_1]  = 1.005 \cdot 25 + 0.012(2501.4 + 1.82\cdot25] = 55.69\frac{kJ}{kg} \\
   h_l &= c_l \theta_l = 4.18 \cdot 8.9 = 37.2 \frac{kJ}{kg}

De lo anterior se obtiene

.. math::

   \dot{Q} = 0.4965(26.57 - 55.69) + 0.4965(0.012 - 0.007) \cdot 37.2 \\
   \dot{Q} = -14.37 \frac{kJ}{s}
