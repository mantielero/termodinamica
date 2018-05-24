Ejercicio 10.2
^^^^^^^^^^^^^^

Cierto día se alcanza una temperatura de 34°C , con una humedad relativa del 20%. Para acondicionar una vivienda se utiliza un sistema de humidificación adiabática.

Si a la salida se requiere tener una temperatura de 21°C, determinar de forma analítica y con el diagrama psicrométrico la cantidad de agua que hay que añadir al aire y la humedad relativa del mismo.

La presión atmosférica es de 1 bar y el agua se suministra a la temperatura de salida del aire.

Solución
''''''''

De la ecuación (10.6) se obtiene

.. math::

   p_v = \phi \cdot p^*

:math:`p^*` de las tablas de propiedades termodinámicas del agua en saturación a :math:`\theta = 34°C` es

.. math::

   p^*(34°C) = 0.05324bar
   p_v =  0.2 \cdot 0.05324 = 0.010648bar


De la ecuación (10.4)

.. math::

   \omega_1 = 0.622 \cdot \frac{p_v}{p-p_v} = 0.622\cdot \frac{0.010648}{1-0.010648} = 6.694 \cdot 10^{-3} \frac{kg}{kg}
   
De la ecuación (10.57)

.. math::

   h_2 - h_1 = (\omega_2- \omega_1)h_l

y con las ecuaciones (10.17) y (10.18)

.. math::

   \left[
   \begin{array}
   h = c_{p-1} \theta \omega [h_{lv}(\theta_{ref})+c_{p_v} \theta] \\
   h_l = c_l \theta + \frac{p-p_{ref}}{\rho_l}
   \end{array}
   \right. \\
   c_{p_a} \theta_2 + \omega_2 [h_{lv}(\theta_{ref})+c_{p_v} \theta_2]- c_{p_a} \theta_1 - \omega_1 [h_{lv}(\theta_{ref})+c_{p_v} \theta_1] = (\omega_2- \omega_1)c_l \theta_l \\
   \omega_2 = \frac{\omega_1 [h_{lv}(\theta_{ref})+c_{p_v} \theta_1] + c_{p_a} (\theta_2 - \theta_1)}{ [h_{lv}(\theta_{ref})+c_{p_v} \theta_1 - c_l \theta_l}\\
   \left[
   \begin{array}
   c_{p_v} = 1.82\frac{kJ}{kg \cdot K} \\
   c_{p_a} = 1.005\frac{kJ}{kg \cdot K}  \hspace{2cm} p^*(21°C) = 0.02487bar\\
   c_l = 4.18 \frac{kJ}{kg \cdot K}
   \end{array}
   \right. \\
   \omega_2 = \frac{29.6359}{2451.84} = 0.012087 \frac{kg}{kg}
    
De la ecuación (10.4) 

.. math::

   p_v = \frac{\omega \cdot p}{0.622+\omega}

y de la ecuación (10.6)

.. math::

   \phi = \frac{p_v}{p^*} \Rightarrow \phi_2 = \frac{\omega_2 p}{(0.622+\omega_2)p^*} = \frac{0.012087 \cdot 1}{(0.622+0.012087)\cdot 0.02487} = 0.7665 = 76.65% \\
   \frac{\dot{m}_l}{\dot{m}_a} = (\omega_2 - \omega_1) = 5.39\cdot 10^{-3}\frac{kg}{kg}

La resolución utilizando el diagrama psicrométrico se deja como ejercicio.
