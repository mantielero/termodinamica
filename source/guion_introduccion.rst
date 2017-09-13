Introducción. Algunos conceptos y definiciones
==============================================

(Antonio Sánchez Sánchez. Teresa Leo Mena)

Introducción
------------

En esta asignatura se expondrán los conceptos y métodos que permiten discernir en qué casos un determinado sistema puede alcanzar el objetivo para el que ha sido diseñado y en cuales no. En general se profundizará sobre el concepto de energía y la forma en que ésta puede utilizarse con un mejor aprovechamiento.

La palabra termodinámica proviene de las griegas *thermo* (calor) y *dynamics* (potencia). Según esto, la termodinámica se definiría como la parte de la física que estudia la potencia que puede obtenerse del calor. Esta definición estaría de acuerdo con el objetivo inicial de los estudios termodinámicos en el pasado siglo XIX, que surgieron para conseguir mejorar el rendimiento de las máquinas de vapor.

En la actualidad la termodinámica se define como la ciencia de la energía y la entropía. Puesto que todavía no se han definido estas magnitudes y se tiene un conocimiento intuitivo de las denominadas calor y trabajo, se puede dar una definición en términos que resultan más familiares diciendo que *la termodinámica es la ciencia que trata del calor y el trabajo y los cambios en aquellas propiedades de la materia que tienen relación con el calor y el trabajo*. Posteriormente se definirán con precisión estas magnitudes.

Ya de entrada es importante tener muy claro, aunque se volverá a repetir a lo largo del curso con frecuencia, que la termodinámica no formula ninguna hipótesis respecto a la constitución del sistema, es decir, nada estipula sobre la naturaleza de los constituyentes de la materia (moléculas, átomos, protones, etc ). En termodinámica se considera que la distribución de materia es continua y, por tanto, las dimensiones de los sistemas sometidos a estudio han de ser grandes respecto a las dimensiones atómicas, con volúmenes mínimos del orden de :math:`10^{-18}` a :math:`10^{-15}m^3`. Esto representa el volumen de un cubo de hasta 1 micra de lado, o el de una esfera de hasta 0,6 micras de radio. Téngase en cuenta que en este volumen tiene que haber un gran número de partículas para que la hipótesis de distribución continua se cumpla. Suponiendo que el mencionado volumen contenga un gas en condiciones normales, el número de partículas sería muy alto (de :math:`10^6` a :math:`10^9`), por lo que las posibles variaciones aleatorias en el valor de las distintas propiedades que pueden definir el sistema resultan pequeñas y la hipótesis se cumple.

En el estudio de la termodinámica se considerará cómo son afectadas las propiedades de un sistema por las interacciones que modifican su energía, cómo la energía puede transformarse de una forma en otra, qué limitaciones tienen estas transformaciones y cómo se puede utilizar la capacidad de transformación de la energía en el diseño de máquinas útiles.

A lo largo del curso se verá cómo el concepto de la termodinámica se va llenando de contenido.

En este tema se considerará el alcance y método de la termodinámica, distinguiéndolo del que es característico de la mecánica estadística, así como un conjunto de conceptos básicos necesarios para realizar su estudio.

Alcance de la Termodinámica
---------------------------

Ya se ha dicho que la termodinámica centra su estudio en objetos macroscópicos, es decir, porciones de materia integradas por un gran número de partículas. El estudio de cómo influyen las interacciones de calor y trabajo sobre las propiedades de estos cuerpos y cómo pueden utilizarse estos cambios de propiedades en la conversión de una forma de energía en otra y qué limitaciones tiene esta conversión, será el tema de trabajo. Se verá que los principios primero y segundo de la termodinámica delimitarán las posibilidades que presénta la conversión de energía.

Para hacerse una idea del alcance de la termodinámica, desde el punto de vista del ingeniero, se considerarán algunas de las áreas en las que se aplica. Entre ellas se pueden citar:

- Plantas de potencia (combustibles fósiles, fisión nuclear, fusión nuclear, energía solar, geotérmica, etc. ).
- Motores (vapor, gasolina, diesel, turbinas estacionarias y de propulsión, cohetes, etc.).
- Sistemas de acondicionamiento de aire y refrigeración.
- Calentadores.
- Equipos para procesos químicos.
- Diseño de equipos mecánicos, etc.

De hecho, **en cualquier sistema que maneje o transforme energía, la termodinámica juega un papel fundamental**, por lo que en la mayor parte de las áreas de la ingeniería el conocimiento de los conceptos termodinámicos se hace imprescindible. Para facilitar su estudio se comenzará considerando algunas definiciones y conceptos fundamentales utilizados con frecuencia en el desarrollo de esta materia.


Conceptos fundamentales y definiciones
--------------------------------------

Sistema termodinámico
^^^^^^^^^^^^^^^^^^^^^

Como **sistema termodinámico** se puede considerar cualquier cosa que se desee estudiar y el sistema puede ser tan sencillo como un cuerpo libre, o tan complejo como una moderna central productora de energía. A efectos de sistematización, un sistema termodinámico se define como cualquier cantidad de materia o cualquier región del espacio sometida a estudio (se entiende que se está considerando el análisis termodinámico del mencionado sistema). La cantidad de materia o región del espacio debe hallarse contenida dentro de unos límites perfectamente predeterminados. Estos límites pueden ser fijos o deformables, así como reales o imaginarios.

Según su constitución los sistemas pueden ser homogéneos o heterogéneos. Se dice que un sistema es homogéneo cuando su composición química y propiedades físicas son iguales en todas sus partes o varían de un modo continuo de un punto del sistema a otro. Como ejemplo característico se podría considerar una columna de aire donde en este sistema y debido a la gravedad, cambian de un modo continuo con la altura, tanto su composición química como sus propiedades físicas. Cuando un sistema está constituido por dos o más partes homogéneas distintas se denomina heterogéneo.

En general, se estudiarán sistemas simples compresibles, es decir, aquellos sistemas para los que la única forma de trabajo reversible posible es la ligada a un cambio de volumen. Estos sistemas son homogéneos y se considerará que no es importante la influencia de:

- Campos eléctricos, magnéticos o gravitatorios.
- Efectos de capilaridad.
- Variación de composición isotópica en la sustancia que constituye el sistema.
- Si el sistema es sólido, igualdad de presión en todas las direcciones.

.. note::

   Composición isotópica: del número másico.

Si se define el sistema como una determinada cantidad de materia, entonces el sistema contiene siempre la misma materia y no puede haber transferencia de masa a través del límite del mismo. Sin embargo, si un sistema se define como una región del espacio dentro de un límite predeterminado, entonces la materia puede cruzar el límite del sistema. Para distinguir estos dos tipos de sistemas, al primero se le denomina sistema cerrado o masa de control y al segundo sistema abierto o volumen de control. El límite de un volumen de control, que puede ser móvil, se denomina superficie de control.

Todo lo situado fuera de los límites del sistema se denomina medio ambiente. Normalmente se considera como medio ambiente del sistema aquellas cosas exteriores al mismo que ejercen alguna influencia sobre él (interaccionan con el sistema). El conjunto de sistema y medio ambiente constituye el universo termodinámico en un problema dado.

Un caso especial de sistema cerrado es el sistema aislado. Un sistema aislado es aquel que no interacciona de ningún modo con su medio ambiente. Téngase en cuenta que necesariamente un sistema aislado ha de ser un sistema cerrado, ya que la condición de no interacción con el ambiente prohíbe cualquier transferencia de masa a través del límite del sistema.

Como ya se ha dicho, los sistemas termodinámicos pueden abarcar desde el gas contenido en un pequeño volumen, a plantas industriales complejas y también grandes regiones de la atmósfera terrestre. EL PASO MAS IMPORTANTE EN LA SOLUCION DE UN PROBLEMA EN TERMODINAMICA ES NORMALMENTE LA SELECCION Y ESPECIFICACION CUIDADOSA DEL SISTEMA A CONSIDERAR.

Se consideran a continuación algunos ejemplos de sistemas termodinámicos que se presentarán con frecuencia a lo largo de este estudio.

Cuando se estudia el flujo de gas a través de un conducto, el sistema a considerar será el gas contenido en un determinado tramo del conducto y en este caso los límites del sistema serán las paredes del conducto (límite real) y la frontera ideal que delimita transversalmente la longitud predeterminada del mismo (límite imaginario), como se muestra en la figura 1.1:

.. figure:: ./img/volumen_control.png
   :height: 300px
   :align: left

   Volumen de control

.. figure:: ./img/masa_control.png
   :height: 300px
   :align: right

   Masa de control


En el estudio de un gas contenido en un cilindro provisto de émbolo, el sistema será normalmente el gas contenido dentro del cilindro. En este caso, aunque el volumen del sistema varíe, el sistema será un sistema cerrado mientras el émbolo se mueva en el cilindro y no sobrepase el límite del mismo. En el estudio de plantas de potencia se verá que las transformaciones que tienen lugar en las mismas se pueden analizar considerando un determinado elemento de masa de fluido (sistema cerrado) y siguiendo su evolución a lo largo de la instalación, o considerando un determinado volumen de control y realizando sobre él el análisis correspondiente.

En general, **al proceder al estudio de una determinada instalación, la mayor parte de las veces ha de idealizarse el conjunto de elementos que la constituyen**, de forma que sean asimilables a sistemas que puedan someterse a un análisis termodinámico sencillo. En tanto en cuanto la elección del correspondiente sistema ideal resulte adecuada al sistema real que se quiere modelar, el análisis teórico dará un resultado que responderá tanto más al resultado real, cuanto más se aproxime la descripción ideal al comportamiento real del sistema. Se ha de tener esto muy presente para ”no caer en la falacia de considerar que el estudio teórico de un sistema hace posible una determinada actuación, mientras que realmente esa actuación no se da”. Está claro que, cuando esto ocurre, el mencionado estudio teórico se basa en un modelo inadecuado al sistema real sometido a estudio.

Propiedades, estados, procesos y equilibrio
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para estudiar un determinado sistema lo primero que debe hacerse es proceder a su descripción y ello requiere el conocimiento de sus características propias, es decir, de sus propiedades.

También la predicción de la evolución del mismo requiere el conocimiento de las propiedades del sistema y de cómo estas se relacionan. ¿A qué se llaman propiedades de un sistema?

Se denominan propiedades termodinámicas de un sistema, o simplemente propiedades, a cualesquiera características macroscópicas observables tales como la masa, el volumen, la presión, la temperatura..., cuyos valores numéricos pueden asignarse en un momento dado sin 'tener en cuenta la historia del sistema. A veces se considera propiedad del sistema cualquier relación entre las propiedades directamente observables del mismo, tal como el producto de la presión y el volumen o la presión y la temperatura, etc. Tales propiedades pueden considerarse características indirectamente observables de un sistema. Teóricamente pueden definirse un gran número de propiedades, pero como se verá, sólo unas pocas resultan útiles. Conviene tener en cuenta que a las propiedades termodinámicas también se las conoce como variables termodinámicas o variables de estado.

Hay otro tipo de propiedades de un sistema que no son directamente observables y que se deducen de los principios de la termodinámica. En las lecciones correspondientes se verá cómo se introducen la energía interna, la entalpía, la entropía, etc., a partir de estos principios.

En el estudio de la termodinámica también se encuentran magnitudes que no son propiedades, porque sus valores dependen de la trayectoria seguida por el sistema, pudiendo citar entre ellas las transferencias de energía, como son el calor y el trabajo.

Todo lo dicho anteriormente podría sintetizarse utilizando un lenguaje matemático de la forma siguiente.

Supóngase un conjunto de propiedades de un sistema:

.. math::

   x_1, x_2, ..., x_n

que pueden ser utilizadas para su caracterización. Desde este punto de vista, serían entonces varióles de estado. Cualquier relación entre estas propiedades conduce a otra propiedad termodinámica que puede expresarse por la función:

.. math::

   y = y(x_1, x_2, ..., x_n)

siendo *y* la nueva propiedad, que por la forma de definirla se denomina función de estado.


Si esto es así, *y* es diferenciable:

.. math::

   dy = \sum_i \frac{\partial y}{\partial x_i} dx_i


y los coeficientes de esta expresión satisfacen la relación de las derivadas cruzadas (teorema de Schwarz):

.. math::

   \frac{\partial^2 y}{\partial x_j \partial x_i} = \frac{\partial^2 y}{\partial x_i \partial x_j}

es decir, *dy* es una diferencial exacta. Esta condición se utilizará con frecuencia posteriormente.

Si *y* no fuese una propiedad del sistema, es decir, su valor en cada punto dependiera de la trayectoria seguida para alcanzar ese punto, entonces las ecuaciones (1.1) y (1.2) no se cumplirían.

Para representar un cambio diferencial en una variable que no sea una propiedad se utilizará el símbolo :math:`\delta y`, que podrá expresarse:

.. math::

   \delta y = \sum z_i dx_i

donde :math:`z_i` y :math:`x_i` son variables de estado para las que:

.. math::

   \frac{\partial z_i}{\partial x_j} \neq \frac{\partial z_j}{\partial x_i}

por lo que :math:`\delta y` no es una diferencial exacta y su integral depende de la trayectoria (integral de línea).

El estado, o situación determinada en la que se halla un sistema, viene especificado por el valor de sus propiedades. Ya que hay numerosas relaciones entre las propiedades de un sistema particular, los valores de unas pocas propiedades identificarán completamente su estado, puesto que las otras propiedades pueden determinarse en función de estas pocas. El número mínimo de propiedades que hace falta para definir el estado de un sistema depende de su complejidad y como se verá al estudiar el Principio de Estado, se halla perfectamente determinado.

Si un sistema tiene el mismo valor de sus propiedades en dos instantes diferentes, se dice que el sistema se encuentra en el mismo estado en estos dos instantes. Cuando cualquier propiedad cambia, el estado del sistema cambia y se dice que el sistema ha experimentado un proceso. Por lo tanto, un proceso es una transformación desde un estado a otro. Un sistema está en estado estacionario si ninguna de sus propiedades cambia con el tiempo.

Entre los diversos procesos que puede experimentar un sistema, tiene especial interés el ciclo termodinámico. Se define el ciclo termodinámico como la secuencia de procesos experimentados por un sistema de forma que comienza y termina en el mismo estado. Por lo tanto, al final de un ciclo las propiedades del sistema son las mismas que al principio, es decir, en el ciclo no hay cambio neto del estado del sistema. Los ciclos juegan un gran papel en las aplicaciones de la termodinámica y la mayor parte de las instalaciones de potencia funcionan mediante ciclos repetidos en el tiempo. El funcionamiento de cualquier motor puede modelizarse según este proceso y el funcionamiento real de las plantas de vapor se representa perfectamente mediante este modelo.

Como se ha dicho antes, en un estado dado cada propiedad tiene un valor definido que puede ser asignado sin saber cómo el sistema ha llegado a ese estado. Por lo tanto, el cambio en el valor de una propiedad, cuando el sistema es alterado para pasar de un estado a otro, se determina únicamente por los estados extremos y resulta independiente de la trayectoria particular seguida por el sistema en el cambio de estado. Es decir, el cambio es independiente de los detalles, o historia, del proceso. Recíprocamente, si la variación en el valor de una magnitud es independiente de la trayectoria del proceso entre dos estados, entonces aquella magnitud es una propiedad. Esto proporciona la prueba necesaria y suficiente para determinar si una magnitud es una propiedad: una magnitud determinada es una propiedad si, y solo si, la variación de su valor al pasar de un estado a otro es independiente del proceso seguido. Se sigue de esto que si el cambio en el valor de una magnitud depende de los detalles del proceso y no solamente de los estado extremos, la mencionada magnitud no es una propiedad termodinámica.

Propiedades extensivas, intensivas y específicas
''''''''''''''''''''''''''''''''''''''''''''''''

Las propiedades termodinámicas pueden dividirse en dos grandes grupos: propiedades extensivas y propiedades intensivas.

A una propiedad se le denomina extensiva si su valor para el sistema en conjunto es la suma del valor correspondiente a cada parte en las que el sistema puede dividirse. Entre ellas se pueden citar la masa y el volumen, así como muchas otras que se irán definiendo a lo largo del curso.

Las propiedades intensivas son aquellas que tienen el mismo valor para cualquier parte del sistema homogéneo que para el sistema en conjunto. La presión, temperatura y densidad son ejemplos de estas propiedades.

Si el valor de una propiedad extensiva se divide entre la masa del sistema, la propiedad resultante es una propiedad intensiva y se denomina propiedad específica. Por ejemplo, el volumen específico se obtiene dividiendo el volumen total del sistema (propiedad extensiva) entre la masa del mismo. Esta relación del volumen a la masa es la misma para cualquier punto de un sistema homogéneo y por tanto es una magnitud intensiva. Para designar una propiedad intensiva se utilizarán letras minúsculas y las propiedades extensivas se designarán mediante letras mayúsculas. Las propiedades específicas se representarán, por tanto, con letras minúsculas. Como excepción, la temperatura termodinámica del sistema se representará con mayúscula y la masa del sistema se suele representar mediante *m* minúscula.

Matemáticamente, se puede formular todo lo dicho recurriendo al concepto de función homogénea. Como se recordará o puede verse en cualquier libro de análisis matemático, una función *Y* se denomina homogénea de grado :math:`\alpha` cuando se verifica:

.. math::

   Y(\lambda X_1, \lambda X_2, ..., \lambda X_n) = \lambda^\alpha Y(X_1, X_2, ..., X_n)

en la que las :math:`X_i` son propiedades extensivas del sistema.

Para estas funciones se cumple el teorema de Euler:

.. math::

   \sum X_i \frac{\partial Y}{\partial X_i} = \alpha Y


También se verifica que si una función es homogénea de grado :math:`\alpha`  su derivada de orden *p* es homogénea de grado :math:`\alpha -p`. En esta expresión *p* es un entero positivo, pero :math:`\alpha`  no necesita ser un entero mayor que *p*.

Según lo que acaba de verse, si *Y* es una propiedad de un sistema simple que contiene *n* moles de sustancia, *Y* será intensiva o extensiva según sea proporcional a :math:`n^0` o a :math:`n^1`, respectivamente:

.. math::

   Y \approx n^0° (\alpha = 0), intensiva\\
   y \approx n^1 (\alpha = 1), extensiva

Así, el volumen total *V* es extensiva, ya que si se duplica el número de moles del sistema, conservando constantes todos los parámetros intensivos, el volumen se duplica. Por otro lado, el volumen total dividido entre el número de moles del sistema proporciona el volumen específico molar (:math:`v = \frac{V}{n}`) que es una variable intensiva.

Conviene tener claro que cualquier propiedad extensiva *Y* tiene una variable intensiva correspondiente :math:`\frac{Y}{n}`, pero la inversa no es siempre cierta ya que variables como *T* y *p* no poseen sus correspondientes extensivas.

Para aclarar lo expuesto, supóngase que *Y* es una propiedad extensiva dependiente de otras propiedades extensivas :math:`X_i`. El requisito de que *Y* sea una propiedad extensiva significa que si se duplican las :math:`X_i`, se duplica *Y*, es decir:

.. math::

   Y(2X_1,2X_2, ..., 2X_n) = 2 Y(X_1, ..., X_n)

y en general:

.. math::

   Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = \lambda Y(X_1, ..., X_n)

en otras palabras, *Y* es homogénea de grado uno.

Considerando que *Y* sea una propiedad intensiva, al duplicar las *X* se deja sin alterar la *Y*, o en general:

.. math::

   Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = Y(X_1, ..., X_n)


por lo que *Y* es homogénea de grado cero.

Resumiendo, si *Y* es una propiedad que depende de variables extensivas :math:`X_i`, resultará que *Y* será una propiedad extensiva si es homogénea de grado uno, y será intensiva si es homogénea de grado cero. Según se vió antes al considerar la derivada de orden *p* de una función homogénea, si *Y* es extensiva, la primera derivada respecto a una variable extensiva será una propiedad intensiva.

A lo largo del curso se utilizará con frecuencia el criterio de homogeneidad.

Fase y sustancia pura
^^^^^^^^^^^^^^^^^^^^^

Con la palabra fase se hace referencia a la materia que se presenta con una composición química y estructura física determinadas, es decir, una sustancia se presenta en una fase dada cuando es homogénea en todos sus puntos, tanto en composición como en estructura física.

En general, se acostumbra a considerar que distintas fases de una sustancia definida suponen distintos estados de agregación, así se dice que el agua puede presentarse en tres fases distintas: sólido (hielo), líquido (agua líquida) y gas (vapor de agua); no obstante, se han citado hasta siete variedades de hielo, todas sólidas, cada una de las cuales constituye una fase distinta. Algo análogo podría decirse del azufre, fósforo, carbono, etc.

Cuando se halla presente más de una fase, las fases están separadas mediante superficies de separación (interfases), al pasar a través de las cuales cambian bruscamente las propiedades físicas o las químicas del sistema. Los gases, en general, se mezclan en cualquier proporción para formar una sola fase. Algunos líquidos denominados miscibles, como el alcohol y el agua, se mezclan para formar una sola fase líquida. Otros líquidos, que se denominan inmiscibles, como el aceite y el agua al mezclarse forman dos fases líquidas.

De los sistemas termodinámicos estudiados tienen una importancia fundamental, por la frecuencia con que se presentan, los constituidos por una sustancia pura. Se define una sustancia pura como aquella que tiene una composición química definida. Una sustancia pura puede existir en más de una fase, pero su composición química debe ser la misma en cada una de ellas. Por ejemplo, la mezcla de agua líquida y vapor de agua forma dos fases, pero es una sustancia pura, ya que se tiene la misma composición química en ambas fases. Al estudiar un sistema formado por aire seco, podrá ser considerado como sustancia pura en tanto en cuanto sea una mezcla de gases, pero si por enfriamiento se consigue que aparezca una fase líquida, el sistema ya no estará integrado por una sustancia pura, ya que la composición del líquido es distinta a la de la fase gaseosa.


Equilibrio
^^^^^^^^^^

El estudio de la termodinámica clásica se centra especialmente en el estudio de los estados de equilibrio y la variación de propiedades producidas cuando un sistema pasa de un estado de equilibrio a otro.

En estudios previos ya se ha encontrado esta palabra, en primer lugar en mecánica, en donde la condición de equilibrio resultaba de la anulación de la resultante de las fuerzas que se ejercían sobre el punto, o bien la anulación de fuerzas y momentos sobre el cuerpo rígido o sistema de puntos.

Cuando se efectúa el estudio termodinámico de un sistema, el concepto de equilibrio tiene mayor alcance y no sólo incluye el equilibrio de fuerzas sino también el de otras interacciones. Cada clase de interacción se refiere a un aspecto particular del equilibrio termodinámico o equilibrio total de un sistema. De acuerdo con lo dicho, deben existir varios tipos de equilibrio particular para completar la condición de equilibrio termodinámico. Entre estos figuran el equilibrio mecánico, el equilibrio térmico y los equilibrios de fase y químico. Más adelante se consideran criterios para estos cuatro tipos de equilibrio, pero de momento es importante conocer la forma de decidir si un sistema se encuentra en estado de equilibrio termodinámico. Para ello, se aisla el sistema de su medio ambiente y se observa qué sucede con sus propiedades. Si no hay cambio una vez aislado el sistema, se puede asegurar que el sistema se hallaba en equilibrio en el momento de aislarlo y se puede afirmar que se encontraba en estado de equilibrio termodinámico, o simplemente en estado de equilibrio.

Cuando un sistema se halla en estado de equilibrio, las propiedades del sistema tienen igual valor en cada fase del mismo y de hecho sólo tiene sentido hablar de variables o propiedades del sistema cuando el sistema se encuentra en equilibrio. Considérese, por ejemplo, que se utiliza la presión y la temperatura para describir el estado de un sistema. En este caso, la temperatura del sistema es uniforme en todos los puntos del mismo y, si no existen campos de fuerza externos, también lo es la presión.

Para los sistemas termodinámicos son posibles estados en los que las propiedades termodinámicas toman distintos valores en distintos puntos del sistema y, por lo tanto, no son estados de equilibrio. Considérese, por ejemplo, una barra metálica con un extremo en contacto con la pared de un horno y el otro en contacto con la atmósfera. Si este sistema se aisla, se verá que sus variables cambian con el tiempo hasta llegar al equilibrio. El proceso durante el que el sistema pasa de un estado de no equilibrio a un estado de equilibrio se denomina proceso de relajación^ y el tiempo que tarda cada parámetro del sistema en hacerse igual en todo el sistema, se conoce como tiempo de relajación del parámetro dado r. El tiempo total de relajación de un sistema es más largo que los tiempos individuales de relajación.

Los tiempos de relajación para los distintos procesos no pueden calcularse dentro del marco de la termodinámica, ya que los fenómenos de relajación son procesos, a nivel molecular, de transferencia de energía, cantidad de movimiento y magnitudes físicas análogas. La evaluación de los tiempos de relajación es un problema de la cinética física.

En termodinámica técnica se está más interesados por los procesos (cambios de estado) que por los estados de equilibrio en sí, que no pueden dar lugar a ningún cambio que permita obtener el efecto que se busca en una instalación determinada. Es claro que durante un proceso determinado, cuando el sistema que lo realiza pasa de un estado a otro, no es posible definir el valor de sus propiedades termodinámicas porque éste varía según el punto que se elija en el mismo para efectuar su determinación. A fin de poder estudiar termodinàmicamente estos cambios, se utilizan dos modelos de procesos: procesos reversibles y procesos cuasiestáticos.

El proceso reversible se define como aquel que experimenta un sistema que mantiene el equilibrio termodinàmico en los sucesivos estados que definen la trayectoria del proceso.

Más próximo a la realidad, y por tanto se utilizará con frecuencia para aproximarse al estudio de un proceso que tenga lugar en una instalación real, se encuentra el modelo de proceso cuasi estático o de cuasiequilibrio. Estos procesos se caracterizan porque su desviación de los correspondientes procesos en equilibrio termodinàmico es muy pequeña. Es decir, todos los estados por los que pasa un sistema en un proceso cuasi estático pueden considerarse estados de equilibrio. Para que esto ocurra los correspondientes tienpos de relajación de los distintos parámeros que carazterizan a sistem deben ser mucho más pequeños, que el tiempo empleado por el proceso para completarse. Dicho de otra forma, la velocidad del proceso es mucho menor que la velocidad de relajación. Por ello, en cualquier etapa del proceso habrá tiempo suficiente como para que las variables termodinámicas utilizadas adquieran cada una de ellas valores uniformes en todo el sistema y el proceso representará una sucesión continua de estados de equilibrio infinitamente próximos entre sí.

En los procesos reales, los estados de no equilibrio son inevitables, por lo que las transformaciones que interesará analizar se podrán aproximar a procesos cuasi estáticos, pero nunca se identificarán del todo con ellos.

El interés en los procesos cuasi estáticos se basa fundamentalmente en dos consideraciones:

- Primero, los modelos termodinámicos simples dan al menos una información cualitativa del comportamiento de los sistemas reales y estos modelos pueden obtenerse considerando procesos cuasi estáticos. Esto es análogo a la utilización del punto material o a las poleas sin rozamiento en el estudio de la mecánica
- Segundo, el concepto de proceso cuasi estático es el instrumento más adecuado para la deducción de las relaciones que existen entre las propiedades de sistemas en equilibrio.
Para estudiar termodinàmicamente un determinado proceso no es condición imprescindible que el proceso sea asimilable a uno cuasi estático. Simplemente, pudiendo definir los estados inicial y final del proceso, es decir, siempre que estos estados sean de equilibrio, es posible deducir y evaluar ciertos efectos globales que tienen lugar durante aquel.

Método termodinàmico y metodo estadístico
-----------------------------------------

El estudio de los procesos que tienen lugar en los sistemas macroscópicos, es decir, sistemas formados por un gran número de micro partículas (átomos, moléculas, iones, etc., dependiendo de la clase de sistema) puede abordarse siguiendo dos métodos:

- Método termodinàmico.
- Método estadístico.

El método termodinàmico es independiente de cualesquiera modelos de la estructura de la materia (para nada requiere la existencia de átomos, moléculas, etc.) esencialmente es un método fenomenológico, es decir, su propósito fundamental es establecer relaciones entre propiedades directamente observables (que se miden por procedimientos macroscópicos), tales como presión, volumen, temperatura, concentración de disoluciones, intensidad de campos eléctricos, y magnéticos, etc. Magnitudes asociadas con la estructura atómica y molecular de la materia (dimensiones de átomos o moléculas, su masa, etc.) no son utilizadas por el método termodinámico en la solución de problemas.

En contraste con lo dicho antes, el método estadístico para estudiar las propiedades de cuerpos macroscópicos se basa en la utilización de modelos atómico-moleculares. El propósito fundamental de la física estadística puede formularse como sigue: utilizando las leyes que gobiernan el comportamiento de las partículas integrantes de un determinado sistema, deduce las leyes que gobiernan el comportamiento de las magnitudes macroscópicas que definen el sistema mencionado.

Al afrontar el estudio del comportamiento de la materia, se encuentra que tanto la termodinámica como la física estadística poseen ventajas e inconvenientes en la consideración de distintos fenómenos.

El método termodinàmico, al ser independiente de modelos estructurales determinados, está caracterizado por un mayor grado de generalidad. Los resultados obtenidos por la utilización de la física estadística son ciertos sólo en el intervalo de validez de las hipótesis efectuadas en relación con el comportamiento de los constituyentes del sistema.

El método termodinàmico se distingue, por regla general, por su gran simplicidad y abre el camino a la solución de gran número de problemas específicos mediante procedimientos matemáticos sencillos, sin necesidad de ninguna información de las propiedades de átomos y moléculas. Esta es la gran ventaja de esté método, especialmente cuando se resuelven problemas prácticos de carácter técnico (termodinámica técnica, transferencia de calor).
El método termodinàmico posee, sin embargo, una limitación fundamental: su utilización no permite poner de manifiesto el mecanismo interno de los fenómenos estudiados.

Por esta razón, en Termodinámica, la pregunta ¿por qué? carece de sentido. Supóngase, por ejemplo, que se aplica el método termodinámico para determinar cómo un alambre de cobre se enfría cuando se somete a una rápida extensión, mientras que una banda de goma, en las mismas condiciones, se calienta. Desde un punto de vista termodinámico hay que contentarse en el hecho experimental, ya que el mecanismo físico en el que se basa este fenómeno permanece oculto. En contraste con esto, la solución de un problema particular por el método de la física estadística se basa desde el principio en conceptos atómico-moleculares, lo que permite visualizar el mecanismo del fenómeno considerado.

El método estadístico permite, en principio, resolver problemas que no tienen solución por el método termodinámico. Los ejemplos más importantes de esta clase son la deducción de las ecuaciones de estado de sistemas macroscópicos, la teoría de capacidades térmicas, algunos problemas de la teoría de la radiación térmica, etc.

Conviene destacar que el método estadístico permite, por un lado, una fundamentación rigurosa de las leyes de la termodinámica y por otro lado, hace posible fijar los límites de aplicabilidad de las leyes y también predecir las violaciones de la termodinámica clásica (fluctuaciones) y estimar su escala.

Es claro, de lo visto antes, que ni la Termodinámica ni la Física Estadística se encuentran limitadas a un campo particular de fenómenos físicos, en contraste con la óptica, mecánica, electrodinámica y otras ramas de la física que estudian fenómenos muy definidos. Tanto la Termodinámica como la Física Estadística proporcionan los métodos más adecuados para el estudio de cualquier sistema en estado de equilibrio.

Densidad y volumen específico
-----------------------------

A continuación se considera la definición de algunas magnitudes que ya han sido utilizadas en los estudios realizados con anterioridad y de las que se tendrá que hacer uso en Termodinámica.

La densidad de una sustancia se define como la masa por unidad de volumen y se designa
por :math:`\rho`:

.. math::

   \rho = \lim_{\Delta V \rightarrow \Delta V'} \frac{\Delta m}{\Delta V}

en que :math:`\Delta V'` es el volumen más pequeño compatible con la idea de distribución continua de materia, y ésta es la condición que ha de cumplirse a fin de que esta magnitud sea aplicable en el razonamiento termodinámico.

El volumen específico se define como volumen por unidad de masa y, por tanto, es la inversa de la densidad:

.. math::

   v = \frac{1}{\rho}

Como sistema de unidades utilizaremos fundamentalmente el S.I., por lo que las unidades de las magnitudes definidas serán el :math:`kg \cdot m^{-3}` y el :math:`m^{-3} \cdot kg^{-1}`, respectivamente.

Presión
-------

Se define la presión *p* en un punto de la superficie límite de un sistema en equilibrio, como la componente normal de la fuerza mecánica ejercida sobre la unidad de área de la superficie en el punto mencionado. Si se designa por :math:`\delta F_n` la componente normal citada y por :math:`\delta A` el elemento de superficie en el entorno del punto sobre el que se ejerce :math:`\delta F_n`, *p* vendrá dada por:

.. math::

   p =  \lim_{\Delta A \rightarrow \Delta A'} \frac{\Delta F_n}{\Delta A}

en la que :math:`\Delta A'` es el elemento de superficie más pequeño compatible con la hipótesis de distribución continua de materia.

La definición de *p* enunciada también se aplica en el interior de un fluido.

Conviene destacar que, ya que un fluido en equilibrio no puede soportar esfuerzos tangenciales, la única fuerza que actúa sobre un elemento de área :math:`\Delta A` en un punto de la frontera, es normal a la mencionada superficie.

De forma análoga, la fuerza que actúa sobre un área :math:`\Delta A` en un punto del interior de un fluido en equilibrio, es normal al área e independiente de la orientación de dicha superficie, por lo que la presión en cualquier punto en una superficie, en el interior de un fluido en equilibrio, depende solamente de la posición de :math:`\Delta A` y no de la orientación. A este tipo de presión se la suele denominar hidrostática y se simboliza con la letra *p*.

Como consecuencia de lo dicho, resulta evidente que en ausencia de campos de fuerza o paredes rígidas interiores, la presión de un fluido en equilibrio, es uniforme sobre su límite y en el interior del mismo.

En ingeniería es normal que la presión de un sistema se mida respecto a la atmosférica (:math:`p_{atm}`) en vez de hacerlo respecto al vacío, denominándose entonces presión manométrica, :math:`p_{man}`. En la figura 1.2 se representa un esquema del sistema utilizado frecuentemente en la determinación de la presión y de ella se deduce con facilidad:

.. math::

   p_a = p_{man}+p_{atm}


.. figure:: ./img/presion_absoluta_manometrica.png
   :width: 70%
   :align: center

   Relación entre presión absoluta :math:`p_a` y presión manométrica :math:`p_{man}`



Es preciso insistir en que la magnitud que utiliza la termodinámica es la presión absoluta (que es la que define el estado del sistema) y no la manométrica, por lo que hay que ser muy cuidados a la hora de utilizar esta magnitud.

La determinación de la presión mediante la lectura de una columna de líquido, como indica la figura 1.2, es el fundamento de muchos instrumentos utilizados para la medida de presiones. Para evaluar los cambios de presión dentro del fluido, en presencia del campo gravitatorio, se hace un balance de fuerzas en un elemento de la columna fluida, como se muestra en la figura 1.3.


.. math::

   p_z \delta A &= p_{z+dz} \delta A + \rho g \delta A dz\\
   p_z &= p_{z+dz} + \rho g dz\\
   -dp &= \rho g dz\\
   p_2-p_1 &= \delta p = - \rho g (z_2-z_1)


.. figure:: ./img/elemento_columna.png
   :width: 70%
   :align: center

   Elemento de columna de fluido en el campo gravitatorio

Esta ecuación define la diferencia de presión entre dos puntos de una columna de fluido en el campo gravitatorio, supuesto que :math:`\rho` y *g* se mantengan constantes.

Cuando la presión del recinto en el que se efectúa la medición es inferior a la atmosférica, se suele hablar de presión de vacío. La relación entre ellas se muestra en la figura 1.4.


.. figure:: ./img/relacion_presiones.png
   :width: 70%
   :align: center

   Relación entre las presiones absoluta, manomètrica y de vacío

En el sistema internacional la presión se expresa en pascales:

.. math::

   1Pa = 1N \cdot m^{-2}

pero debido a la pequeñez de esta unidad se utiliza el :math:`kPa = 10^3 Pa` y el :math:`MPa= 10^6 Pa`.

Aunque no sea del sistema internacional, es frecuente expresar la presión en bares (:math:`1bar = 10^5 Pa`). La presión atmosférica estándar es:  :math:`1,01325 bar`.

Temperatura y Ley Cero
----------------------

Debido al papel fundamental que la temperatura juega en el estudio de la termodinámica, es conveniente considerar ahora con cierto detenimiento esta magnitud, aunque una definición completa no se pueda obtener hasta abordar el estudio del segundo principio.

La noción de temperatura es compleja y a lo largo de nuestro estudio la veremos evolucionar y completarse. En esta parte se proporciona una noción experimental de temperatura. Fundamentalmente se establece una escala práctica de temperatura, así como los instrumentos utilizados para su aplicación.

Noción intuitiva de temperatura
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

La sensación táctil de caliente y frío proporciona la primera aproximación experimental a la noción de temperatura, y se dice que un cuerpo caliente tiene mayor temperatura que un cuerpo frío. No obstante, esta noción resulta insuficiente a la hora de proceder a una evaluación cuantitativa de esta magnitud ya que ni siquiera es capaz de establecer, a partir de ella, un criterio de igualdad (recuérdese la distinta sensación producida por el contacto con un trozo de hierro o un trozo de corcho o madera, mantenidos en un mismo ambiente frío). Debido a esto, es preciso revestir adecuadamente estas sensaciones de caliente y frío a fin de convertirlas en conceptos cuantitativamente manejables. Para ello se establecen las definiciones de pared diatèrmica, pared adiabática y equilibrio térmico.

Pared diatérmana y pared adiabática. Equilibrio térmico
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Considérese la experiencia siguiente, esquematizada en la figura 1.5: dos recipientes de paredes rígidas A y B contienen el mismo gas con la misma densidad p y presiones distintas :math:`P_A` y :math:`P_B` respectivamente. Los recipientes se encuentran inicialmente separados, sin que pueda suponerse ninguna influencia entre ellos. A continuación se aproximan entre sí, hasta conseguir el contacto físico. Una vez alcanzado dicho contacto pueden ocurrir dos cosas:

.. figure:: ./img/pared_adiabatica_diatermica.png
   :width: 80%
   :align: center

   Definición de pared adiabática y pared diatérmana

a)	que la presión inicial en cada uno de los recipientes se mantenga después de un tiempo suficientemente largo, de forma que :math:`p_{A}'' = p_{A}'` y :math:`p_{B}'' = p_{B}'`.

b)	que la presión vaya cambiando y después de un tiempo suficientemente largo :math:`p_A'' = p_B''`.

En el caso a) se dice que:

- los dos sistemas no están en contacto térmico.
- las paredes del recipiente están formadas por una sustancia que es un aislante térmico.
- las paredes se denominan adiabáticas

Si lo que se produce es el proceso b):

- los dos sistemas están, por definición, en contacto térmico.
- los recipientes están formados por una sustancia que se dice es conductora térmica.
- las paredes se denominan diatérmanas o diatérmicas.

En este último caso los sistemas A y B se hallan, por definición, en equilibrio térmico una vez alcanzado un estado que se mantiene independientemente del tiempo. Puede constatarse la existencia de equilibrio térmico porque, una vez alcanzado éste y aislado el conjunto del exterior, la presión no cambia.

Relacionado con la definición de pared diatérmana se tiene el concepto de conductor térmico los sistemas que llegan al equilibrio térmico cuando se separan mediante paredes diatérmicas, es decir, cuando se ponen en contacto térmico, son conductores térmicos. Los metales, especialmente la plata y el cobre, y los gases, sobre todo el helio, son conductores térmicos. Estas sustancias pueden ser utilizadas como elementos de ensayo para distinguir entre superficies diatérmanas y adiabáticas. Experimentalmente se ha visto que las paredes que permiten el contacto térmico entre dos sistemas (sustancias) determinados, también lo permiten entre otros cualesquiera.

Hay sistemas (generalmente son sólidos como el amianto, la lana de vidrio, cierto tipo de plásticos, etc.), que cuando se les rodea de paredes diatérmanas, no alcanzan el equilibrio térmico con su medio ambiente, o tardan un tiempo excesivamente largo en alcanzarlo. A estos sistemas se les denomina aislantes térmicos o malos conductores térmicos. Estos materiales se utilizan para conseguir paredes adiabáticas (casi adiabáticas).

Según lo que se acaba de ver, el contacto térmico entre un sistema y su medio ambiente o un sistema y otro, viene determinado sólo por la naturaleza de las paredes que lo separan.

Ahora bien, para que se alcance el equilibrio térmico en un tiempo prudencial, es preciso que el sistema sea buen conductor térmico.

Téngase en cuenta que ningún material proporciona una pared que sea realmente adiabática
o diatérmana. Por lo tanto, la consideración de pared adiabática o diatérmana depende del intervalo de tiempo en el que se considera el proceso. Para procesos rápidos casi todas las paredes serán adiabáticas y para procesos lentos las paredes se comportarán como diatérmanas. Si las velocidades son intermedias, una pared metálica será diatérmana y un recipiente recubierto por lana de vidrio o poliuretano será adiabático.

Principio Cero de la Termodinámica
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Considérese que se dispone de tres sistemas, cuyas propiedades pueden medirse mediante la instrumentación adecuada, limitados por paredes diatérmanas, rígidas e impermeables. Para concretar, supóngase que son gases confinados en un volumen determinado, cuya masa y presión se puede determinar. Los tres sistemas se hallan dispuestos en el interior de un recipiente aislado y, mediante tabiques adiabáticos móviles, se aíslan unos de otros.

Mediante el desplazamiento del tabique que separa A y B, se permite que estos establezcan contacto térmico. Si las propiedades de A y B no cambian después de que este contacto térmico se produzca, puede decirse que A y B están en equilibrio térmico. De forma análoga, se puede establecer el contacto térmico entre A y C, y si se ve que tampoco hay variación en las propiedades, se dice que hay equilibrio térmico entre A y C.

Una vez realizados los procesos anteriores, si se ponen en contacto térmico B y C, se observa que tampoco se producen modificaciones en las propiedades de estos sistemas, por lo que se puede afirmar que también se encuentran en equilibrio térmico.

.. figure:: ./img/pared_adiabatica_diatermica.png
   :width: 80%
   :align: center

   Principio Cero de la Termodinámica

La generalización de estos resultados constituye el *Principio Cero de la Termodinámica*, que puede ser enunciado de la forma siguiente:

**Si dos sistemas se encuentran, por separado, en equilibrio térmico con
un tercero, se encuentran en equilibrio térmico entre sí.*

.. note::

   1 Enunciado por R.H.Fowler en 1931.

Concepto de temperatura
'''''''''''''''''''''''

Si varios sistemas están en equilibrio térmico deben tener alguna característica o propiedad en común y a esta propiedad común la denominamos *temperatura*.

Aunque la esencia de este concepto sólo se alcanza a través de la teoría cinético-molecular de la materia o a partir del segundo principio de la termodinámica y de la mecánica estadística, tomando como base el Principio Cero de la Termodinámica se pueden obtener métodos que permiten operar con esta magnitud. Es decir, el Principio Cero permite definir una escala empírica de temperaturas. Para conseguir esto se pueden considerar las experiencias que se describen a continuación.

Se toman dos sistemas, A y B, en equilibrio térmico. Las propiedades elegidas para caracterizar su estado tendrán unos valores determinados que, suponiendo sistemas simples (como después se verá, son aquéllos que interaccionan mediante una sola forma de trabajo), se pueden designar por los conjuntos :math:`(X_1^A, Y_1^A)` y   :math:`(X_1^B, Y_1^B)`  para cada sistema. Estas parejas de valores se pueden representar en un sistema de ejes adecuados como se indica en la figura 1.7.

.. figure:: ./img/isotermas.png
   :width: 100%
   :align: center

   Definición de isotermas

.. note::

   2 La función termometrica que dió lugar a esta escala es una función lineal del tipo 0 = a - X -f b, en que los dos puntos fijos necesarios para caracterizarla son la temperatura del hielo en equilibrio con agua líquida (0 = 0°C) y la temperatura del vapor en equilibrio con agua líquida (0 = 100°C), a la prseión atmosférica estándar.

Se puede variar el estado del sistema A, manteniendo el contacto térmico con B, de forma que se garantice la existencia de equilibrio térmico. La experiencia muestra que existen parejas de valores :math:`(X_i^A, Y_i^A)` con :math:`i = 2, 3,...`, correspondientes a estados del sistema A en equilibrio térmico con el estado original del sistema B, y por tanto, en equilibrio térmico entre sí. Se denomina *isoterma* al lugar geométrico de los puntos :math:`(X_i^A, Y_i^A)` que corresponden a estados de un sistema en equilibrio térmico entre sí. La curva I de la figura 1.7 puede ser una de estas isotermas.

Repitiendo la experiencia con distintos estados iniciales del sistema B, que ha servido de base de comparación, se obtendría una red o conjunto de isotermas del sistema A (curvas I, II y III de la figura 1.7). Procediendo de manera análoga con B, pero tomando ahora el sistema A como referencia, se tendrían ahora las curvas I’ ( estados de equilibrio térmico con los estados I de A), II’ (equilibrio con II) y III’ (equilibrio con III) de la figura 1.7.

Las curvas I y I’ que corresponden a estados de los dos sistemas en equilibrio térmico se denominan *isotermas correspondientes*. Como la propiedad de los sistemas que determina su estado de equilibrio térmico se ha denominado temperatura, se puede decir que los estados representados sobre estas curvas son estados de igual temperatura y por eso el nombre de las curvas.

Escala de temperatura y termómetros
'''''''''''''''''''''''''''''''''''

Se ha visto en el apartado anterior cómo puede obtenerse una familia de isotermas para un sistema determinado y cómo conseguir esto para otros sistemas a partir de ellas. Para establecer una escala de temperatura se tendrá que asignar, de forma biunívoca, un número a cada conjunto (par, en el caso descrito) de isotermas correspondientes. De esta forma se dispondrá de una cuantificación empírica de la magnitud temperatura.

Para medir la temperatura de un cierto sistema, se utilizará el Principio Cero de la termodinámica, es decir, se procede a conseguir el equilibrio térmico entre el sistema mencionado y otro sistema que se tomará como patrón, y al que se denomina *termómetro*.

Es necesario que el termómetro, al ponerse en contacto con el sistema para determinar su temperatura, no modifique apreciablemente el estado del mismo. Si no fuese así, la temperatura que se obtendría sería la del equilibrio termómetro-sistema, distinta de la temperatura inicial del sistema.

A fin de asignar un número a la temperatura correspondiente a cada isoterma de la familia, se recurre al hecho de que alguna o algunas de las propiedades del termómetro varían al vaciar la temperatura de equilibrio termómetro-sistema en observación. Para simplificar el procedimiento, conviene que sea una sola de las propiedades del termómetro la que varíe, para lo que se deben mantener constantes el resto de las que definen su estado. Téngase en cuenta que, si el termómetro se comporta como un sistema simple, cada una de las isotermas viene expresada en función de un par de magnitudes observables como podrían ser *p* y *V*, y en general, cualesquiera parejas de variables que puedan definir el estado del sistema y que se pueden representar por las variables genéricas *X* e *Y*. La forma más simple de efectuar la asignación antes aludida podría ser, entonces, la que se describe a continuación.

Figura 1.8 Red de isotermas

En el plano *XY* de las coordenadas del termómetro, en el que se han representado las isotermas, se elige una trayectoria que podría ser la recta :math:`Y = Y_j`, representada en la figura 1.8. Cada uno de los puntos en los que ésta corta a las isotermas tiene la misma coordenada :math:`Y_1`, pero diferente coordenada *X*, que corresponde a una temperatura diferente. La temperatura asociada a cada isoterma se toma de forma que sea una función cómoda de la X de este punto de intersección. La coordenada *X* se denomina magnitud o propiedad termométrica, y la forma de la función termométrica :math:`\Theta (X)` determina la escala de temperatura. En principio, cualquier función:math:`\Theta = f(X)`  puede asignarse arbitrariamente para establecer la escala.

Existen cinco tipos importantes de termómetros, cada uno de los cuales posee su propia propiedad termométrica, como se indica en la Tabla 1.1. Se podría representar por *X* una cualquiera de las magnitudes termométricas relacionadas en la misma, y se elige arbitrariamente para la temperatura que marca el termómetro, común a todos los sistemas en equilibrio térmico con él, la siguiente función lineal de X:

.. math::

   \Theta (X) = a X \text{ (Y constante)}

siendo *a* una constante arbitraria. Al utilizar esta función para calcular la razón de dos temperaturas en esta escala lineal, se obtiene:

.. math::

   \frac{\Theta (X_1)}{\Theta (X_2)} = \frac{X_1}{X_2}

es decir, la razón de dos temperaturas es igual a la razón de sus correspondientes valores de la magnitud termomètrica *X*.

Tabla 1.1 Tipos importantes de termómetros

Termómetro	Magnitud termometrica	Símbolo
Gas mantenido a volumen constante	Presión	P
Gas mantenido a presión constante Resistencia eléctrica	Volumen	V
(presión y esfuerzo constantes) Par termoeléctrico	Resistencia eléctrica	R
(presión y esfuerzo constantes)	f.e.m. térmica	£
Columna líquida en un capilar de vidrio (presión constante)	longitud	L

Para fijar el valor de la temperatura de un sistema se definió una escala que utilizaba dos puntos fijos con un intervalo entre ellos igual a 100, eligiendo en un principio los puntos de fusión del hielo y ebullición del agua líquida a la presión atmosférica. La escala se suele conocer con el nombre de quien se considera su descubridor, Celsius.

La escala así definida conducía a errores importantes en la determinación de temperaturas muy bajas, por lo que Giauque en 1939 propuso que se definiera una escala de temperatura que tuviera un solo punto fijo y se eligiera arbitrariamente este punto fijo (esto ya había sido sugerido por lord Kelvin en 1854). Esta propuesta de Giauque, apoyada por la mayor parte de los físicos y químicos que trabajaban con bajas temperaturas, fue aprobada en la X Conferencia de Pesas y Medidas celebrada en París en el verano de 1954.

A partir de esta fecha sólo se requiere un punto fijo para la definición de la escala termométrica; este punto fijo es la temperatura y presión para las cuales pueden coexistir en equilibrio hielo, agua líquida y vapor de agua. A este estado se le denomina punto triple del agua. Como temperatura de este punto fijo se ha asignado el valor 273,16 kelvin (abreviado, 273,16K). El kelvin es la unidad de temperatura en el Sistema Internacional.

Si se tiene en cuenta la relación (1.15) y se designa con el subíndice 3 las estados de equilibrio térmico con el punto triple del agua, se obtiene:

.. math::

   \frac{\Theta (X)}{\Theta (X_3)} = \frac{X}{X_3}

y al haberse asignado a :math:`\Theta (X_3)` el valor 273,16 se obtiene:


.. math::

   \Theta (X) = 273,16 \frac{X}{X_3} K \text{ (Y constante)}

Al ser el punto triple del agua el único punto fijo en termometria, es importante disponer de una fuente térmica a esta temperatura. Para conseguirla se utiliza un recipiente como el esquematizado en la figura 1.9.

Figura 1.9 Esquema de la fuente térmica del punto triple del agua

El recipiente se llena prácticamente con agua destilada perfectamente desgasificada y desionizada; después se hace el vacío, de forma que cuando se cierre sólo contenga agua líquida y vapor de agua. Una vez en estas condiciones, se sitúa en la cavidad central una mezcla frigorífica, con lo que se consigue formar hielo sobre las paredes interiores del recinto al congelarse el agua contenida en el mismo. Posteriormente, se elimina la mezcla frigorífica y en su lugar se sitúa la ampolla del termómetro, con lo que se fundirá una delgada película en contacto con la pared. En estas condiciones quedarán en equilibrio las tres fases (hielo, agua líquida y vapor de agua). Mientras esto suceda tendremos la seguridad de que el recinto se encuentra en el punto triple.

Tipos de termómetros. Comparación
'''''''''''''''''''''''''''''''''

Aplicando a los distintos tipos de termómetros el procedimiento que se termina de describir, se dispone de cinco posibilidades de realizar la determinación de temperatura de un sistema dado. Cada una de éstas conduce al resultado siguiente:


.. math::

   \Theta (p) &= 273,16 \frac{p}{p_3} K \text{ (V constante)}\\
   \Theta (V) &= 273,16 \frac{V}{V_3} K \text{ (p constante)}\\
   \Theta (R) &= 273,16 \frac{R}{R_3} K \text{ (esfuerzo constante)}\\
   \Theta (\epsilon) &= 273,16 \frac{\epsilon}{\epsilon_3} K \text{ (esfuerzo constante)}\\
   \Theta (L) &= 273,16 \frac{L}{L_3} K \text{ (p constante)}

La definición de los cinco posibles tipos de termómetros no resuelve el problema de la determinación de temperatura, ya que si se utilizaran los cinco termómetros simultáneamente en la medida de la temperatura de un sistema determinado, se observarían bastantes discrepancias en los resultados obtenidos con cada uno de los termómetros, dependiendo del intervalo en el que se estuviese midiendo. Aún más, si se eligiese el mismo tipo de termómetro, pero utilizando como sustancia termométrica distintas materias, también se encontrarían diferencias, en algunos casos notables. No obstante, hay termómetros con los que se obtienen resultados más reproducibles, como son los que utilizan gases a presiones moderadas, especialmente :math:`H_2` y :math:`He`. Debido a esto, los gases son las sustancias termométricas más ampliamente utilizadas, y será este tipo de termómetro el que se describirá a continuación. En el libro de **Zemansky4**, se puede encontrar una buena información sobre tipos de termómetros y determinación de temperaturas.

Termómetro de gas a volumen constante
-------------------------------------

La figura 1.10 muestra un esquema muy simplificado de un termómetro de gas a volumen constante. Los materiales, construcción y dimensiones varían de unos laboratorios e institutos nacionales a otros, dependiendo de la naturaleza del gas y del intervalo de temperaturas que se intenta medir. En esta figura, el gas se halla contenido en el depósito B, que comunica con la columna de mercurio M a través de un capilar. El volumen del gas se mantiene constante modificando la altura de la columna M hasta que el nivel de mercurio toque exactamente el índice en el espacio situado encima de M, denominado "espacio muerto" o "volumen perjudicial". Se varía el nivel de la columna M subiendo o bajando el tubo M’ unido a M mediante un tubo flexible.


.. note::

   3A1 comportarse el líquido como un fluido incompresible, esta condición no influye apreciablemente en la lectura.

   4M.W.Zemansky & R.H.Dittman Calor y Termodinámica 1981 McGraw-Hill USA.


Figura 1.10 Termómetro de gas a volumen constante

Para realizar la determinación de :math:`\Theta`, se mide la diferencia de niveles *h*, entre las dos columnas de mercurio M y M’, cuando el depósito del termómetro B está rodeado por el sistema cuya temperatura se va a medir y cuando se halla rodeado de agua en el punto triple. Es evidente que la presión del gas en cualquier caso está dada por:

.. math::

   p = p_{atm}+-\rho g h

utilizando el signo + cuando el extremo superior de M’ está por encima del de M.

Las lecturas de presión han de corregirse debido a diversas causas de error, entre las que se pueden citar: la presencia de gas en diversos espacios muertos, en los que el gas se encuentra a temperatura distinta que en B; presencia de gradientes de temperatura y presión en el capilar que une B con el medidor de presión, etc. Algunas de estas causas son corregibles por diseño y otras son evaluables, por lo que el valor de *p* se puede determinar con bastante precisión. Este valor de *p* corregido es el que se lleva a la fórmula correspondiente y mediante ella se calcula :math:`\Theta (p)`:

.. math::

   \Theta (p) = 273.16 \frac{p}{p_3} K

donde *p* y :math:`_3` son las lecturas obtenidas llevando el termómetro en contacto con el sistema cuya temperatura se quiere determinar y la fuente en el punto triple, respectivamente.

Si se utilizaran distintos gases en la determinación de la temperatura de un determinado sistema con este tipo de termómetro, se encontrarían diferencias, por lo que es necesario encontrar otro procedimiento para evaluar esta magnitud que no dependa del instrumento o sustancia de trabajo utilizada. Esto se consigue mediante la escala de gas ideal.

Temperatura en la escala de gas ideal
'''''''''''''''''''''''''''''''''''''

Como se ha dicho y experimentalmente puede comprobarse, al realizar la determinación de la temperatura de un sistema con un termómetro de gas a volumen constante, utilizando distintos gases, los resultados obtenidos son distintos. No sólo ocurre esto, sino que utilizando cantidades distintas de masa de gas termométrico en el termómetro de volumen constante se obtienen resultados distintos según la cantidad de masa de gas que se ponga en el termómetro.

En la figura 1.11 se han representado los datos experimentales obtenidos al calcular la temperatura de ebullición normal del agua utilizando un termómetro de gas a volumen constante utilizando distintos gases y distintas masas para cada gas, como refleja el valor diferente de presión en el punto triple. Es decir, cuanto menor masa tiene el termómetro, menor es el valor de la presión de vapor en este punto.

Es importante destacar el hecho de que, según disminuye la masa de gas en el termómetro, los valores de temperatura indicados por los distintos gases se van aproximando. En el límite, cuando la presión en el punto triple se anula (valor que en la realidad coincidiría con la anulación del gas), los datos de los cinco termómetros coinciden. Basándose en este hecho se establece la definición de la escala de gas ideal, que puede resumirse en la ecuación:

.. math::

   T = 273,16 \lim_{p_3 \rightarrow 0} \left( \frac{p}{p_3} \right) K

Figura 1.11 Punto de ebullición del agua en función del tipo de gas y masa del mismo, en el termómetro

La necesidad de independencia de la lectura de temperatura de la naturaleza del gas con el que se efectúe la determinación al utilizar esta escala, obliga a utilizar el termómetro de acuerdo con el método sugerido anteriormente al citar los resultados experimentales. Es decir, cada medición de temperatura obliga a realizar un conjunto de determinaciones utilizando cada vez menos cantidad de gas, hasta que la sensibilidad de los instrumentos lo permitan, y extrapolar los resultados a presión cero.

Lo dicho anteriormente indica que la escala de gas ideal no resulta una escala cómoda de aplicar en las determinaciones prácticas de temperatura, por lo que se la ha sustituido por una escala práctica que permite realizar las medidas con comodidad. Esta es la escala internacional de temperatura, cuya última versión es la de 1990.

Escala Internacional de Temperatura
'''''''''''''''''''''''''''''''''''

Para evitar la molestia que conlleva la utilización de la escala de gas ideal se utiliza una serie de termómetros secundarios, cuya calibración se realiza basándose en la escala de gas ideal. Para ello, se divide la escala de temperatura en intervalos y en cada uno se utiliza un termómetro secundario con funciones que relacionan los valores medidos con este termómetro y los correspondientes valores de la escala de gas ideal.

La última versión de la ESCALA INTERNACIONAL DE TEMPERATURA es la correspondiente a 1990 (ITS-90). Esta escala se extiende desde 0,65 K a las temperaturas más altas que pueden medirse utilizando un método óptico. En los intervalos más bajos utiliza, o bien un termómetro de gas He, o bien la determinación de temperatura basada en las relaciones presión de vapor-temperatura para 3He y 4He. Entre 14 K y 904 K utiliza un termómetro de resistencia de platino y un polinomio que expresa T en función de R (resistencia eléctrica) y cuyas constantes se calculan utilizando distintos puntos fijos determinados con la escala de gas ideal. Desde 904 a 1338 K, se emplea un termopar de platino platino-rodio y el correspondiente polinomio y puntos fijos de referencia. Por encima de esta temperatura se recurre a la pirometría óptica.

Normalmente, la calibración de los instrumentos utilizados en la determinación de temperatura se basa en esta escala, mucho más fácil de aplicar que la del gas ideal, y en su definición se ha cuidado de que las diferencias se hallen dentro de la sensibilidad de los instrumentos utilizados.


EJERCICIOS
-----------

Ejercicio 1.1 Para estudiar el comportamiento termodinàmico del congelador de su frigorífico:

a) ¿Qué consideraría como sistema?
b) ¿El sistema es abierto ocerrado?
c) ¿De qué tipo son los límites del mismo?
d) ¿Qué elementos integran su medio ambiente?

Ejercicio 1.2 Se debe estudiar termodinàmicamente el llenado de una botella de gas:

a) Seleccione el sistema adecuado y responda a las preguntas del ejercicio anterior,
b) Considere, sucesivamente, un sistema abierto y uno cerrado.

Ejercicio 1.3 De las siguientes propiedades, diga cuál es intensiva y cuál extensiva:

a) Volumen,
b) Densidad,
c) Indice de refracción.
d) Y = A - B / C (en la que A, B y C son propiedades extensivas).
e) Z = H - p / G (en la que H y G son variables extensivas y p una variable intensiva).

Ejercicio 1.4 De las expresiones siguientes, determine cuál o cuáles corresponden a propiedades termodinámicas y cuál o cuáles no, si x e y son variables de estado y a y b constantes:

a) z = a- x- y + b- y
b) z = a- b- x/y2
c) z = a -x / y

Ejercicio 1.5 En la figura se esquematizan dos cilindros adyacentes provistos de un émbolo doble adaptado a los cilindros. El manómetro M marca 945 kPa, y los diámetros interiores de los cilindros pequeño y grande son 20 cm y 60 cm, respectivmente. La presión atmosférica posee un valor de 100 kPa:

a) Determínese la presión en B.
b) ¿Cuál será la posición de la columna de mercurio en el manómetro en U conectado en B?

Nota: Cuando el manómetro en U está sin conectar, el mercurio alcanza 50 cm en cada
rama.

Ejercicio 1.6 En un sistema dado, tras un proceso,la presión se hace el doble de la inicial. Si al comienzo de dicho proceso la presión manométrica es 104 Pascal, ¿cuál sería la presión manométrica final? Coméntese la respuesta.

Ejercicio 1.7 En un depósito de 40 m3 hay 60 kg de un determinado gas. Mediante un tabique que ajusta herméticamente, se divide el depósito en dos partes iguales. El gas contenido en una de las partes se introduce en otro depósito, comprimiéndolo, hasta ocupar 1 m3, mientras que el gas de la otra mitad se expande hasta llenar por completo el depósito inicial. Determínense las densidades finales del gas en ambos recintos.

Ejercicio 1.8 ¿Cuál será la temperatura doble correspondiente a 25 °C?

Ejercicio 1.9 A continuación se muestran las lecturas obtenidas con un termómetro de gas a volumen constante, correspondientes a la determinación de las temperaturas de dos sistemas A
y b.

Sistema A:

Sistema B:
p(mbar)	1.200	1.000	800	600	400	200
p3(mbar)	634,4	552,5 459,7		357,1	245,4	125,8
p (kPa)	60,0	50,0 40,0	30,0	20,0	10,0
P3 (kPa)	39,5	34,2 28,4	21,9	14,9	7,57

Determínense dichas temperaturas.
