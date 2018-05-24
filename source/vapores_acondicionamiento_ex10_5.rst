Ejercicio 10.5
^^^^^^^^^^^^^^

En el proceso de acondicionamiento de un edificio se han de mezclar adiabáticamente :math:`75\frac{m^3}{min}` de aire exterior a 30°C y 80% de humedad relativa con :math:`100\frac{m^3}{mm}` de aire interior tratado a 19°C y 30% de humedad relativa.

Determinar para la mezcla resultante:

a)	Humedad.
b)	Temperatura seca.
c)	Temperatura húmeda.
d)	Humedad relativa.

Resolver el problema analítica y gráficamente suponiendo que la presión se mantiene igual a 1bar.

Solución
''''''''

Antes de nada vamos a calcular los gastos, humedad, y entalpia en las entradas.

De la ecuación (10.6)

.. math::

   p_v = \phi \cdot p^*
   


y con los valores de :math:`p^*` obtenidos de las tablas de propiedades termodinámicas del agua en saturación

.. math::

   p_1^* = 0.04246bar \\
   p_2^* = 0.02198bar \\
   p_{v_1} = 0.8 \cdot 0.04246 = 0.033968bar \\
   p_{v_2}= 0.3 \cdot 0.02198 = 0.006594bar 
   

y por tanto

.. math::

   p_{a_1} = 1-0.033968 = 0.966bar \\
   p_{a_2} = 1-0.006594 = 0.993bar


De la ecuación de estado :math:`p\cdot \dot{V} = \dot{m} \cdot R \cdot T` para el aire queda

.. math::

   \dot{m_{a_1}} = \frac{p_{a_1 \dot{V}_1}}{R_a T_1} = \frac{0.966 \cdot 10^5 \cdot 75}{287 \cdot 303} = 83.31\frac{kg}{min} \\
   \dot{m_{a_2}} = \frac{p_{a_2 \dot{V}_2}}{R_a T_2} = \frac{0.993 \cdot 10^5 \cdot 100}{287 \cdot 292} = 118.5 \frac{kg}{min}

Para calcular la humedad recurrimos a la ecuación (10.4) puesta en la forma

.. math::

   \omega = 0.622 \frac{p_v}{p_a} \\
   \omega_1 = 0.622 \frac{0.033968}{0.966} = 0.02187\frac{kg}{kg} \\
   \omega_2 = 0.622 \frac{0.006594}{0.993} = 118.5\frac{kg}{min}

Para calcular las entalpias recurrimos a la ecuación (10.17)

.. math::

   h = c_{p_a} \theta + \omega [h_{lv}(\theta_{ref}) + c_{p_v} \theta] \\
   h_1 = 1.005 \cdot 30 + 0.02187 [2501.4 + 1.82 \cdot 30] = 86.05 \frac{kg}{kg} \\
   h_2 = 1.005 \cdot 19 + 0.004130 [2501.4+1.82 \cdot 19] = 29.57\frac{kJ}{kg}

a) De la ecuación (10.66)

.. math::

   \omega_3 = \frac{\dot{m}_{a_1} \omega_1 + \dot{m}_{a_2} \omega_2 }{ \dot{m}_{a_1} + \dot{m}_{a_2}} = \frac{83.31\cdot 0.02187 + 118.5 \cdot 0.004130}{83.31+118.5} = 0.01145\frac{kg}{kg}

b) De la ecuación (10.66)

.. math::

   h_3 = \frac{\dot{m}_{a_1} h_1 + \dot{m}_{a_2} h_2 }{ \dot{m}_{a_1} + \dot{m}_{a_2}} 

y como :math:`h_3 = c_{p_a} \theta_3 + \omega_3[h_{lv}(\theta_{ref}) + c_{p_v} \theta_3]` queda

.. math::

   \theta_3 = \frac{ \frac{\dot{m}_{a_1} h_1 + \dot{m}_{a_2} h_2 }{ \dot{m}_{a_1} + \dot{m}_{a_2}} - \omega_3 h_{lv}(\theta_{ref}) }{c_{p_a} + \omega_3 c_{p_v}} \\
   \theta_3 = \frac{ \frac{83.31 \cdot 86.05 + 118.5 \cdot 29.57 }{ 83.31 + 118.5} - 0.01145 \cdot 1501.4 }{1.005  + 0.01145 \cdot 1.82}  \\
   \theta_3 = 23.6°C \\
   h_3 = 52.88 \frac{kJ}{kg}

c) Utilizando la definición de temperatura húmeda y para el proceso de saturación 3 — 3'

.. math::
 
   h_3 + (\omega_{3'} ~ \omega_3 )h_l = h_{3'}
   
y con

.. math::

   \omega_{3'} = 0.622 \frac{p_{v_{3'}}}{ p -p_{v_{3'}}} = 0.622 \frac{p^*}{p-p^*}


queda

.. math::

   52.88 + \left( 0.622 \frac{p^*}{p- p^*} - 0.01145\right) 4.18 \theta_{3'} = 1.005 \theta_{3'} + 0.622 \frac{p^*}{p- p^*} [2501.4 + 1.82 \theta_{3'}]


y reordenándola queda

.. math::

   0 = 50.225+ \frac{p^*}{p- p^*} [1.394 \theta_{3'} -1477.8] - \theta_{3'} = y

Para resolverla se utiliza el método de prueba y error, calculando :math:`p^*` en las tablas de propiedades termodinámicas del agua en saturación.

+--------------------------+-------------------+-------+
| :math:`\theta_{3'}` (°C) | :math:`p^*` (bar) | y     |
+==========================+===================+=======+
| 20.0                     |  0.02339          | -4.50 | 
+--------------------------+-------------------+-------+
| 18.0                     | 0.02064           | 1.61  |
+--------------------------+-------------------+-------+
| 19.0                     | 0.02198           | -1.39 |
+--------------------------+-------------------+-------+
| 18.5                     | 0.02131           | 0.11  | 
+--------------------------+-------------------+-------+

Por lo que tomamos :math:`\theta_{\text{húmeda}} = 18.5°C`

d) De la ecuación (10.6)

.. math::

   \phi = \left. \frac{p_v}{p^*} \right|_{p,T}

y de la ecuación (10.4)

.. math::

   \omega = 0.622 \frac{p_v}{p - p_v}

y con :math:`p^*(23.6°C) = 0.02915bar` se obtiene

.. math::

   \phi &= \frac{ \omega p }{ ( 0.622 + \omega ) p^{*} } =  \frac{ 0.01145 \cdot 1 }{ (0.622 + 0.01145) \cdot 0.02915} = 0.62 \\
   \phi &= 62\%   
        


La resolución gráfica se deja como ejercicio.

