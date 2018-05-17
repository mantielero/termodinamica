
Ejercicio E6.2
==============

Se ha de comprimir un gas monoatómico en un compresor que funciona en régimen estacionario, de forma reversible y a temperatura constante.

El gas entra al compresor a 300 K y 10 bar y se comprime hasta 150 bar.
Determínese:

1)	el trabajo requerido, por mol de gas, para hacer funcionar el compresor.
2)	la cantidad de calor intercambiado, si:

   a)	El gas se comporta como gas perfecto.
   b)	El comportamiento del gas obedece a la ecuación:

.. math::

   pv= RT - \frac{a}{T}p+bp

en la que:

.. math::

   a &= 0.385 \frac{K m^3}{kmol} \\
   b &= 0.0152 \frac{K m^3}{kmol} 


Relaciones termodinámicas generalizadas.

*******************

.. figure:: ./img/ejercicio_rtg2.png
   :align: center


Solución
--------

* Sistema: Volumen de control definido por la carcasa del compresor. * Interacciones: Las esquematizadas en la figura.
* Proceso: El representado en el diagrama.
* Ecuaciones aplicables: las (4.11) y (4.20)

.. math::

   q &= h_{ts} - h-{te} - w_x \\
   \sum_i \frac{Q_i}{T_i} &= \sum_s s \left. \dot{m} \right|_s — \sum_e s \left. \dot{m} \right|_e



En el caso que estamos considerando sólo hay una entrada y una salida y puede considerarse que únicamente se intercambia calor con una fuente térmica a 300K (proceso isotérmico), por lo que:

.. math::

   \frac{\dot{Q}}{T} = (s_s-s_e) \dot{m}
   

de donde:

.. math::

   q = T (s_s -s_e)


En esta ecuación podemos considerar valores por unidad de masa o por unidad de cantidad de sustancia (mol). Para el problema que nos ocupa conviene utilizar el mol.

Se ha de calcular :math:`w_x` y :math:`q`, por lo que, según (4.11) y (E.6.2.a):

.. math::

   w_x &= \Delta h - q \\
   q &= T \Delta s
   
Vemos que, calculado el incremento de entropía, puede determinarse :math:`q` y una vez conocido :math:`q` y calculado :math:`Dh`, se podrá determinar el trabajo.

Para calcular :math:`\Delta s` y :math:`\Delta h`, recordemos que según (6.43) y (6.45):

.. math::

   ds &= \frac{c_p}{T} dT - \left( \frac{\partial v}{\partial T}\right)_p dp \\
   dh &= c_p dT + \left[ v-T\left( \frac{\partial v}{\partial T} \right)_p\right] dp


para un proceso a temperatura constante:

.. math::

   ds_T = - \left( \frac{\partial v}{\partial T} \right)_p dp \\
   dh_T = \left[ v - T \left( \frac{\partial v}{\partial T} \right)_p\right] dp


a) En el caso de gas perfecto:

.. math::

   pv &= RT \\
   v &= \frac{RT}{p} \\
   \left( \frac{\partial v}{\partial T} \right)_p &= \frac{R}{p}
   ds_T = - \frac{R}{p}dp \\
   s_2-s_1 = -8.314 \int_10^150 \frac{dp}{p} = R \ln \frac{150}{10} = -22.51 \frac{kJ}{kmol} \\
   dh_T = \left[ v-T\frac{R}{p} \right] dp = 0 \\
   \Delta h = 0 \\
   q = TDs = 300(-22.51) = -6754.42 \frac{kJ}{kmol} \\
   w_x = Dh -q = 0+6754.42 = 6754.42 \frac{kJ}{kmol}
   

b) Gas real:

.. math::

   pv = RT -\frac{a}{T} p +bp \\
   v = \frac{RT}{p}-\frac{a}{T}+b \\
   \left( \frac{\partial v}{\partial T} \right)_p = \frac{R}{p}+\frac{a}{T^2} \\
   \left[ v-T \left( \frac{\partial v}{\partial T} \right)_p\right] = v- \frac{RT}{p}-\frac{a}{T} = \frac{RT}{p}-\frac{a}{T}+b-\frac{RT}{p}-\frac{a}{T} = - \frac{2a}{T}+b \\
   ds_T = - \left( \frac{\partial v}{\partial T} \right)_p= -\left( \frac{R}{p} + \frac{a}{T^2} \right) dp \\
   \Delta s = \int_10^150 - \left( \frac{R}{p} + \frac{a}{T^2} \right ) dp \\
   \Delta s_T = -8.314 \ln \frac{150}{10} - \frac{0.385}{300^2}(150-10) 10^2 = -22.57 \frac{kJ}{kmol \cdot K } \\
   dh_T = \left[ v- T \left( \frac{\partial v}{\partial T} \right)_p\right] dp = \left( b-\frac{2a}{T} \right) dp \\
   \Delta h_T = \int_10^150 \left(b- \frac{2a}{T} \right) dp = \\
   = b(150-10)10^2-\frac{2a}{300}(150-10)10^2= 176.86\frac{kJ}{kmol} \\
   q = -300 \cdot 22.57 = -6772.38\frac{kJ}{kmol} \\
   w_x = 176.86 - (-6772.38) = 6949.24\frac{kJ}{kmol}
   
