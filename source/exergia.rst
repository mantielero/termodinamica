TEMA 5 - COMBINACION DEL PRIMER Y SEGUNDO PRINCIPIO: EXERGIA.
=============================================================

Antonio Sánchez Sánchez.

Pablo de Assas Martínez de Morentin.


Bibliografía
------------

Qengel, Yunus A. y M.A. Boles. TERMODINÁMICA Tomo I) Me GRAW-HILL. 1996 México Capitulo IV, VI y VII.
   
Wark. K. TERMODINÁMICA. Me GRAW-HILL. 1991 México Capítulos VII y VIII.

Índice::

   5.1 Introducción.
   5.1.1 Relación entre la variación de propiedades en un sistema cerrado y un sistema abierto
   5.1.2 Conservación de la masa


Introduccion
------------

Como se vio en el tema 3, la implicación más técnica e ingenieril de los dos principios de la termodinámica estudiados hasta ahora, primer y segundo principio, es la deducción de la íntima relación existente entre la generación de entropía y la pérdiada de capacidad de realizar trabajo. Esta relación es fundamental ya que la Termodinámica Técnica es el resultado de nuestro interés en el trabajo como valor de cambio (mercancía), es decir: obtención de trabajo de diferentes fuentes energéticas y utilización al máximo del trabajo ya en nuestro poder.

A nivel teórico, el concepto de ’’trabajo disponible destruido” nos recuerda que los principios primero y segundo de la termodinámica van conjuntos, a pesar de que la tradición en la resolución de problemas nos puede inducir a pensar lo contrario. El concepto que forma el objetivo de este tema tjene su origen en la invocación simultánea de los dos principios ya mencionados. A menudo, este procedimiento tiende a ser obscurecido con etiquetas tales como ’’análisis según el segundo principio” que muy frecuentemente se pone para la evaluación del trabajo disponoble perdido y para la minimización de la generación de entropía. No obstante, entendido en el sentido señalado de conjunción de los dos principios, incluso el término ’’análisis según el segundo principio” puede ser efectivo para recordar que el segundo principio debe formar parte del análisis enegético y en muchos casos ser previo en su utilización al primero.

El tema se inicia con el análisis de sistemas cerrados, obteniendo la expresión general del trabajo útil reversible y a partir de él se define la exergía. Después se hace aplicación de las expresiones generales de los sistemas cerrados a sustancias incompresibles y a gases perfectos. A continuación se hace una aplicación de la ecuación del trabajo útil reversible a procesos de flujo y posteriormente se da la definición y algunas aplicaciones de lo que llamaremos rendimiento exergético. El tema se termina con la aplicación a los ciclos termodinámicos.

En todo lo que sigue, conviene destacar:

a) Al exterior inmediato al sistema lo denominaremos, indistintamente, medio ambiente, atmósfera o entorno.
b) Que este medio ambiente lo consideraremos infinito y que sus propiedades térmicas (presión, volumen y temperatura) no se verán alteradas por los interacambios energéticos (calor y/o trabajo) con el sistema en consideración.
c) También hay que decir que el equiljjj¿& al que se hace referencia en todo el tema es , sólo el equilibrio térmico v mecánico,-dejando el equilibrio material o químico, por intercambio de especies, para el tema 9. Por esta razón el estado de equilibrio con el medio ambiente se denomina. estatlo”müeff(rrestrin.gido en el que:

.. math::

   T &= T_o\\
   p &=p_o\\
   \nu &= 0\\
   z & =0






Balance de exergía para sistemas cerrados
-----------------------------------------

Consideremos un sistema cerrado de propiedades uniformes que evoluciona intercambiando calor con un cierto número de fuentes térmicas a temperaturas (i = 0,1,. ..n), y entre las que se encuentra la atmósfera. Durante la evolución el exterior comunica al sistema un trabajo bW. Una posible interacción mecánica realizada por la atmósfera, en tanto que ésta actúe como depósito mecánico, es el trabajo :math:`-p_odV`.(*)

El primer principio aplicado al sistema nos proporciona:

.. math::

   \sum_{i=0}^n \partial Q_i + \partial W = dE  \text{ con } E=U+E_m
   

Si calculamos la producción de entropía habida en la evolución del sistema obtendremos:

.. math::

   \partial \sigma_t = dS_{sis} - \sum_{i=0}^n \frac{\partial Q_i}{T_i}

donde :math:`\partial \sigma_t >0` representa la producción de entropía e incluye no sólo las irreversibilidades interiores y en la frontera del sistema, sino también, el hecho de que cada :math:`Q_i` esté siendo cedido desde una fuente a una temperatura :math:`T_i` que en general no es la temperatura del sistema.

De siempre el interés de la ingeniería es realizar cambios sobre los sistemas que lleven de forma coherente a incrementar el trabajo obtenido o a disminuir el trabajo consumido. Esto nos lleva a considerar la posibilidad de cambiar el funcionamiento interno del sistema para poder minimizar el trabajo comunicado al mismo. Para conseguir este efecto, supuestos definidos los estados extremos del proceso y teniendo en cuenta (5.1), se tendrá que cambiar alguno de los :math:`\partial Q_i` si se quiere modificar :math:`\partial W`. Supongamos que es la transferencia de calor con la atmósfera, :math:`\partial Q_o`, la única interacción energética que varía en tanto que :math:`\partial W` se minimiza. Es decir: suponemos que a excepción de :math:`\partial Q_o`, el resto de las interacciones térmicas vienen fijadas por diseño y que sólo ese :math:`\partial Q_o` es flotante de cara a equilibrar los cambios habidos en :math:`\partial W`. La elección de :math:`\partial Q_o` como la interacción "flotante" como consecuencia del cambio en el diseño, es consistente cop el papel que tradicionalmente se le asigna al calor cedido a la atmósfera en el diseño de sistemas de potencia y refrigeración.

Si se elimina :math:`\partial Q_o` entre las ecuaciones (5.1) y (5.2) queda:

.. math::

   dE - \sum_{i=1}^n \partial Q_i -\partial W = T_o dS_{sis} - \sum_{i=1}^n \frac{T_o}{T_i}\partial Q_i - T_o \partial \sigma_i

y despejando el trabajo:

.. math::

   \partial_{real} = d(E-T_oS)_{sis} - \sum_{i=1}^n \partial Q_i \left( 1 - \frac{T_o}{T_i}\right) + T_o \partial \sigma_t

(*) Nota: es obvio que estamos tratando con velocidades de desplazamiento de la frontera del sistema, v, pequeñas frente a la velocidad del sonido en la atmósfera de modo que la sobrepresión generada por ese desplazamiento, del orden de :math:`\rho \nu^2`, es muy pequeña frente a :math:`p_o` si :math:`v << a` (siendo a la velocidad local del sonido), esto es :math:`\frac{\rho \frac{\nu^2}{2}}{p_o}<<1` y :math:`(p - p_o)dV = \left( \frac{p-p_o}{p_o} \right) p_odV`, por lo que quitamos ese término del trabajo de desplazamiento de la atmósfera.

De acuerdo con el segundo principio :math:`\partial \sigma_t \get 0` por lo tanto los otros dos términos del segundo miembro representan algebraicamente un b'mite inferior para :math:`\partial W`. Este límite inferior se alcanza cuando el sistema evoluciona de manera que no haya producción de entropía en el proceso (esto es, la variación de entropía del universo sea nula). Así pues, identificamos los dos primeros términos del segundo miembro como el trabajo Reversible comunicado al sistema; esto es:

.. math::

   \partial W_{rev} = d(E-T_o S)_{sis}  - \sum_{i=1}^n \partial Q_i \left( 1 - \frac{T_o}{T_i}\right)

Una cuestión que surge en conexión con esto último es si todo el trabajo reversible es trabajo útil o no. La respuesta depende de si la atmósfera, como depósito mecánico, es parte del entorno y de si el sistema experimenta un cambio de volumen comprimiéndose a favor de (o expandiéndose contra) la misma. En el caso en que el depósito mecánico atmosférico intercambie trabajo con el sistema, la parte de SW que es transferida por la atmósfera es (—p0dVj mientras
que el resto loRonstituye el trabajo útil’esto ps de (5.3) se tendrá:

.. math::

   \partial W_{util,real} &= \partial W + p_odV \\
    &= d(E+p_oV-T_oS)_{sis}-\sum_{i=1}^n \partial Q_i \left( 1 - \frac{T_o}{T_i} \right) + T_o \partial \sigma_t


Teniendo en cuenta (5.4) podemos poner:


.. math::

   \partial W_{util,real} = \partial W_{util,rev} + T_o \partial \sigma_t

ecuación que puede escribirse en la forma:

.. math::

   \partial W_{util,real} - \partial W_{util,rev} = T_o \partial \sigma_t

donde se ha puesto que:

.. math::

   \partial W_{util,rev} = d(E+p_oV-T_oS)_{sis} - \sum_{i=1}^n \partial Q_i \left( 1 - \frac{T_o}{T_i}\right)

Así pues:

.. math::

   \partial W_{real} - \partial W_{rev} = \partial W_{util,real} - \partial W_{util,rev}

representa eltra.ba.jo perdido y la ecuación (5.6) es la expresión matemática del **teorema de Gouy-Stodola** o del trabajo perdido que puede enunciarse de la siguiente forma: cuando un sistema evoluciona irreversiblemente destruye trabajo a un ritmo que es proporcional a la generación de entropía habida en el proceso. Al producto T0 6<rt se le conoce con el nombre de irreversibilidad 61 (6i por unidad de masa); al igual que el calor y el trabajo, depende del camino seguido por la evolución, esto es, no es una propiedad del sistema ni tampoco del conjunto sistema-medio ambiente.

Si se quiere saber cuál es el trabajo útil reversible que es necesario comunicar a una masa de control (sistema cerrado) para llevarla desde las condiciones de equilibrio termomecánico con la atmósfera (estado muerto restringido) hasta unas condiciones de temperatura y presión determinadas ( y distintas de las de la atmósfera) en un proceso en el que la única fuente térmica con la que el sistema pueda interactuar es la atmósfera, se hace aplicación de (5.7) obteniéndose:

.. math::

   \Phi_2-\Phi_1 = W_{util,rev} = E-E_o + p_o(V-V_o)-T_o(S-S_o)

A este trabajo, que es el mínimo necesario para conseguir un estado termodinámico determinado (T, p) a partir de las condiciones del medio ambiente se le llama exergía, :math:`\Phi(*)`. Si se considera la unidad de masa, la exergía específica, :math:`\phi = \frac{\Phi}{m}` vendrá expresada por:

.. math::

   \phi = (e-u_o)+p_o(v-v_o)-T_o(s-s_o)

Con esta definición dada de la exergía, la ecuación (5.7) se puede escribir en la forma

.. math::

   \partial W_{util,rev} = d(\Phi) - \sum_{i=1}^n \partial Q_i \left( 1 - \frac{T_o}{T_i} \right)

Así pues, el trabajo útil comunicado a un sistema cuando evoluciona desde un estado de equilibrio 1 a otro 2 , también de equilibrio, y en su evolución intercambia calor con i fuentes térmicas, puede expresarse en la forma:

.. math::

   W_{útil,real} = (\Phi_2-\Phi_1)-\sum_{i=1}^n Q_i \left( 1- \frac{T_o}{T_i}\right) + T_o\sigma_t

Esta ecuación (5.10.a) podemos reescribirla poniendo:

.. math::

   \Delta\Phi = \Phi_2-\Phi_1 = W_{útil,real}+\sum_{i=1}^n Q_i \left( 1- \frac{T_o}{T_i}\right) + T_o\sigma_t

ecuación que no es sino la expresión del balance de exergía para una masa de control; balance que nos indica que la variación de exergía en el sistema cerrado proviene de la exergía que se introduce al sistema con el trabajo comunicado al sistema,	reai, la que se introduce con el calor que se le transfiere al sistema,	:math:`\sum_{i=1}^n Q_i \left( 1-\frac{T_o}{T_i}\right)` (téngase en cuenta que este término representa el trabajo máximo que se podría obtener con la mencionada interacción mediante máquinas de Carnot), menos la que se destruye por irreversibilidades tanto internas al sistema como por las existentes entre el sistema y la atmósfera, :math:`T_o\sigma_t`.

(*) Es importante señalar que la práctica totalidad de los autores definen la exergía como el trabajo máximo que puede obtenerse de un sistema en un determinado estado termodinámico cuando, sin producción de entropía y sin otra fuente térmica distinta de la atmósfera, se le lleva al equilibrio con el medio ambiente. Sin embargo aquí se ha cambiado la definición para que haya coherencia con el criterio de signos atribuido al trabajo en el primer principio. También es importante señalar que lo que aquí se ha denominado exergía, algunos autores de habla inglesa (norteamericanos fundamentalmente) lo denominan disponibilidad.

La exergia, tal como se ha definido, es una función de estado del conjunto sistema-ambiente, y no del sistema sólo; esto es, dados dos estados de equilibrio de un sistema y una atmósfera, la variación de la exergia no depende del camino que el sistema recorra para pasar de un estado de equilibrio a otro. Como el medio ambiente viene caracterizado por su presión y temperatura (T0, p0), es lógico que todas las propiedades termodinámicas que intervienen en la evaluación de la exergia, <f>, vengan expresadas en función de esas variables. Así pues, a partir de (5.8.b) y considerando un sistema simple, podemos escribir:

.. math::

   d\phi = de +p_odv-T_ods

Vamos a hacer aplicación de (5.11) a dos tipos de sustancias:

A)	Sustancias incompresibles a temperatura *T* y presión *p* tales que :math:`T \neq T_o` y :math:`p \neq p_o`.
B)	Gases perfectos, que al igual que en el caso anterior, su presión y temperatura son distintas a la del medio ambiente.

A) Sustancias incompresibles
''''''''''''''''''''''''''''

Para una sustancia incompresible :math:`du = c dT`, :math:`dv=0` y :math:`ds = c \frac{dT}{T}` por lo que la ecuación (5.11), una vez integrada, se reduce a:

.. math::

   \phi = \frac{\phi}{cT_o} =\frac{T}{T_o} -1 - \ln \frac{T}{T_o}

La exergia de una sustancia incompresible es sólo función de la temperatura y referida a :math:`cT_o`, ecuación (5.12), es independiente de cuál sea la sustancia concreta.

Si representamos :math:`\phi = \frac{\phi}{cT_o}` en función de :math:`\frac{T}{T_o}` obtenemos la curva de la Fig 5.1 en la que se puede ver que una sustancia incompresible puede servir como fuente de trabajo en tanto que su temperatura sea distinta de la temperatura de la atmósfera. Efectivamente, un sistema caliente de masa fija puede servir como fuente de alta a un motor térmico cíclico que ceda calor a la atmósfera (punto :math:`T_o`) obteniéndose una cantidad de trabajo. Igualmente de una masa fría también puede obtenerse trabajo sin más que considerar a ésta como el foco frío de un motor térmico, siendo la atmósfera el foco caliente.


B) Gases perfectos
''''''''''''''''''

Para gases perfectos la dependencia de la energía interna, del volumen específico y de la entropía con la temperatura y la presión viene dada por las expresiones siguientes:

.. math::

   du = C_v dT \\
   dv = Rd \left( \frac{T}{p} \right) \\
   ds = c_p \frac{dT}{T} - R\frac{dp}{p}

con lo que :math:`\phi` vendrá dada por:

.. math::

   \phi = c_v T_o \left( \frac{T}{T_o}-1-\gamma \ln \frac{T}{T_o} \right) + RT_o \left( \frac{T}{T_o}\frac{p_o}{p} - 1 + \ln\frac{p}{p_o} \right)

Expresión que podemos adimensionalizar con :math:`c_vT_o` obteniendo:

.. math::

   \phi = \left( \frac{T}{T_o}-1-\gamma \ln \frac{T}{T_o}\right) + (\gamma-1) \left( \frac{T}{T_o}\frac{p_o}{p} - 1 + \ln\frac{p}{p_o} \right)


De (5.13.a) se ve que, para un gas perfecto, la exergia depende de la presión y temperatura. Puede comprobarse que :math:`\phi` (o :math:`\phi`) dada por (5.13.a) tiene un mínimo en (:math:`T_o `, :math:`p_o`). También puede comprobarse que, si del estado final se tiene determinada la presión, la temperatura correspondiente que hace que la, exergia sea mínima viene dada por:

.. math::

   \frac{T}{T_o} = \frac{1}{ 1- \frac{\gamma-1}{\gamma}\left( 1- \frac{p_o}{p} \right) }

En la Fig 5.2 se ha representado :math:`\phi` en función de :math:`\frac{T}{T_o}` para gases perfectos cuyo :math:`\gamma` sea 1.4 y para valores de :math:`\frac{p}{p_o}=0.5;1 y 1.5`


Figura 5.2

Los mínimos indican el valor que alcanzaría la temperatura de un sistema si desde un estado inicial fijo :math:`\left( \frac{T_1}{T-o},\frac{p_1}{p_o}\right)` se quisiera, para un valor de :math:`\frac{p_2}{p_o}` dado, alcanzar, con el consumo mínimo de trabajo, esto es, teniendo como única fuente térmica la atmósfera, un estado termodinámico de equilibrio mediante un proceso sin producción de entropía.

De (5.13.b) puede verse que las curvas :math:`\phi = cte` en las proximidades del punto :math:`\frac{T}{T_o}=1`, :math:`\frac{p}{p_o}=1` son elipses dadas por la ecuación:

.. math::

   \phi = \frac{\tau^2}{2}+\frac{\gamma-1}{2}(\pi-\tau)^2

donde las variables :math:`\tau` y :math:`\pi` están definidas como:

.. math::

   \tau &= \frac{T-T_o}{T_o} \\
   \pi &= \frac{p-p_o}{p_o}

Balance de exergía para sistemas de flujo
----------------------------------------

Para obtener el balance de exergía en sistemas dé flujo, (esto es, sistemas en los que la masa tiene una velocidad media macroscópica) se procede de manera análoga a lo hecho con los sistemas cerrados. Según vimos en el tema 4 [(4.8.a) y (4.24.b)], las ecuaciones del primer y segundo principio para sistemas abiertos en régimen no estacionario son:

.. math::
   
   \sum_{i=0}^n \dot{Q}_i+\dot{W}+\sum_e\left( h+\frac{\nu^2}{2} + gz \right) \dot{m} -  \sum_s \left( h+\frac{\nu^2}{2} + gz \right) \dot{m} = \frac{d}{dt}\left( U+E_m\right)_{VC}

Eliminando :math:`\dot{Q}_o` entre las ecuaciones (5.15) y 1(5.16), y como :math:`h_t = h +\frac{\nu^2}{2} + gz`, despejando :math:`\dot{W}` se obtiene:

.. math::

   \dot{W} = \frac{d}{dt} \left( U+E_m-T_oS\right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t - T_os) \dot{m} -\sum_{i=1}^n \dot{Q}_i \left( 1 - \frac{T_o}{T_i} \right) + T_o \dot{\sigma}_t

A :math:`h_t — T_os` se le suele llamar disponibilidad de flujo(*)


Al igual que en el caso de sistemas cerrados, en lo que estamos interesados es en la potencia mecánica útil, tanto real como reversible, que hay que consumir en una evolución de un sistema de flujo no estacionario. Procediendo igual que en el apartado anterior, podremos escribir:

.. math::

   \dot{W}_{útil,real} = \frac{d}{dt} \left(U + E_m + p_oV - T_oS \right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t-T_os)\dot{m}  - \sum_{i=1}^n \dot{Q}_i\left( 1- \frac{T_o}{T_i}\right) +T_o\dot{\sigma}_t


habiendo desdoblado el término de la potencia mecánica en dos: potencia útil, :math:`\dot{W}_{útil}`, y potencia debida al hecho de que las paredes del volumen de control es deformable, :math:`-p_o\frac{dV_{VC}}{dt}` que representa la potencia mecánica intercambiada con la atmósfera.

La potencia útil reversible será: 

.. math::

   \dot{W}_{útil,rev} = \frac{d}{dt} \left(U + E_m + p_oV - T_oS\right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t-T_os)\dot{m}  - \sum_{i=1}^n \dot{Q}_i\left( 1- \frac{T_o}{T_i}\right) +T_o\dot{\sigma}_t

y la ecuación (5.18) se puede escribir:

.. math::

   \dot{W}_{útil,real} = \dot{W}_{útil,rev}+T_o\dot{\sigma}_t

(*) En algunos textos a :math:`(e + p_ov — T_os)` le llaman disponibilidad. La disponibilidad de flujo se relaciona con ésta mediante la relación :math:`a_f = a + v(p — p_o)`.


Si desde las condiciones del medio ambiente (estado muerto restringido: :math:`p_o, T_o, v = 0 y z = 0`) mediante un proceso en régimen estacionario (:math:`\frac{d}{dt}=0`) y teniendo como única fuente térmica la atmósfera (:math:`\sum_{i=1}^n \dot{Q}_i \left( 1- \frac{T_o}{T_i} \right)=0` ) se quiere obtener una corriente con una velocidad, v, temperatura, T, presión, p y altura z determinadas, la potencia mecánica reversible útil i necesaria es :math:`m\psi` siendo :math:`\psi`  la exergía de una corriente, que se obtiene a partir de (5.19) con ^ todas las condiciones especificadas. Esto es:

.. math::

   \psi = h -h_o + \frac{\nu^2}{2}+gz- T_o(s-s_o)

Teniendo en cuenta (5.8.a), (5.18) v Í5.211 el balance de exergía para sistemas de flujo en ;égimen no estacionario puede expresarse en la forma:	

.. math::

   \frac{d}{dt}\bracevert_{VC} + \sum_s \psi \dot{m} - \sum_e \psi \dot{m} - \dot{W}_{útil,real} - \sum_{i=1} \dot{Q}_i \left( 1-\frac{T_o}{T_i} \right) + T_o\dot{\sigma}_t = 0

Ecuación, que de manera análoga al caso de sistemas cerrados (5.10.b), nos indica que la variación de exergía de un recinto abierto proviene de la exergía neta que se introduce al recinto: a) con la masa a través de las fronteras permeables, (:math:`\sum_s \psi \dot{m} - \sum_e \psi \dot{m}`) con el trabajo, :math:`\dot{W}_{útil,real}`

a través de las fronteras impermeables restando la
exergía que se destruye por irreversibilidades existentes en el proceso, irreversibilidades tanto internas al sistema como las que hay entre el sistema y el medio ambiente.

Si el proceso de flujo es estacionario, la ecuación (5.22) se reduce a:

.. math::

   \sum_s \psi \dot{m} - \sum_e \psi \dot{m} - \dot{W}_{útil,real}- \sum_{i=1} \dot{Q}_i \left( 1-\frac{T_o}{T_i} \right) + T_o\dot{\sigma}_t = 0


La expresión (5.23) puede ponerse de una forma genérica:

.. math::

   \dot{e_x}\bracevert_{obtenida} + \dot{e_x}\bracevert_{perdida} = \dot{e}\bracevert_{suministrada} 


donde :math:`e_x` señala exergía. El valor de cada término habrá que asignarlo en cada caso concreto. A modo de ejemplo, supongamos la actuación de una turbina funcionando en régimen estacionario a la que se suministran :math:`\dot{m} kg\cdot s^{-1}` de vapor en condiciones (:math:`p_1`, :math:`T_1`), que sen de la misma en condiciones (:math:`p_2`, :math:`T_2`) y proporciona una potencia :math:`\dot{W}`. En este caso particular:

.. math::

   \dot{e}_x\bracevert_{obtenida} &\text{ es la potencia } \dot{W} \\
   \dot{e}_x\bracevert_{suministrada} &\text{ es } \dot{m}\psi_e


y de (5.24) se sigue que:

.. math::

   \dot{e}_x\bracevert_{perdida} = \dot{m} \psi_e - \dot{W} = \dot{m} \psi_s + T_o \dot{\sigma}_t 

¿Cómo se modificarían estas expresiones si el flujo músico de salida se utilizase en un dispositivo para calefacción saliendo del dispositivo en condiciones del ambiente (p0, T0)1.

De manera análoga, la expresión (5.lO.b) y la (5.22) una vez integrada, pueden expresarse, también, en la forma:

.. math::

   \dot{e}_x\bracevert_{obtenida} + \dot{e}_x\bracevert_{perdida} = \dot{e}_x\bracevert_{suministrada} 




.. toctree::
   :maxdepth: 1
   :caption: Contenido:
   
   exergia_rendimiento
   exergia_procesos_ciclicos