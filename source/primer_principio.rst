Primera Ley de la Termodínamica. Postulado de Estado
====================================================

El concepto de trabajo y los procesos adiabáticos
-------------------------------------------------

Trabajo
   interacción entre sistema y medio ambiente que, cuando es realizado por el sistema, su único efecto sobre el ambiente "puede representarse" por la elevación de un peso.

Criterio de signos
   positivo cuando vaya al sistema y negativo cuando salga de él (puede ser el criterio contrario)

Transformación adiabática
   aquella en la que sólo intervienen interacciones de trabajo.

Primer principio
----------------

La cantidad de trabajo adiabático suministrado a un sistema para llevarlo desde un estado a otro no depende del procedimiento seguido para conseguir ese cambio, sino sólamente de los estados inicial y final. (Demostrado empíricamente).

El :math:`W_{adiabático}` será la medida de una propiedad a la que llamaremos **energía total**. Ya que sólo depende de los estados final e inicial:

.. math::

   \delta E = E_2 - E_1 = W_{adiabático}

.. note::

   Aunque entre 1 y 2 no haya un proceso adiabático, siempre podemos localizar un punto R tal que  :math:`\overline{1R}` y :math:`\overline{R2}` sean adiabáticos. En ese caso:

   .. math::
      \delta E = E_2-E_1 = W_{adiabático}

.. note::

   Podemos calcular :math:`\delta E` pero no :math:`E` en un momento dado.


Principio de conservación de la energía para sistemas cerrados
--------------------------------------------------------------

.. math::

   \delta E = W_{21}+Q_{12} \text{ , en donde } Q_{12} \text{ son }





Equilibrio
----------


Equilibrio termodinámico: equilibrio mecánico, equilibrio térmico, equilibrio de fase y equilibrio químico.

Procedimiento: aislamos del medio ambiente. Si no cambian las propiedades, estaba en equilibrio, si no, no.

.. note::

   En el eqilibrio, las propiedades del sistema tienen igual valor en cada fase del mismo.

.. note::

   Sólo tiene sentido hablar de propiedades del sistema cuando éste está en equilibrio.

Proceso de relajación: paso de un estado de no equilibrio a uno de equilibrio (:math:`\tau=` tiempo de relajación = lo que dura el proceso).

Modelos de procesos:

- Proceso reversible: el que experimenta un sistema que mantiene el estado de equilibrio termodinámico en todo instante.
- Proceso cuasiestático: :math:`\tau<< t_p`, en donde, :math:`t_p=` tiempo del proceso. nos movemos casi en estado de equilibrio. Es el modelo a utilzar cuando un proceso es lento.

.. note:: en probelmas, bsaa con definir los estados inicial y final para que podamos deducir ciertos efectos globales que ocurren durante el proceso.

Densidad, volumen específico, presión
-------------------------------------

.. math::

   \rho = \lim_{\delta V \rightarrow \delta V'} \frac{\Delta m}{\Delta V}

Las unidades serán: :math:`[SI]=\frac{kg}{m^3}`

en donde:

- :math:`\delta V'`: volumen más pequeño comparable con la idea distribución continua de la materia. Es decir, lo más pequeño posible moviéndonos en el estadio macroscópico.
- :math:`v = \frac{1}{\rho}`: ¿volumen específico?
- :math:`\rho = \lim_{\Delta A \rightarrow \Delta A'} \frac{\Delta F_n}{\Delta A}`: en donde :math:`F_n` tiene componente normal a :math:`\Delta A`. Cierto en un sistema en equilibrio. Esto es válido para un fluido. como un fluido no soporta esfuerzos tangenciales, la única fuerza que soportará será la normal a la superficie (presión hidrostática). Ver pag. 19.

La presión de un fluido en equilibrio es uniforme sobre su límite y en el interior del mismo.

Presión manométrica:

.. math::

   P_a = P_{manométrica}+ P_{atmosférica}

en donde:

- :math:`P_a`: presión absoluta (la que se usa en termodinámica).

Evaluar  los cambios de presión dentro de un fluido (gas o líquido) en presencia de campo gravitatorio:

.. math::

   P_z \Delta A &= P_z dz \cdot \Delta A + \rho g \Delta A dz\\
   -dP &= \rho g dz

en donde:

- :math:`\rho = rho(z)`: el aire  lejos es menos denso; :math:`g=g(z)` (recordar ecuaciones)

Para diferencias de altura suficientemente pequeñas: p y g son constantes. En ese caso:

.. math::

   P_2-P_1 = -pg(z_2-z_1)

Presión de vacío: es la presión manométrica uando la presión absoluta es la atmosférica.

Unidades:

.. math::

   [SI] = 1Pa=1N\cdot m^{-2}\\
   1bar = 10^5Pa\\
   \text{Presión atmosférica estándar: }1'01325bar

Temperatura y Ley Cero
----------------------

Sean dos sistemas A y B con el mismo gas. A y B con la misma densidad :math:`rho`, presiones distintas y temperaturas distintas (lo sabemos tocándolo; no nos confundimos porque se trata de la misma sustancia y no de hierro y madera, por ejemplo).

Los ponemos en contacto:

a. :math:`P_A^{(1)} = P_A^{(2)}` y :math:`P_B^{(1)} = P_B^{(2)}`; paredes adibáticas: aislante térmico.
b. :math:`P_A^{(2)} = P_B^{(2)}`; paredes diatérmanas (o diatérmicas): conductoras térmicas.

Equilibrio térmico: estado que se mantiene independiente del tiempo

.. note:: un material que sea conductor térmico lo será sean cuales sean las sustancias puestas en contacto.

Los procesos rápidos serán adiabáticos. Los procesos lentos serán diatérmicos (equilbrio térmico con el medio ambiente).

Principio cero de la termodinámica: A en equilibrio térmico con B y B en equilibrio térmico con C implica que A está en equilibrio térmico con C. (se observa empíricamente)

Temperatura: característica o propiedad común que tienen dos sistemas en equilibrio térmico.

Escala empírica de temperaturas:





