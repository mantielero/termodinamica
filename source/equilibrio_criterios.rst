Criterios de equilibrio
-----------------------

Decimos que un sistema no está en equilibrio termodinámico cuando los valores de sus coordenadas termodinámicas son distintos de los correspondientes al equilibrio en la situáción considerada. La ecuación deducida del primero y segundo principios en su forma más general:

.. math::

   TdS \geq dU - \sum Y_k dX_k
   
en la que :math:`Y_k` representa una fuerza generalizada (presión, tensión superficial, fuerza electromotriz, etc.) y :math:`dX_k` la variación de un desplazamiento generalizado (variación de volumen, superficie , carga eléctrica, etc.), nos permite obtener condiciones generales de equilibrio termodinámico y de estabilidad.
Teniendo en cuenta que el estado de los sistemas termodinámicos se define, no solamente por los parámetros específicamente termodinámicos (temperatura, entropía, etc), sino también por los correspondientes parámetros mecánicos (presión, volumen) y químicos, las condiciones de equilibrio dependerán del tipo de interacción entre sistema y medio ambiente.

Determinemos las Condiciones de equilibrio y estabilidad de los sistemas termodinámicos de masa constante, en las situaciones que se presentan con mayor frecuencia.

a) Sistema aislado (esto es, cerrado) (U = constante, V = constante)	
Para este sistema, suponiendo que sólo consideramos trabajo pdV y para una transformación en condiciones alejadas del equilibrio (irreversible), la desigualdad fundamental (8.16) nos lleva a:

.. math::

   TdS > dU + pdV
   
por lo que, al ser :math:`dU= 0` y :math:`dV = 0`:

.. math::

   TdS > 0

es decir, cuando un sistema aislado evoluciona irreversiblemente, la entropía aumenta. Si la entropía tiende a incrementarse, la evolución no cesará hasta que se alcance un valor máximo, momento en el que habrá llegado al equilibrio.

Por lo tanto, la condición general de equilibrio estable de un sistema aislado es que la entropía sea máxima. Si llamamos :math:`S_o` a la entropía del sistema en equilibrio y S a la
entropía en cualquier otro estado, tendremos que:

.. math::

   \Delta S = S-S_o<0
   
o también:

.. math::

   dS= 0 \\
   d^2 S<0


La anulación de la primera diferencial de la entropía no es más que la condición de extremo, pero no asegura la condición de máximo. La condición suficiente de máximo de entropía es el valor negativo de su segunda diferencial, que asegura la estabilidad del equilibrio.

A fin de aclarar lo que acabamos de ver, tengamos en cuenta que, cuando se estudia un sistema en estado de equilibrio, se ve que los valores de las propiedades no permanecen exactamente constantes, sino que se presentan ciertas desviaciones en el valor de las que definen este estado y a estas variaciones en el valor de las propiedades se les denomina fluctuaciones. Las fluctuaciones generan perturbaciones del estado de equilibrio, de tal forma que, si este equilibrio no es estable el sistema se alejaría de dicho estado. Por ello, si queremos que el estado de equilibrio sea un estado de equilibrio estable el valor de la entropía debe ser máximo, ya que al presentarse fluctuaciones éstas siempre llevarán al sistema a un estado situado en las proximidades del estado de partida, que tendrá una entropía menor. Como la evolución espontánea siempre se produce con un aumento de entropía, el sistema recuperaría el valor máximo de entropía.

De lo dicho anteriormente se deduce que la condición (8.19 a) es una condición necesaria y suficiente de estabilidad.

b)	Sistemas isotermos e isocoros (T = constante,  V = constante)

Recordemos que paradas-variables V y T el potencial termodinámico correspondiente es la función de Helmholtz. Podemos ver cómo este potencial se utiliza para definir los criterios de equilibrio y estabilidad en sistemas que evolucionan a T y V constantes, sin más que aplicar la ecuación deducida del primer y segundo principios, para transformaciones no reversibles, de la siguiente forma:

.. math::

   dU < TdS - pdV \\
   d(TS) = TdS + SdT
   
restando (8.21) de (8.20):

.. math::

   d(U - TS) = dA < -pdV - SdT
   
por lo que para V y T constantes:

.. math::

   dA <0

es decir, el potencial de Helmholtz en un sistema isotermo a volumen constante, que experimenta una transformación irreversible, tiende a disminuir, por lo tanto la transformación cesará cuando este potencial alcance un valor mínimo.

Esta condición podemos expresarla mediante las relaciones:

.. math::

   \Delta A > 0

o

.. math::

   dA = 0\\
   d^2A>0
   

en la que :math:`dA = 0` es la condición necesaria de equilibrio y :math:`d^2A>0` es la condición suficiente de estabilidad de un sistema isotermo - isócoro.


c)	Sistema isotermo e isóbaro (T = constante, p = constante)

El potencial termodinamico para las variables T y p es el de Gibbs. Para este potencial y procesos irreversibles, teniendo en cuenta la desigualdad anterior:

.. math::

   dA < —SdT — pdV
y

.. math::

   d(pV) = pdV + Vdp

Sumando (8.25) y (8.26) obtenemos:


.. math::

   d(A + pV) = dG < Vdp - SdT
   
por lo que para un sistema mantenido a p y T constantes:

.. math::

   dG < 0

Es decir, para este tipo de sistemas se produce una disminución de G cuando experimentan una transformación irreversible, por lo que la transformación cesará, llegando a un punto de equilibrio, cuando G alcance un valor mínimo.

De forma análoga a lo visto antes, tendremos como condición general de equilibrio y estabilidad:

.. math::

   \Delta G > 0
   
o

.. math::

   dG = 0 \\
   d^2 G >0

en la que :math:`dG = 0` es la condición de equilibrio y :math:`d^2G > 0` es la condición de estabilidad.

d)	Sistemas a S y p constantes

Para un sistema a S y p constantes es fácil demostrar, utilizando un método por completo análogo al seguido en los casos anteriores, que:

.. math::

   \Delta H > 0
   
o bien

.. math::

   dH = 0 \\
   d^2H > 0

es decir, en el estado de equilibrio estable la entalpia es mínima.

e)	Sistemas a S v V constantes

En el caso de sistemas a S y V constantes:

.. math::

   \Delta U > 0
   
o bien

.. math::

   dU = 0 \\
   d^2U > 0
   

para este tipo de sistemas el equilibrio estable se consigue cuando la energía interna es mínima.