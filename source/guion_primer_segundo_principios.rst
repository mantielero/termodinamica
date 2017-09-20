Primer y Segundo Principios Aplicados a Sistemas Abiertos
=========================================================

(Antonio Sánchez Sánchez)


Introducción
------------

El desarrollo de la termodinámica clásica está ligado, fundamentalmente, al estudio de sistemas cerrados, esto es, sistemas que constan de una cantidad de materia constante. Sin embargo, a veces, como sistema de estudio se elige la cantidad de materia que en cada instante hay en el interior de un recinto dado, limitado por una frontera constituida por paredes en parte físicas (reales) y en parte imaginarias. Estos últimos permiten el flujo de masa a través de las paredes imaginarias, es decir, son sistemas abiertos.

Estos sistemas abiertos suelen ser los de mayor interés práctico, pues facilitan el estudio de las instalaciones y procesos utilizados en el manejo de la energía, cuyo análisis es el objeto de la Termodinámica Aplicada. Entre estos procesos e instalaciones se pueden citar: el flujo de fluidos a través de conductos, válvulas de estrangulación, compresores, turbinas, cambiadores de calor, etc.

La ampliación de la metodología seguida en el estudio de sistemas cerrados a sistemas abiertos se produce con bastante proximidad histórica. La primera formulación explícita del primer principio, como tal, se da alrededor de 1850 (Clausius, Kelvin y Rankine) y el primero en ofrecer una formulación de la primera ley para sistemas abiertos fue Gustav Zenner como parte de su análisis sobre sistemas de flujo que funcionan en régimen estacionario, publicado en su tratado sobre termodinámica técnica en 1859. Respecto a esta cuetión del desarrollo histórico de estas ideas, es interesante la contribución de A. Bajan^*\
Para el estudio de los sistemas abiertos, como ya vimos al considerar la clasificación de sistemas, se utiliza el denominado volumen de control: cualquier región definida del espacio y limitada por una superficie (superficie de control) real o imaginaria y que puede ser variable en forma y tamaño, así como debe permitir a su través el flujo de materia y energía.

El flujo de materia se define como aquella condición de desplazamiento del fluido en la que un elemento fluido puede considerarse como un sistema cerrado limitado por una superficie definida durante un cierto tiempo. La condición de flujo de materia no se da cuando una sustancia se difunde a través de otra.

En lo que sigue realizamos la aplicación de los principios primero y segundo a este tipo de sistemas. Es importante destacar que, a fin de hacer aplicables los razonamientos de la termodinámica a estos sistemas, es preciso considerar en ellos la hípótesis de equilibrio termodinámico local.

(*)Vide A. Bejan Advanced Engineering Thermodynamics 1988 pp. 5, 30 - 38


FIGURA A MANO EN EL BORDE


Al aplicar los conceptos de la termodinámica a un sistema abierto, es preciso suponer que en el sistema se cumple la condición de equilibrio local. Es decir, puesto que en un sistema abierto, aún trabajando en régimen estacionario, nos vamos a encontrar con un conjunto de valores de las correspondientes magnitudes en cada localización, distinto del que se presentará "en otra, se tendrán que definir las condiciones que deben cumplirse en cada punto para poder asignar un valor a estas magnitudes que tengan sentido termodinámico.

Para ello, recuérdese que cuando hablamos de un punto en un sistema abierto, de hecho nos estamos refiriendo a un elemento de volumen pequeño en valor absoluto, pero grande respecto al recorrido libre medio de las moléculas que integran el sistema, de forma que el elemento de volumen contenga un gran número de moléculas.

Al considerar que podemos asignar un valor determinado a las propiedades termodinámicas en un punto del sistema, estamos considerando que, si se aislara la masa contenida en ese elemento de volumen del conjunto que integra el sietema abierto, las propiedades de este elemento de volumen no se alteran con el tiempo. Recordemos que este es el criterio seguido para que un 
sistema esté en equilibrio-termodinámico. Por otro lado, para poder considerar que la transformación es cuasiestática, otra característica que tiene que darse en el valor de las propiedades termodinámicas de dos elementos de masa próximos de los que integran el contenido del volumen de control, es que la variación del valor de estas propiedades sea muy pequeña frente al valor real de las mismas en la zona considerada. Si estas dos condiciones se cumplen, puede decirse que en el sistema se dan las condiciones del equilibrio termodinámico local en todos los puntos del mismo.

En el estudio que realicemos se supondrá, en general, que se cumplen estas condiciones.

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

   \dot{m}_\Omega = 

(ya que se considera positiva la masa que entra) en la que :math:`\dot{m}` representa la velocidad a la que el volumen limitado por :math:`\Omega` gana masa, :math:`\textbf{n}` es un vector unitario normal al área de la superficie :math:`a_k` en la que la velocidad es :math:`\textbf{V_k}` y :math:`\textbf{\rho_k}` es la densidad del fluido en :math:`a_k`.

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

   \sum_k \textbf{V_k} \cdot \textbf{n} a_k \rho_k = 0
   
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

Ecuación del segundo principio para sistemas abiertos
-----------------------------------------------------

De manera análoga a como anteriormente hemos procedido con el primer principio de la termodinámica, en esta sección haremos una deducción de la aplicación del segundo principio de la temodinámica a sistemas abiertos.

De acuerdo con (3.18), la variación de entropía de un sistema cerrado que experimenta una evolución elemental vendrá dada por:

.. math::

   dS = \frac{\partial Q}{T} + \partial \sigma

y para un proceso finito:

.. math::

   S_2-S_1 = \frac{Q_{12}}{T} + \sigma_{12}

A continuación procederemos a deducir la aplicabilidad de esta ecuación a un sistema abierto, para lo que seguiremos un método análogo al utilizado en la deducción de la ecuación del primer principio para este tipo de sistemas.


Instante t	Instante t -f At

Masa del sistema = m< + Sme	Masa del sistema	+ ¿m.

Entropía del sistema = St + se Sme	Entropía del sistema = Sj+a< + s» 4m»

Figura 4.3 Esquema para la deducción de la ecuación del segundo principio aplicada a un sistema abierto.

En el instante t nuestro sistema está integrado por la masa contenida en el volumen de control, delimitado por la línea a trazos, rnj, y la contenida en el volumen rayado, Sme.

Transcurrido el intervalo de tiempo At, durante el que la masa Sme se ha introducido ya en el volumen de control y de él ha salido la masa ím„ el sistema a considerar (instante t -f At) es el constituido por la masa en el interior del volumen de control y 6ms

Durante el intervalo de tiempo considerado se supone que se produce una interacción con el medio ambiente en la que se transfieren al volumen de control una cierta cantidad de calor SQi y un trabajo SWX.

Como se indica en la figura 4.3, St y St+At son los valores de la entropía de la masa del volumen de control en los instantes í y i + Ai respectivamente. Si es Si la entropía del sistema en el instante í y S2 la del sistema en el instante í + Ai, tendremos:

.. math::

   S_1 &= S_t + s_e \partial m_e\\
   S_2 &= S_{t+\Delta t}+ s_s \partial m_s

Así pues, llevando estas expresiones a /4.17) obtendremos:

.. math::

   S_{t+\Delta t} - S_t+s_s \partial m_s -s_e \partial m_e = \frac{\partial Q_i}{T_i} + \partial \sigma_{VC}

En el caso que estamos considerando, hemos de tener claro que SQi y son, respectivamente, los valores de la cantidad de calor que a través de las fronteras impermeables recibe el sistema y la temperatura de la frontera del sistema por donde se produce la transferencia de calor. Si esta transferencia de calor tiene lugar en más de un punto de la frontera habrá que considerar el sumatorio correspondiente.

Considerando el cambio por unidad de tiempo, tendremos:

.. math::
 
   \frac{\partial \sigma_{VC}}{\Delta t} = \frac{S_{t+\Delta t}-S_t}{\Delta t} + s_s \frac{\partial m_s}{\Delta t} - s_e \frac{\partial m_e}{\Delta t} - \sum_i \frac{\frac{\partial Q_i}{\Delta t}}{T_i}
  
En el límite Ai —> 0 y suponiendo múltiples entradas y salidas:

.. math::

   \dot{\sigma}_{VC} = \sum_s s \dot{m}_s - \sum_s \dot{m}_e - \sum_i \frac{\dot{Q}_i}{T_i}

La ecuación (4.18) es la ecuación del segundo principio para sistemas abiertos en régimen no estacionario. El término de producción de entropía que aparece en ella recoge todas las irreversibilidades existentes en el interior del volumen de control.

Si consideramos un proceso estacionario, Svc = 0,;y de (4.18) deducimos:

.. math::


   \dot{\sigma}_{VC} = \sum_s s \dot{m}_s - \sum_s \dot{m}_e - \sum_i \frac{\dot{Q}_i}{T_i}

y si además el proceso es reversible, :math:`\dot{\sigma}_{VC} = 0`,

.. math::

   \sum_i \frac{\dot{Q}_i}{T_i} = \sum_s s \dot{m}_s - \sum_s s \dot{m}_e

es decir, en un proceso estacionario y reversible, el flujo de entropía debido a la transferencia de calor en un sistema abierto es igual al flujo neto de entropía debido al flujo másico.

De (4.20) obtenemos que para un proceso que cumpla las condiciones anteriores y además sea adiabático:

.. math::

   \sum_s s \dot{m}_s = \sum_s s \dot{m}_e

y si sólo hubiese una corriente de entrada y una de salida:

.. math::

   s_s = s_e

Es decir, un proceso adiabático y reversible en un sistema abierto es isoentrópico.

A fin de encontrar la semejanza entre las ecuaciones deducidas de la aplicación de los principios primero y segundo, tanto a sistemas cerrados (masa de control) como a sistemas abiertos (volumen de control), expresemos la ecuación (4.18) en la forma:

.. math::

   \dot{S}_{VC} &= \frac{d}{dt} \left( m s \right)_{VC} \\
                &= \sum_i \frac{\dot{Q}_i}{T_i} + \sum_e s \dot{m}_e - \sum_s s \dot{m}_s + \dot{\sigma}_{VC}

De nuevo nos encontramos con que la variación de entropía de un volumen de control está compuesta por términos de flujo, (a), y términos de producción, crvc. En este caso, a diferencia de lo encontrado para el sistema cerrado, el ambiente no sólo actúa como un conjunto de fuentes térmicas que proporciona una determinada cantidad de calor, sino que además proporciona un intercambio de materia al que podemos asociar el correspondiente flujo de entropía	m¡


Teniendo esto en cuenta podemos expresar la producción total de entropía., como en el caso de sistemas cerados, sin más que recordar que:

.. math::

   \Delta S_{univ} = \Delta S_{sis} + \Delta S_{MA} = \sigma_t

siendo, en este caso, AS,i, el incremento de entropía del volumen de control, ASvc e ASMA el incremento de entropía del medio ambiente. La ecuación anterior se puede escribir también:

.. math::

   \dot{S}_{univ} = \dot{S}_{VC} + \dot{S}_{MA} = \dot{\sigma}_t

La expresión para Svc es la (4.22). Para calcular la variación de entropía del medio ambiente, SMA, hemos de tener en cuenta que éste podemos modelizarlo mediante un conjunto de fuentes térmicas, más las fuentes y sumideros de materia. En todo caso, el calor QFi que la fuente intercambia con el sistema será igual pero de signo contrario a Qi que como vimos es el calor desde el punto de vista del sistema, ya que el calor cedido por la fuente es recibido por el sistema y viceversa. Algo análogo podríamos decir respecto a los términos m¡ es decir, lo que es positivo para el sistema es negativo para la fuente y a la inversa. Es importante resaltar que no siempre es inmediato la modelización de las correspondientes fuentes térmicas.

Por lo tanto tendremos:

.. math::

   \dot{S}_{MA} &= \sum_i  \frac{\dot{Q}_{Fi}}{T_{F_i}} + \sum_s s \dot{m}_s - \sum_e \dot{m}_e \\
                &= -\sum_i \frac{\dot{Q}_{Fi}}{T_{F_i}} + \sum_s s \dot{m}_s - \sum_e \dot{m}_e
 
Por lo tanto, sustituyendo en (4.23), (4.22) y (4.24.a) se obtiene:7

.. math::

   \dot{S}_{univ} = \dot{\sigma}_{VC} + \sum_i \dot{Q}_i \left( \frac{1}{T_i} - \frac{1}{T_{Fi}} \right) = \dot{\sigma}_t

.. math::
 
   \dot{\sigma}_t = \dot{S}_{VC} + \sum_s s \dot{m}_s - \sum_e s \dot{m}_e - \sum_i \frac{\dot{Q}_i}{T_{Fi}}

Nos encontramos con que la producción de entropía en el proceso es debida a los fenómenos <)isipativos que se producen en el volumen de control, más la irreversibilidad producida por la diferencia finita de temperaturas entre las fuentes térmicas y las distintas secciones de la superficie en las que se produce la transferencia de caloré.

Magnitudes de remanso
---------------------

Definimos las magnitudes de remanso como las magnitudes termodinámicas que se obtendrían decelerando el fluido desde la velocidad V hasta el reposo en las siguientes condiciones:

a)	estacionariamente
b)	sin fuerzas músicasni de viscosidad ff :

f. ■
/

No se consideran posibles efectos disipativos debido al flujo de materia en las mismas secciones de entrada o salida.
Fuerzas músicas son aquellas proporcionales a la masa como las fuerzas gravitatorias y las fuerzas de inercia dabidas al movimiento del sistema de referencia

Primer y segundo principios aplicados a sistemas abiertos
11

c-i/A ,

c)	adiabáticamente (ríV .
d)	sin paredes móviles en el volumen de control f	J

Teniendo es cuenta estas condiciones y las ecuaciones (4.8.b) y (4.21), obtenemos:

/■ kyw'n -hr.í
\\	A.--'"'
>V© o®
f y
j/lííCtja rjbv
iJ-	''UysA'A2~	suLst^dh	-

donde el subídice Q_denata magnitud de remenso. '	■

—- — --------------------------- í2vy ,

Si la sustancia de trabajo es un gas perfecto, como para"7estas sustancias h — c,,T. de la primera de las igualdades de (4.26) se obtiene la relación entre la temperatura de remanso y la temperatura estática; esto es:

(4.27)
A 'Vw -o
Ctr~
C'irli	V/''tAS'0'/ (AA.M

La segunda de las igualdades se reduce a:

í i- -	-•-T° ».-»»

r-'T l ¿ fc*
ÁM ii	!
50 = S
c„ ln ^ — E ln — = 0
(4.28)

trata de una sustancia incompresible (un líquida por ejemplo), gualdades (4.26) se obtiene:
segunda de las

f h ¿fa
As = c ln ^ = 0
Ì , ' » vu)l


Ij T0 = fJJ	(4.29)

ya que para este modelo de sustancias la variación de entropía sólo es función de la temperatura [ver (3.29)].
Al ser la temperatura de remanso igual a la estática, de (4.26) y de la definición de entalpia, h = u + pv, obtenemos:
l Po = P+ ¿/>V2	(4.30)

Hay que señalar que las expresiónes (4.27) a (4.30) sólo son válidas para los modelos de sustancias señalados. Para cualquier otro comportamiento de las sustancias, habrá que resolver las ecuaciones (4.26) junto con la ecuación térmica de estado correspondiente a la sustancia particular.

Análisis de turbinas, compresores, difusores y toberas

Vamos ahora a analizar una serie de dispositivos que suponemos funcionan en régimen estacionario y que sólo tienen una corriente de entrada y otra de salida. Para ellos será de aplicación la ecuación (4.11):	__q	¿JPyk,

A
q +(«y= ht
h
te

Suponiendo despreciable la variación de energía potencial gravitatoria y la interacción con otros campos de fuerzas, la entalpia total coincide con la entalpia de remanso, ht = h0, pudiéndose escribir la última ecuación en la forma:

q + wx = h0¡ - h0c
(4.31)

12

Primer y segundo principios aplicados a sistemas abiertos. Entropía

Turbina
^^^^^^^

Una turbina es un dispositivo para obtener trabajo de una corriente fluida. En ella el paso del fluido es tan rápido y el área efectiva para la transferencia de calor es tan pequeña que, en primera aproximación, podemos suponer que la turbina es un dispositivo adiabática, esto es, en ella q = 0, por lo que, de (4.31), el balance energético para una turbina se reduce a:
wx = h0l - hQt	(4.32.a)

Si suponemos, además, que la variación de velocidad es despreciable, la ecuación anterior queda:
wx = ha — he	(4.32.b)

Compresor
^^^^^^^^^

Un compresor es un dispositivo que se utiliza para incrementar la presión de un fluido. En este dispositivo se entraga trabajo al fluido y se produce un incremento de presión en el mismo. Si suponemos transformación adiabática y en régimen estacionario, al igual que en la turbina, podremos escribir:
wx = hQ¡ - h0c	(4.33.a)
y si V8 ~ Ve:
wx — ha — he	(4.33.b)

Difusor y Tobera
^^^^^^^^^^^^^^^^

Los difusores y toberas son elementos sin partes móviles utilizados en las instalaciones que funcionan con fluidos y en las que se quiere o bien incrementar la presión a expensas, fundamentalmente, de la energía cinética (compresión dinámica), difusor, o bien incrementar la velocidad expansionando el fluido (expansión dinámica), tobera.

En ambos casos, tanto q como wx son nulos, por lo que:

i................... y2	y2 \
I h0, = h0e	—*	h3 +	= he + j	(4-34)

Si la sustancia de trabajo es un gas perfecto, como h — u + pv, sustituyendo en (4.34):

Aec = ui + (pv)i - «2 - (pv)2
= cv(T\ — T-¡) — R (Ti - r2) = cp (Ti - T2) )

En esta última ecuación vemos que, en estos dispositivos; la contribución de la energía interna al cambio de energía cinética es prácticamente el doble que la contribución correspondiente al trabajo de flujo.
Rendimiento adiabático de estos dispositivos.

Podemos decir que el rendimiento de una instalación, de una máquina y en general de cualquier dispositivo no es otra cosa que una comparación entre la actuación real de ese dispositivo bajo ciertas condiciones y la actuación que tendría lugar en un proceso ideal. En esta

Primer y segundo principios aplicados a sistemas abiertos

13

condición de idealidad es donde interviene la segunda ley, ya que lo que vamos a tomar como referencia de idealidad es el comportamiento isoentrópico del dispositivo. Así, cuanto más se acerque la instalación al comportamiento reversible más se acerca el rendimiento al valor unidad.

Compresor

o2

Turbina
^^^^^^^

En la figura 4.4 representamos en un diagrama T — s la evolución tanto de un compresor como de una turbina. A partir de ese diagrama queda claro que los rendimientos de un compresor y de una turbina se definen como:

wis
o2r
o2i
Ve =
Wreal
hpn, ~ fi'Oi bo2r
Vt =
Wreal
Wi.

Figura 4.4Esquema de la evolución del fluido en un compresor y en una turbina.

hp2r hQl hou, ~ h0l
(4.35)
(4.36)

Para un tobera, definimos el rendimiento adiabático como el cociente entre la energía cinética real de la corriente de salida y la energía cinética que tendría esa corriente si el proceso en la tobera fuese isoentrópico. Esto es:

_	vl
”T ~ VV2|2,

Este rendimiento lo ponemos en función de las entalpias de remanso a la entrada de la tobera y de la entalpia estática a la salida sin más que despejar de (4.34) los términos de energía cinética a la salida quedándonos:

Vt =
boi b*2 ho i ^2*

El rendimiento adiabático de un difusor lo definimos en la forma:

2¡ h\
Vd =
ho2r h\
(4.37)
(4.38)

siendo (2') el estado que se alcanzaría si llevásemos el fluido, isoentrópicamente, desde las condiciones de presión y temperatura de entrada hasta alcanzar la presión de remanso de salida.
Dispositivos de estrangulación.

Sistemas de flujo estacionario tales como una turbina Ó'una tobera producen, como hemos dicho, trabajo o un incremento de la energía cinética cuando el fluido pasa a través de ellos. Concomitante con estos efectos hay una caída de presión. Esta caída de presión debe controlarse en las instalaciones y el control se consigue insertando en el sistema de flujo otra componente denominada artificio de estrangulación. El proceso de estrangulación se utiliza para fines distintos de los meramente de control.j El efecto principal conseguido es una caída significativa de \ Impresión sin interacción de trabajo ni variación apreciable de las energías cinética o potencial. /El flujo a través de restricciones tales como una válvula o un tapón poroso, cumplen por completo

14

Primer y segundo principios aplicados a sistemas abiertos. Entropía

las condiciones requeridas para este tipo de proceso. En la figura 4.5 se muestra una válvula de estrangulación.

Figura 4.5Esquema de una válvula.

Aunque la velocidad puede ser muy alta en la región de la restricción, medidas realizadas corriente-arriba y corriente-abajo de la restricción real indican que el cambio en la velocidad, y por tanto en energía cinética, a través de la válvula es muy pequeño. Como el volumen de control es rígido y no hay presente ningún eje giratorio, no hay implicada ninguna interacción trabajo

Así pues, con las consideraciones anteriores, el balance energético para el flujo estacionario a través de una válvula de estrangulación queda reducido a:

q — hi — h\

Sin embargo, en la mayoría de las aplicaciones, o el dispositivo de estrangulación está asilado o la transferencia de calor es despreciable, por lo que para este proceso el cambio de entalpia es nulo; esto es:

/12 = h\

Esto no quiere decir que la entalpia sea constante durante el proceso, sino que la entalpia del flujo en la sección de entrada y en la sección de salida son las mismas. Como ejemplos de sistemas sencillos que utilizan este efecto podrían citarse un grifo de agua, una válvula de expansión de un figorífico, etc. En todos estos dispositivos tiene lugar un efecto de estrangulación o expansión de Joule-Thomson.

TEMA 5 - COMBINACION DEL PRIMER Y SEGUNDO PRINCIPIO: EXERGIA.
=============================================================

Antonio Sánchez Sánchez.

Pablo de Assas Martínez de Morentin.

5. PRINCIPIOS PRIMERO Y SEGUNDO APLICADOS A SISTEMAS ABIERTOS::

   5.1.- Introducción.
   5.1.1.	- Relación entre la variación de propiedades en un sistema cerrado y un sistema abierto.
   5.1.2.	- Conservación de la masa..
   5.2.	- Formulación del primer principio vara sistemas abiertos.
   5.2.1.	-Procesos de flujo estacionario.
   5.2.2.	-Trabajo mecánico en flujo estacionario.
   5.3.	- Ecuación del sesundo principio para sistemas abiertos.
   5.4.	- Magnitudes de remanso.
   5.5.	- Análisis de turbinas, bombas, compresores, difusores y toberas.
   5.5.1.	- Turbina.
   5.5.2.	- Compresor y bomba.
   5.5.3.	- Difusor y Tobera.
   5.5.4.	-Rendimiento adiabático de estos dispositivos. 
   5.5.5- Dispositivos de estrangulación.

Bibliografía
------------

Qengel, Yunus A. y M.A. Boles. TERMODINÁMICA Tomo I) Me GRAW-HILL. 1996 México Capitulo IV, VI y VII.
   
Wark. K. TERMODINÁMICA. Me GRAW-HILL. 1991 México Capítulos VII y VIII.


Introducción
------------

Como se vio en el tema 3, la implicación más técnica e ingenieril de los dos principios de la termodinámica estudiados hasta ahora, primer y segundo principio, es la deducción de la íntima relación existente entre la generación de entropía y la pérdiada de capacidad de realizar trabajo. Esta relación es fundamental ya que la Termodinámica Técnica es el resultado de nuestro interés en el trabajo como valor de cambio (mercancía), es decir: obtención de trabajo de diferentes fuentes energéticas y utilización al máximo del trabajo ya en nuestro poder.

A nivel teórico, el concepto de ’’trabajo disponible destruido” nos recuerda que los principios primero y segundo de la termodinámica van conjuntos, a pesar de que la tradición en la resolución de problemas nos puede inducir a pensar lo contrario. 

El concepto que forma el objetivo de este tema tjene su origen en la invocación simultánea de los dos principios ya mencionados. 

A menudo, este procedimiento tiende a ser obscurecido con etiquetas tales como ’’análisis según el segundo principio” que muy frecuentemente se pone para la evaluación del trabajo disponoble perdido y para la minimización de la generación de entropía. No obstante, entendido en el sentido señalado de conjunción de los dos principios, incluso el término ’’análisis según el segundo principio” puede ser efectivo para recordar que el segundo principio debe formar parte del análisis enegético y en muchos casos ser previo en su utilización al primero.

El tema se inicia con el análisis de sistemas cerrados, obteniendo la expresión general del trabajo útil reversible y a partir de él se define la exergía. Después se hace aplicación de las expresiones generales de los sistemas cerrados a sustancias incompresibles y a gases perfectos. A continuación se hace una aplicación de la ecuación del trabajo útil reversible a procesos de flujo y posteriormente se da la definición y algunas aplicaciones de lo que llamaremos rendimiento exergético. El tema se termina con la aplicación a los ciclos termodinámicos.

En todo lo que sigue, conviene destacar:

|¡a) Al exterior inmediato al sistema lo denominaremos, indistintamente, medio ambiente, atmósfera o entorno.
1 b) Que este medio ambiente lo consideraremos infinito y que sus propiedades térmicas
i (presión, volumen y temperatura) no se verán alteradas por los interacambios ener-
j) géticos (calor y/o trabajo) con el sistema en consideración.
1c) También hay que decir que el equiljjj¿& al que se hace referencia en todo el tema es , sólo el equilibrio térmico v mecánico,-dejando el equilibrio material o químico, por
I	intercambio de especies, para el tema 9. Por esta razón el estado de equilibrio con el
II	medio ambiente se denomina. estatlo”müeff(rrestrin.gido en el que:

2

Combinación del primer y segundo principio: exergía

V = O y z = 0
----—---J

Balance de exergía para sistemas cerrados
-----------------------------------------

Consideremos un sistema cerrado de propiedades uniformes que evoluciona intercambiando calor con un cierto número de fuentes térmicas a temperaturas (i = 0,1,. ..n), y entre las que se encuentra la atmósfera. Durante la evolución el exterior comunica al sistema un trabajo bW. Una posible interacción mecánica realizada por la atmósfera, en tanto que ésta actúe como depósito mecánico, es el trabajo -p0dV.*

El primer principio aplicado al sistema nos proporciona:

n ------' f
Y^6Qt + 6W = dE con E = U + Em	(5.1)

Si calculamos la producción de entropía habida en la evolución del sistema obtendremos:

n
bcji — dSsis ^ ^ -------- i=0
(5.2)

donde bot > 0 representa la producción de entropía e incluye no sólo las irreversibilidades interiores y en la frontera del sistema, sino también, el hecho de que cada bQi esté siendo cedido desde una fuente a una temperatura que en general no es la temperatura del sistema.

De siempre el interés de la ingeniería es realizar cambios sobre los sistemas que lleven de forma coherente a incrementar el trabajo obtenido o a disminuir el trabajo consumido. Esto nos lleva a considerar la posibilidad de cambiar el funcionamiento interno del sistema para poder minimizar el trabajo comunicado al mismo. Para conseguir este efecto, supuestos definidos los estados extremos del proceso y teniendo en cuenta (5.1), se tendrá que cambiar alguno de los bQi si se quiere modificar bW. Supongamos que es la transferencia de calor con la atmósfera, bQ0, la única interacción energética que varía en tanto que bW se minimiza. Es decir: suponemos que a excepción de bQ0, el resto de las interacciones térmicas vienen fijadas por diseño y que
Ísólo ese bQ0 es flotante de cara a equilibrar los cambios habidos en bW. La elección de bQ0 como la interacción ’’flotante” como consecuencia del cambio en el diseño, es consistente cop el papel que tradicionalmente se le asigna al calor cedido a la atmósfera en el diseño de sistemas de potencia y refrigeración.

Si se elimina bQ0 entre las ecuaciones (5.1) y (5.2) queda:

*Nota: es obvio que estamos tratando con velocidades de desplazamiento de la frontera del sistema, v, pequeñas frente a la velocidad del sonido en la atmósfera de modo que la sobrepresión generada por ese desplazamiento, del orden de p0v2, es muy pequeña frente a p0 si v < a (siendo a la velocidad local del sonido), esto es e°v ‘2 < 1
/ — \ P° y (p ~ Po)dV = ^-------J p0dV -C p0dV, por lo que quitamos ese término del trabajo de desplazamiento de la
atmósfera.

Combinación del primer y segundo principio: exergía

3
dE-Y, éQi ~SW = T0dSsis - Y ^SQt ~ To So
i=1
¿=1
Ti
Sí
i
!
y despejando el trabajo:
M
Vi
,¿%Md(E~T°s^
\SQi (1-^) +T0Sot
(5.3)

De acuerdo con el segundo principio ^ cr( > 0 por lo tanto los otros dos términos del segundo miembro representan algebraicamente un b'mite inferior para SW. Este límite inferior se alcanza cuando el sistema evoluciona de manera que no haya producción de entropía en el proceso (esto es, la variación de entropía del universo sea nula). Así pues, identificamos los dos primeros
términos del segundo miembro como el trabajo Reversible coiqunicado al sistema; esto es:

mxd<av ¿>C	^
i - óVf L
¡swTI
d{E - T0S)sis -
n	/ \ T
E««.)1-F
i=1	v 1
h^/'o	w£<.
(5.4)
o 'Usoh. J
I  ------------ —*	. (I _	0

Una cuestión que surge en conexión con esto último es si todo el trabajo reversible es trabajo útil o no. La respuesta depende de si la atmósfera, como depósito mecánico, es parte del entorno y de si el sistema experimenta un cambio de volumen comprimiéndose a favor de (o expandiéndose contra) la misma. En el caso en que el depósito mecánico atmosférico intercambie trabajo con el sistema, la parte de SW que es transferida por la atmósfera es (—p0dVj mientras
que el resto loRonstituye el trabajo útil’esto ps de (5.3) se tendrá:

y*
j
¿o—<_A c Ja
l
qL^ ¿fl ‘VtZV yj—*—« U p.1—effo'	VI /•
SWútil, real = 6W+ PodV
= d(E + p0V - T0S)sis -YsQí(1~y)+T° 6at Teniendo en cuenta (5.4) podemos poner:

¿=i
(5.5)
«W’ütü, real — ^W^útil, rev H” T0 ¿(71

ecuación que puede escribirse en la forma:

¿Wútil, real ^^útil, rev — T0

donde se ha puesto que:

: swúül rev = d(E + PoV - TaS)sls - Y*Qi (l - y)
Así pues:
(5.6)
(5.7)
^W^real ^b^rev— ^f^útil, real	rev
---1,1,1.	"" v

representa eltra.ba.jo perdido y la ecuación (5.6) es la expresión matemática del (teorema de Gouy-Stodola o del trabajo perdido que puede enunciarse de la siguiente forma: cuando

4

Combinación del primer y segundo principio: exergía

un sistema evoluciona irreversiblemente destruye trabajo a un ritmo que es proporcional a la generación de entropía habida en el proceso. Al producto T0 6<rt se le conoce con el nombre de irreversibilidad 61 (6i por unidad de masa); al igual que el calor y el trabajo, depende del camino seguido por la evolución, esto es, no es una propiedad del sistema ni tampoco del conjunto sistema-medio ambiente. .......

Si se quiere saber cuál es el trabajo útil reversible que es necesario comunicar a una masa de control (sistema cerrado) para llevarla desde las condiciones de equilibrio termomecánico con la atmósfera (estado muerto restringido) hasta unas condiciones de temperatura y presión determinadas ( y distintas de las de la atmósfera) en un proceso en el que la única fuente térmica con la que el sistema pueda interactuar es la atmósfera, se hace aplicación de (5.7) obteniéndose:
\tv -	= Inútil, rev = E - E0 + Po(V - Voy- T0(S - So) [ '	(5.8.a)
A este trabajo, que es el mínimo necesario para conseguir un estado termodinámico determinado (T, p) a partir de las condiciones del medio ambiente se le llama exergía, $(*L. Si se considera la unidad de masa, la exergía específica^ = «h/m/vendrá expresada por:

<í> = (e - u0) + p0(v - vQ) - T0(s - s0)	(5.8.b)

Con esta definición dada de la exergía, la ecuación (5.7) se puede escribir en la forma

1 - Ti)	(5-9)

Así pues, el trabajo útil comunicado a un sistema cuando evoluciona desde un estado de equilibrio 1 a otro 2 , también de equilibrio, y en su evolución intercambia calor con i fuentes térmicas, puede expresarse en la forma:

(Wútil,real = (*2-*l)-¿Q¿ (l ~	+ l>t	(5.10.a)

Esta ecuación (5.10.a) podemos reescribirla poniendo:

j¡A$ = $2 - $1 = Wútil, real + Qi (X “	~	(5.10.b)
/__---------.------------ ------* ~	—------- _ J

ecuación que no es sino la expresión del balance de exergía para una masa de control; balance que nos indica que la variación de exergía en el sistema cerrado proviene de la exergía que se introduce al sistema con el trabajo comunicado al sistema,	reai, la que se introduce con
í*') Es importante señalar que la práctica totalidad de los autores definen la exergía como el trabajo máximo que puede obtenerse de un sistema en un determinado estado termodinámico cuando, sin producción de entropía y sin otra fuente térmica distinta de la atmósfera, se le lleva al equilibrio con el medio ambiente. Sin embargo aquí se ha cambiado la definición para que haya coherencia con el criterio de signos atribuido al trabajo en el primer principio. También es importante señalar que lo que aquí se ha denominado exergía, algunos autores de habla inglesa (norteamericanos fundamentalmente) lo denominan disponibilidad.
Wútil, rev =<*($)- Y.*®'
¿=1

Combinación del primer y segundo principio: exergia

5

el calor que se le transfiere al sistema,	(1 — j (téngase en cuenta que este término

i=i '	1'

representa el trabajo máximo que se podría obtener con la mencionada interacción mediante máquinas de Carnot), menos la que se destruye por irreversibilidades tanto internas al sistema como por las existentes entre el sistema y la atmósfera, T0ot.
La exergia, tal como se ha definido, es una función de estado del conjunto sistema-ambiente, y no del sistema sólo; esto es, dados dos estados de equilibrio de un sistema y una atmósfera, la variación de la exergia no depende del camino que el sistema recorra para pasar de un estado de equilibrio a otro. Como el medio ambiente viene caracterizado por su presión y temperatura (T0, p0), es lógico que todas las propiedades termodinámicas que intervienen en la evaluación de la exergia, <f>, vengan expresadas en función de esas variables. Así pues, a partir de (5.8.b) y considerando un sistema simple, podemos escribir:

d(j> — de + p0 dv — T0 ds
(5.11)
Vil
1

Vamos a hacer aplicación de (5.11) a dos tipos de sustancias:

A)	Sustancias incompresibles a temperatura T y presión p tales que T / T0 y p / p0.
B)	Gases perfectos, que al igual que en el caso anterior, su presión y temperatura son distintas a la del medio ambiente.
| A) Sustancias incompresibles

i--.__...1~T2,	—i	...

Para una sustancia incompresible fdu = c dT( dv — 0 y jds = c — por lo que la ecuación (5.11), una vez integrada, se reduce a:

4>
cT0
T	T
—	1 - ln —
O	1 O
i, #T)
(5.12)

La exergia de una sustancia incompresible es sólo función de la temperatura y referida a cT0, ecuación (5.12), es independiente de cuál sea la sustancia concreta.

(f)	T

Si representamos <j> = —— en función de —

o	lo

obtenemos la curva de la Fig 5.1 en la que se puede ver que una sustancia incompresible puede servir como fuente de trabajo en tanto que su temperatura sea distinta de la temperatura de la atmósfera. Efectivamente, un sistema caliente de masa fija puede servir como fuente de alta a un motor térmico cíclico que ceda calor a la atmósfera (punto T0) obteniéndose una cantidad de trabajo. Igualmente de una masa fría también puede obtenerse trabajo sin más que considerar a ésta como el foco frío de un motor térmico, siendo la atmósfera el foco caliente.

'	¿LJ

B) Gases perfectos

i
< t
Té

>1

6

Combinación del primer y segundo principio: exergia

Para gases perfectos la dependencia de la energía interna, del volumen específico y de la entropía con la temperatura y la presión viene dada por las expresiones siguientes:

du = CydT ; dv — Rd
T
dT ndp P
ds — Cp R

con lo que 4> vendrá dada por: <b ~ jn -j ) t- tio i j - M,}

; v-Ai/f /f= cCurì Jal. Vf 1
/ rp	'10	'
<t> = cvT0 ( £ - 1 - 7ln Jr ) + RT0	- 1 + ln ?-
T0
T0 P
Po

Expresión que podemos adimensionalizar con cvT0 obteniendo:

- r,/
(5.13.a)
■c
-4> =	+(7-l)(f--l+ln-^-
\T0	T0)	\T0 p	p0

(5.13.b)

-De (5.13.a) se ve que, para un gas perfecto, la exergia depende de la presión y temperatura. Puede comprobarse que <¡> (o <f>) dada por (5.13.a) tiene un mínimo en (T0, p0). También puede comprobarse que, si del estado final se tiene determinada la presión, la temperatura
correspondiente que hace „que la, exergia sea mínima,

£ J ukjL kJ T +	y ¿
ft-c. ir fa VlJ1" di. ~f AX
yttu í.Mftv

viene dada por:

______&	tr&' 'i*
JiAs-f---*—w
* &
1 — — ( 1 — ^°
-»Os*.
U
(5.14)

En la Fig 5.2 se ha representado (f) en función de — para gases perfectos cuyo y sea 1,4 ya para,

* í I	* O
0,5; 1 y 1,5.
íM't- XyC¿OiJ- od

Figura 5.2

Los mínimos indican el valor que alcanzaría la temperatura de un sistema si desde un estado inicial fijo
(—^-, —) se quisiera, para un valor de — dado, al-d o Po	Po
canzar, con el consumo mínimo de trabajo, esto es,
teniendo como única fuente térmica la atmósfera,un
estado termodinámico de equilibrio mediante un
proceso sin producción de entropía.

Po

De (5.13.b) puede verse que las jcurvas ¿ = cte en las proximidades del punto ~ = 1,

O

= 1 son elipses dadas por la ecuación:
d:L- ‘	¿i:;J
nHfi Ì.

donde las variables r yyr están definidas como:

^ 2 + 2 ^ T^	Jq-G/Jtt-ñftjr:. \Jfy£r
lt:	T
Af f îæA.
!Í	OÍu*/e*	l'X 4	¿
i;

&*-
f'A^ Jm i
w- WL ,
T

^ ^¿I :o^As> p,i*,ví-i6 eL-.í^^
ki

-7^ y?i^k¿^/s> (í ¿ ¿t/)jr
¿ufa. í&j/J..
i y A	/?

Combinación del primer y segundo principio: exergía	Av /*7^	7

Balance de exergía para sistemas de flujo. (/¿¡Yo J,
---------------------------------------------------

(s«	{ 5c£S#z ■ó. "

Para obtener el balance de exergía en sistemas dé flujo, (esto es, sistemas en los que la masa tiene una velocidad media macroscópica) se procede de manera análoga a lo hecho con los sistemas cerrados. Según vimos en el tema 4 [(4.8.a) y (4.24.b)], las ecuaciones del primer y segundo principio para sistemas abiertos en régimen no estacionario son:

r tai
d
Y Qi + w + Y(h +-¿- +9Z)™~ Y(h + y +gz) ™= ¿¡(u + E
1=0
Jm )vc
(5.15)
r:-r~£~—\ . ds
'W-cfra-t a, = — ---- ---- ::	dt
-E;|-Es™ + Es™^0
ve 1=0
(5.16)

Eliminando entre las ecuaciones (5.15) y 1(5.16), y como ht = h + — + gz, despejando
W se obtiene:

(^fÁ^jw = jt(U + Em-T0S)vc + Y(ht-Tos)m-Y(ht-Tos)^-YQi (l ~t)+To
■------ s	e	i = l '	1 '

(5.17)

A ht — T0s se le suele llamar disponibilidad de flujo*

-Jj
-'V* jj tí*-*. ííy ■
■'i	AA/ _ o-~C- '\A.	(Ajy j

Al igual que en el caso de sistemas cerrados, en lo que estamos interesados es en la potencia mecánica útil, tanto real como reversible, que hay que consumir en una evolución de un sistema de flujo no estacionario. Procediendo igual que en el apartado anterior, podremos escribir:

Wútil,real = -^(U + Em + p0V - T0S)VC + J^(/lí - T0s) m - Y(ht ~ T°S)
m
u
¿q,(i-^)+r0át	j (5.18)

habiendo desdoblado el término de la potencia mecánica en dos: potencia útil, W¿tn, y poten-
dVwr.
cia debida al hecho de que las paredes del volumen de control es deformable, — pQ-representa la potencia mecánica intercambiada con la atmósfera.

La potencia útil reversible será: d

dt ’
que
W,
útiljrev
= -(U + Em+ PoV - T0S)VC + Y(h* ~ T°s) ™ - E(/lí - r°s)
m

¿=i
Tn
(5.19)

y la ecuación (5.18) se puede escribir:
bfútil, real — fí^útil, rev 4" T0 <T¡

(5.20)

*En algunos textos a (e + p0v — T0s) le llaman disponibilidad. La disponibilidad de flujo se relaciona con ésta mediante la relación a¡ = a + v(p — p0).

8

Combinación del primer y segundo principio: exergía

Si desde las condiciones del medio ambiente (estado muerto restringido: p0, T0, v = 0 y z = 0) mediante un proceso en régimen estacionario (— = 0) y teniendo como única fuente
térmica la atmósfera (^jQi ^1 —	= 0) se quiere obtener una corriente con una velocidad,
| v, temperatura, T, presión, p y altura z determinadas, la potencia mecánica reversible útil i necesaria es siendo ip la exergía de una corriente, que se obtiene a partir de (5.19) con ^ todas las condiciones especificadas. Esto es:

<4 0 ,

OinWM-	(5.21)

Teniendo en cuenta (5.8.a), (5.18) v Í5.211 el balance de exergía para sistemas de flujo en ;égimen no estacionario puede expresarse en la forma:	. f

'k
% kns-*'
[|V> = h - hQ + — + gz - T0(s - sQ)
d$
dt
-	- VEútil, real - ^2 Q' ( 1 ~ Yf ) + To
se	i'=l
ot = 0
r; -■ '
(5.22)

Ecuación, que de manera análoga al caso de sistemas cerrados (5.10.b), nos indica que la variación de exergía de un recinto abierto proviene de la exergía neta que se introduce al recinto: a) con la masa a través de las fronteras permeables, (~	b) con el trabajo,
a través de las fronteras impermeables restando la
exergía que se destruye por irreversibilidades existentes en el proceso, irreversibilidades tanto internas al sistema como las que hay entre el sistema y el medio ambiente.
Si el proceso de flujo es estacionario, la ecuación (5.22) se reduce a:
d J l^UIl Id IlidÛd d UdVCÛ UC idO IIUIl leí dO

Inútil, real, y con el calor,	^1 -

tr
i=i
- VEútil, real -	( 1 - T~ ) + T° &t = °
Ti
(5.23)

La expresión (5.23) puede ponerse de una forma genérica:

$

obtenida	perdida	suministrada ¡	(5.24)
donde q0señala exergía. El valor de cada término habrá que asignarlo en cada caso concreto. A modo de ejemplo, supongamos la actuación de una turbina funcionando en régimen estacionario a la que se suministran m kg-s-1 de vapor en condiciones (pi, Ti), que sen de la misma en condiciones (p2, T2) y proporciona una potencia W. En este caso particular:
éx) obtenida es la potencia W
y de (5.24) se sigue que:
éx) . . .	, es mée
’ suministrada
é*) perdida = rhrjle - W =	+ T0át

Í)aq eU L- '
tsf¿, ct<A(.C*'*~	£ Jn**&	hj£*- faéU U- /¿t~Ci~ a^Jt^ /tribus
(&h	^	t*W'ys~>-	a*—'¿«+fa & c- -'V~#!iJ o sut*-	oikf)). 71.	/
*	* / |	^	I	/ l'^Cu' ¿Sifú
A 2/xJo>tfT t

Combinación del primer y segundo principio: exergía

+ 'o ¿T t e Jtv-iiofí. 4,.^_ a
t\L / ) y
* «-«wW
jr N) J 'tx -XxAÍa^-c,
^ /wc/ic/i,

¿Cómo se modificarían estas expresiones si el flujo músico de salida se utilizase en un dispositivo para calefacción saliendo del dispositivo en condiciones del ambiente (p0, T0)1.

De manera análoga, la expresión (5.lO.b) y la (5.22) una vez integrada, pueden expresarse, también, en la forma:
1 obtenida
+ ex) perdida ~ ^)
suministrada
(5.24.a)

Rendimiento exergético
----------------------

De manera análoga a como se ha hecho en el análisis energético de los sistemas donde se ha definido un rendimiento térmico o energético, en el que se relaciona la energía real consumida con la correspondiente al funcionamiento ideal, podemos definir un rendimiento exergético en la forma:
0
obtenida
?x)	• •
> sumtni
strada
Teniendo en cuenta la relación (5.24), el rendimiento exergético se puede escribir:
perdida
x ’ suministrada
(5.25)

En algunos casos, como se verá en el apartado siguiente, los rendimientos térmico y exergético están relacionados entre sí. Qué diferencia haya entre estos rendimientos se puede ver con el siguiente ejemplo. Supongamos un sistema cerrado que recibe una potencia térmica Qs de una fuente térmica a temperatura Ts y cede una potencia térmica Qu a una temperatura de utilización Tu. 

Además hay una pérdida de energía térmica hacia el medio ambiente, Qp, a través de una parte de la frontera que está a Tp.
Suponiendo un funcionamiento en régimen estacionario y que al sistema cerrado no se le transfiere energía en forma de trabajo, los balances energético y exergético (ec 5.lO.b) para el sistema son:

Qs — Qu + Qp

í*(1-£H*(1-£)+í'(1"£)+r" = 0

El balance energético dice simplemente que de la potencia térmica que recibe el sistema parte se utiliza y el resto se pierde.

Un rendimiento energético puede definirse en función de la potencia térmica utilizadáTy la suministrada, esto es:
10

Combinación del primer y segundo principio: exergía

En principio este rendimiento puede aumentarse poniendo más aislante de modo que se reduzcan las pérdidas. En el Emite de Qp = 0, el rendimiento será la unidad.
Si comparamos el balance de exergía del proceso con (5.24), se ve que se suministra exergía el calor, Qs ^1 —	, y que hay una exergía que se obtiene con la potencia térmica utilizada,
con
Qu

1------ ) i de modo que el rendimiento exergético será

Tu,
£ =
Qu 1-
To
Tu
Qs
= V
1- ^
1- ^
T
1 U
T
i- — Ts

De esta expresión se ve que es importante no sólo la energía térmica utilizada, en definitiva valores altos de g que en el límite sería la unidad, sino también la temperatura de utilización de esa energía. Así por ejemplo, suponiendo que seamos capaces de utilizar prácticamente casi toda la energía suministrada (77 ~ 1), si la temperatura a la que se utiliza esa energía Tu, es próxima a la temperatura ambiente, el rendimiento exergético tiende a cero. Dicho de otra forma, cuanto
más baja sea la temperatura de utilización del calor generado a alta temperatura, aunque se utilice íntegramente, peor es la utilización de esa energía. Desde el punió de vista de óptima utilizaciónMeJa^eneFgTarÍTrteresap€©n_k)s. valores más altos posibles de r¡, una temperatura de utilización de la energía térmica lo más próxima a la temperatura de la fuente de la que se
obtiene la energía térmica.'

ergia tei
T7
Lyu /iIzXa/,
7*2? Tc.

Por ejemplo, supongamos que para la calefacción de un gran edificio se ha de quemar un combustible. Mejor que generar vapor y comunicarlo a los radiadores, sería generar vapor y utilizarlo para producir energía eléctrica y sacar parte del vapor en una etapa intermedia para calefacción (este proceso se llama cogeneración).	..	/
_____________________________—----------/ ¿
viví- y* ____.
~57í>UAplicación a procesos cíclicos.
/

Este análisis exergético de los ciclos, aunque lo hacemos con dispositivos poco complicados, esto es, sistemas cerrados que trabajan en un número entero de ciclos, nos va servir como una introducción para el análisis posterior de procesos más complicados y detallados que puedan hacerse con ciclos de potencia y de refrigeración. El estudio lo haremos, separadamente, para motores térmicos y para bombas térmicas y máquinas refrigerantes. El ciclo trabajará entre dos fuentes térmicas. Una será siempre el ambiente y la otra estará, en cada caso, a una temperatura especificada.
Motores térmicos

Al tratarse un sistema cerrado cíclico, definido en la sección 3.2, la ecuación (5.10.a) se reduce a:

Combinación del primer y segundo principio: exergía

11
Ta > T*	¿b /	/ P. tícfió ^ ~Q
V^útil, real — Qa	T0\ TaJ	) + Tq(t — 0	(5.26)
Ti

1 3 donde Qa es el calor que el motor toma de la fuente de alta que está a una temperatura Ta. La otra, como ya se ha dicho, es el ambiente. En los motores el trabajo útil real es trabajo extraído, no suministrado, de modo que si ponemos W(,t\i, rea| = — Wmot0r en la expresión anterior, reordenándola queda en la forma:

Wmotor-Qa[l-~) +ToO = 0
(5.27)

Si se compara (5.27) con (5.24) se ve que se suministra exergía al motor con el calor que éste toma de la fuente de alta; esto es, aunque de forma no muy ortodoxa, se podría hablar del contenido de trabajo disponible en el calor transferido.

El rendimiento exergético de un motor térmico, según la expresión (5.25) es:

£ = 1
T0 o
Qa^l-
Wmotor
T
-L O
± a
(5.28)
Qa 1
T
Tn
Como
W,
motor
Qa

es el rendimiento energético del motor térmico, (77), se podrá poner para el
rendimiento exergético de un motor:

7V-Í-Á

(5.29)

¡esto es, el rendimiento exergético es el cociente entre el rendimiento térmico del motor y el rendimiento de un motor equivalente de Carnot que trabajase entre la temperatura de la fuente de alta y la temperatura del medio ambiente.
Bombas térmicas y máquinas refrigerantes

En el caso deJb.QmbasTérmlcas|, al ser éstas dispositivos que ceden una cantidad determinada { de calor (Qa será negativo) a una fuente a una temperatura Ta consumiendo un trabajo W¿t¡i, rea]
| que es el trabajo consumido en el compresor de la máquina (VE), la ecuación (5.10.a) quedará:

';'í74-
U/&T
m

ie se ve que se está calentando.

W = Qa ( 1 - ^ j + T0o
T
J- n
0
(5.30)

de la que se ve que se obtiene la exergía Qa ( 1 — — ) que es la que se suministra al sistema

El rendimiento exergético en este caso de bombas térmicas es:
12

Combinación del primer y segundo principio: exergía

£ =
w
C O Pbomba
(5.31)
siendo COPeq.ca
T
-L n.
COPeq. Carnot

el coeficiente de actuación de una bomba térmica funcionando

T - T
¿a ± o

según un ciclo de Carnot entré la temperatura del recinto a calentar (Ta) y la temperatura del medio ambiente.
Si de lo que se trata es deimáquinas refrigerantes» el calor involucrado es el que hay que extraer (Qb) del recinto a refrigerar (fuente a una temperatura TQ. Este calor es positivo para la máquina. En cuanto al trabajo útil real, también en estos dispositivos es el trabaj^ consumido
en el compresor de manera que (5.10.a), en este caso, será:

W = -Qb(l-'^)+T0a
¡	i	,	6

Como;Tb < T0, la ecuación anterior se puede escribir en la forma:

* ^
w»
id.
T»
Qb
Tb
1 - VE + T0a = 0
(5.32)
(5.33)
Qb

De esta ecuación se ve claramente que de una máquina refrigerante se obtiene exergía,
-f - 1 ) ya que Tb < T0, que es suministrada al sistema que se refrigera. Esta es la razón -^6 /
por la que de un sistema cerrado a tamperatura inferior a la del medio ambiente se puede obtener trabajo, o lo que es lo mismo, este sistema ’’frío” tiene una exergía positiva ya que se le ha dado esa exergía mientras se enfriaba.

El rendimiento exergético de un refrigerador será, pues,

£ =
Qb( Yb -1
w
COPref
(5.34)
siendo COP,
Tb
eq.C arnot
To-Tb
CO Peq. Carnot

el coeficiente de actuación de una máquina refrigerante de
Carnot qué trabajase entre las temperaturas del recinto a refrigerar (Tb) y la temperatura ambiente.
