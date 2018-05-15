Introducción
============


Índice::

   5.1.- Introducción.
   5.1.1.    - Relación entre la variación de propiedades en un sistema cerrado y un sistema abierto.
   5.1.2.    - Conservación de la masa..

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


OTRO
----

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
