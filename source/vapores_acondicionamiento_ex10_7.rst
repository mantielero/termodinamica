Ejercicio 10.7
^^^^^^^^^^^^^^

En un recinto entra una cierta cantidad de aire a una temperatura de 15°C. Debido a la actividad que se produce en el recinto se liberan :math:`8\frac{kJ}{s}` de calor y se añaden :math:`1.4\cdot 10^{-3}\frac{kg}{s}` de vapor de agua saturado a 30°C. Después de estos procesos, el aire sale del recinto a 25°C de temperatura seca y 19°C de temperatura húmeda.

Determinar la temperatura húmeda del aire que entra al recinto y su volumen específico.

Solución
''''''''

Este problema puede resolverse de forma analítica, como se ha hecho en otros, o de una manera más simple utilizando el diagrama psicrométrico.

.. figure:: ./img/acondicionamiento_ejercicio2.png

De las tablas de propiedades termodinámicas del agua en saturación, la entalpia de vapor de agua a 30° C es :math:`2556\frac{kJ}{kg}`

De la ecuación (10.49a)

.. math::

   \frac{h_2 - h_1}{\omega_2 - \omega_1} = \frac{\dot{Q} + \sum_e (\dot{m}_w h_w)_e - \sum_s (\dot{m}_w h_w)_s }{\sum_e \dot{m}_{w_e} -  \sum_s \dot{m}_{w_s} } \\
   \frac{h_2 - h_1}{\omega_2 - \omega_1} = \frac{8+1.4\cdot 10^{-3}\cdot 2556}{1.4\cdot 10^{-3}} = 8270\frac{kJ}{kg_{agua}}

Entrando con este valor en el gráfico adicional del diagrama psicrométrico se obtiene la pendiente de la recta sobre la que se encuentran los puntos inicial y final.

.. figure:: ./img/acondicionamiento_ejercicio3.png

Del diagrama se obtiene un valor de

.. math::

   \theta_{\text{húmedo}_1} = 14°C \\
   v_1 = 0.829 \frac{m^3}{kg}
   
Otra manera de resolver el problema es utilizando la definición del factor FCS. En este caso

.. math::

   FCS = \frac{\dot{Q}}{\dot{Q} + \sum_e (\dot{m}_w h_w)_e - \sum_s (\dot{m}_w h_w)_s }

y entrando con este valor en el gráfico del factor FCS del diagrama psicrométrico se procede igual que antes, obteniendo un resultado análogo.

