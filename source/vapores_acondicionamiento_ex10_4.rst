Ejercicio 10.4
^^^^^^^^^^^^^^

Se desea obtener :math:`0.83\frac{kg}{s}` de aire a una temperatura de 35°C. Para ello, se utiliza aire atmosférico a una temperatura de 4°C y con una humedad de :math:`0.0045\frac{kg}{s}` , que se hace pasar por un cambiador de calor que aumenta su temperatura hasta el valor deseado. 

Calcular la cantidad de calor que es necesario suministrar para realizar dicho proceso.

La presión atmosférica es 1 bar.

Solución
''''''''

El valor pedido se calcula a partir de la ecuación (10.61)

.. math::

   \dot{Q} = \dot{m}_a (h_2 - h_1)

Puesto que 

.. math::

   \dot{m} = \dot{m}_a + \dot{m}_v = \dot{m}_a (1+\omega)

y por tanto

.. math::

   \dot{m}_a = \frac{\dot{m}}{1+\omega} = \frac{0.83 \frac{kg}{s}}{1+0.0045\frac{kg}{kg}} = 0.826 \frac{kg}{s}

De la ecuación (10.17)

.. math::

   h = c_{p_a} \theta + \omega [h_{lv}(\theta_{ref}) + c_{p_v} \theta]

queda

.. math::

   h_1 = 1.005 \cdot 4 + 0.045[2501.4+1.82 \cdot 4] = 15.3\frac{kJ}{kg}\\
   h_2 = 1.005 \cdot 35 + 0.045[2501.4+1.82 \cdot 35] = 46.7 \frac{kJ}{kg}
   

y por tanto la cantidad de calor que hay que suministrar es

.. math::

   \dot{Q} = 0.826 \frac{kg}{s} (46.7\frac{kJ}{kg} - 15.3\frac{kJ}{kg} = 25.9\frac{kJ}{s}

