Formulación del primer principio para sistemas abiertos
-------------------------------------------------------

Consideremos un sistema A (esquematizado en la figura 4.1) definido por una frontera perfectamente determinada fi y un elemento diferencial de masa adyacente dm.

Instante t	Instante t + delta t

Figura 4.1 Masa de control elegida para aplicar el primer principio a sistemas abiertos.

Si dm puede pasar a través de 0 al interior del volumen de control y es p la presión que el medio exterior ejerce sobre ella mientras cruza la frontera, la interacción trabajo será igual a:

.. math::

   \delta W = -p dV_{sis}

en la que :math:`dV_{sis}`, tomando como sistema el conjunto masa contenida inicialmente en :math:`\Omega` más :math:`dm`, será igual a:

.. math:: 

   dV_{sis} = V_{sis(t+\Delta t)} - V_{sis(t)}

Ahora bien, :math:`V_{sis(t)} = V_{\Omega} - V_{dm}` y :math:`V_{sis(t+\Delta t)} = V_{\Omega}` pues el proceso de introducir la masa dentro :math:`\Omega` ha finalizado, por lo tanto :math:`dV_{sis}` queda:


.. math::

   dV_{sis} = V_{\Omega} - (V_{\Omega} + V_{dm}) = -V_{dm}

Si el volumen específico de la sustancia al alcanzar la superficie de entrada es :math:`v`, como la masa es :math:`dm`, tendremos :math:`V_{dm}=v dm` y :math:`dV_{sis} = -vdm`. Sustituyendo en la expresión del trabajo:

.. math::

   \delta W = -p (-vdm) = pvdm

Si designamos por :math:`E_1` y :math:`E_1  + dE` a las energías de la materia en el interior de :math:`\Omega` en los instantes :math:`t` y :math:`t +\Delta t` respectivamente, :math:`(e dm)` es la energía de la masa :math:`dm` en la frontera y durante el proceso hay una interacción térmica, entonces para el sistema cerrado elegido, tendremos:

.. math::

   (E_1 + dE) — (E_1+edm) = \delta Q + pv dm
   
   
Si además consideramos que durante el proceso hay una interacción trabajo, por variación de la frontera :math:`\Omega`, o por rotación de un eje (éste será el caso más frecuente) representemos por :math:`\delta W_x` (trabajo al eje) esta interacción, entonces podremos reescribir la ecuación anterior en la forma:

.. math::

   dE = \delta Q + (e + pv) dm + \delta W_x

donde :math:`dE` representa la variación de energía en el interior de :math:`\Omega`.

A la magnitud :math:`e + pv` se la denomina entalpía total, :math:`h_t`, y si despreciamos todo tipo de acción, menos la presencia del campo gravitatorio, recordarán que:

.. math::

   e = u+\frac{v^2}{2} + gz

por lo que:

.. math::

   dE &= \delta Q + \delta W_x + (h+\frac{v^2}{2} +gz) dm \\
      &= \delta Q + \delta W_x + h_t dm
      
Para la transferencia de una masa finita a través de :math:`\Omega`, los términos de la ecución (4.5) pueden ser sumados para todos los elementos en los que puede considerarse descompuesta la masa finita. Si un elemento de masa pasa a través de :math:`\Omega` hacia afuera, entonces :math:`dm` es negativo y :math:`h_t` es su entalpia por unidad de masa cuando emerge (es decir sobre la frontera :math:`\Omega`). Así:

.. math::

   E_2 - E_1 = Q + W_x + \sum_k \int h_{tk} dm_k
   
Un ejemplo simple al que puede aplicarse la ecuación anterior es al flujo adiabático de un gas desde una línea de alimentación a un depósito a presión más baja (llenado de botellas de gas). Cuando la presión se incrementa en la botella, el incremento de la energía interna del contenido de la botella es igual a la masa del fluido que entra por su entalpia total a la entrada.
Es interesante destacar que la ecuación formulada para aplicar el primer principio a sistemas cerrados:

.. math::

   dE = \delta Q + \delta W

sólo es aplicable a sistemas cerrados y no puede aplicarse a volúmenes de control o sistemas abiertos; tampoco es aplicable a estos sistemas la primera ley en la forma:

.. math::

   \oint \delta Q = - \oint \delta W

El flujo, por definición :math:`= a_k V` Por lo que el flujo máslco :math:`a_k \rho \textbf{V} \cdot \textbf{n}`

Figura 4.2 Flujo másico a través de un elemento de área

Para el volumen de control de la figura 4.2, podemos expresar la velocidad a la que gana masa el interior de :math:`\Omega` en función de los vectores área de la superficie de entrada y velocidad, así como de la densidad en los puntos donde el fluido cruza la superficie, tendremos:

.. math::

   \dot{m}_\Omega = -\sum_k \boldsymbol{V_k} \cdot \boldsymbol{n} a_k \rho_k

(ya que se considera positiva la masa que entra) en la que :math:`\dot{m}` representa la velocidad a la que el volumen limitado por :math:`\Omega` gana masa, :math:`\textbf{n}` es un vector unitario normal al área de la superficie :math:`a_k` en la que la velocidad es :math:`\boldsymbol{V_k}` y :math:`\rho_k` es la densidad del fluido en :math:`a_k`.

La expresión (4.5) podemos referirla a la unidad de tiempo:

.. math::

   \frac{dE}{dt} = \dot{Q} + \dot{W}_x + h_t \dot{m}
   
en la que :math:`\dot{m}` representa la velocidad de flujo másico en el volumen de control para una corriente simple que cruza la superficie de control, :math:`\dot{Q}`  la velocidad a la que se suministra calor y :math:`\dot{W_x}` la potencia mecánica suministrada al eje que cruza la frontera.	

Si en vez de ser una sola corriente, consideramos varias tendremos:

.. math::

   \frac{dE}{dt} = \dot{Q} + \dot{W}_x + \sum_e \left( h_t \dot{m} \right)_e - \sum_s \left( h_t \dot{m} \right)_s

Cuando sólo hay una corriente de entrada y una de salida y los flujos másicos son iguales, la ecuación anterior toma la forma:

.. math::

   \frac{ dE}{dt} = \dot{Q} +\dot{W_x} + (h_t e - h_t s) \dot{m}
   
Otra forma más general de expresar la ecuación anterior sería:


.. math::

   \int_V \frac{\partial(\rho e)}{\partial t} dV = -\int_{\Omega} \textbf{q} \cdot \textbf{n} da + \dot{W_x} - \int_{\Omega} \rho h_t \textbf{V} \cdot \textbf{n} da


En esta ecuación **q** y **V** representan el vector flujo de calor y el vector velocidad respectivamente, correspondientes a cada elemento de área en los que pueden definirse. Como siempre **n** es el vector unitario normal a la superficie del volumen de control y dirigido hacia el exterior de éste.

De acuerdo con (4.6) o (4.8.a) vemos que, para volúmenes de control que experimenten transformaciones cíclicas, no es posible aplicar la ecuación del primer principio en la forma:

.. math::

   \oint \delta Q = - \oint \delta W

pues quedarían sin considerar los términos correspondientes al flujo músico. Por el contrario, tanto las expresiones (4.6) como (4.8.a) serían aplicables a masas de control sin más que considerar nulos los correspondientes flujos másicos.

Proceso de flujo estacionario
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Un caso especial, y que es el que más frecuentemente se considera, es flujo estacionario. Por este nombre entendemos que el estado del fluido en cualquier punto dentro del volumen de control es el mismo a lo largo del tiempo, aunque, como ya se ha dicho, el estado del fluido cambia de una a otra sección del volumen de control. El estado de un sistema abierto para el que esta suposición se cumple se denomina *estado estacionario*.

La condición de estado estacionario requiere que *dE* sea cero, por lo que (4.6) se simplifica y puede expresarse mediante:

.. math::

   Q+W_x+\sum_k \int h_{tk} dm_k = 0

Si sólo hay una corriente de entrada y otra de salida, la ecuación (4.10) se convierte en:

.. math::

   q = h_{ts}-h_{te} -w_x
   
donde :math:`q` y :math:`w_x` representan el calor y el trabajo que, por unidad de masa, se suministran a través de las fronteras impermeables del sistema.

Variaciones periódicas en el estado dentro de :math:`\Omega` se pueden explicar también mediante las ecuaciones (4.10) y (4.11). Si los estados del fluido en todos los puntos dentro del volumen de control, periódica y simultáneamente, se hacen idénticos a estados previamente existentes en aquellos puntos, entonces estas ecuaciones también son aplicables sobre un conjunto de períodos completos. Así, estas ecuaciones se aplican tanto a una turbina como a un motor alternativo.

Para el flujo estacionario la ecuación (4.7) se reduce a:

.. math::

   \sum_k \boldsymbol{V_k} \cdot \boldsymbol{n} a_k \rho_k = 0
   
Cuando sólo hay una corriente de entrada y otra de salida con velocidad constante en cada sección normal al úrea tendremos:

.. math::
  
   \nu_1 a_1 \rho_1 = \nu_2 a_2 \rho_2 = \dot{m}
   

en la que :math:`\dot{m}` es el gasto a través de una sección del sistema y los subíndices 1 y 2 se refieren a cualquier sección normal a la dirección del flujo.

Trabajo mecánico en flujo estacionario
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


En el tema 2 vimos que el máximo trabajo mecánico realizado por un sistema cerrado cuando se desplaza su frontera, en ausencia de otros efectos, viene dado por:

.. math::

   \partial W = -p dV

Esto permite evaluar tales interacciones trabajo, independientemente del conocimiento de la interacción calor y de los cambios en la energía del sistema, que también tengan lugar en el proceso. Sería útil tener una expresión análoga para el máximo trabajo al eje realizado por un sistema durante un proceso de flujo estacionario. En el mejor de los casos, la ecuación resultante debería incluir variables independientes que sean características del sistema y conduzcan ellas mismas a la evaluación del trabajo.

Hay dos métodos de análisis que conducen a una forma deseable de la ecuación para el trabajo mecánico en régimen estacionario durante un proceso sin fricción. Él más cortojfle éstos implica la aplicación de un balance de energía como sistema cerrado y un balance de energía como sistema abierto sobre una cantidad diferencial de masa que pasa a través del sistema en régimen estacionario. El segundo método está basado en un balance de las fuerzas que actúan sobre un elemento de fluido dentro del sistema en flujo estacionario. A continuación analizamos el primero de estos métodos.

Consideremos un observador situado en el exterior de un sistema de flujo estacionario que realiza el balance de energía en un volumen de control, arbitrariamente elegido, en tanto la masa va desde la entrada a la salida.

De acuerdo con la ecuación (4.11), el balance de energía en un sistema en régimen_esta-cionario. sobre el volumen de control por unidad de masa que atraviesa un elemento diferencial de volumen de control, está dada por:

.. math::

   \partial q + \partial w_x = du + d(pv) + d(ec) + d(ep)

si despreciamos otras formas dé energía. (Esto no restringe el resultado final, como ya veremos). Podemos considerar otro punto de vista igualmente válido. Supongamos que otro observador viaja sobre el elemento de masa a través del sistema en flujo estacionario desde la entrada a la salida. En este caso el sistema será la unidad de masa de control, y no el volumen de control, por lo que es válido un análisis como sistema cerrado. Si un elemento de masa experimenta un
cambio sin fricción, el balance de energía sobre la unidad de masa está dado por:

.. math::

   \partial q - pdv = du
   
De nuevo se desprecian otras formas de energía, así como otras formas de trabajo. Los cambios en las energías cinética y potencial no son notados por el observador que viaja con el sistema. En ambas ecuaciones, (4.13) y (4.14), 6q representa la interacción calor entre el medio ambiente y el sistema (unidad de masa) cuando éste pasa a través del dispositivo en flujo estacionario. Eliminando 6qe ntre (4.13) y (4.14) y despejendo 6wx obtenemos:

.. math::
   
   \partial w_x &= d(pv) + d(ec) + d(ep) - pdv \\
    &= vdp + d(ec)+ d(ep)


Para un dispositivo con flujo estacionario, el trabajo mecánico sin fricción sobre la base de la unidad de masa se convierte en:

.. math::

   w_x = \int vdp + \Delta e_c + \Delta e_p

El alumno debe distinguir cuidadosamente entre la ecuación del trabajo para sistemas cerrados y para sistemas en flujo estacionario. La confusión nace, frecuentemente, de la semejanza entre Jpdv y J vdp. Si los cambios en energía potencial y cinética son despreciables, la ecuación

.. math::

   w_x = \int v dp

Trazando el proceso sobre un diagrama p v, se puede distinguir fácilmente entre aquellas dos expresiones de trabajo en función de las áreas sobre el diagrama.
