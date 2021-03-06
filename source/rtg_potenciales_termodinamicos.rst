Potenciales termodinámicos o funciones características
------------------------------------------------------

Se denominan ‘potenciales termodinámicos o funciones características a las funciones que proporcionan una descripción completa del estado termodinámico del sistema. En el caso de sis-jtemas compresibles simples, en los que sólo son necesarias dos variables independientes para identificar su estado, las fondones características pueden tomar cualesquiera de las formas siguientes:

.. math::

   u&=u(s,v)\\
   h&=h(s,p)\\\
   a&=a(T,v)\\
   g&=g(T,p)

Expresadas estas funciones mediante las variables indicadas, tienen la importante propiedad de que nos permiten calcular a partir de cada una de ellas cualquier magnitud termodinámica que nos interese.

Consideremos el caso de :math:`u = u(s, v)`. Por ser función de estado, tendremos:

.. math::

   du = \left( \frac{\partial u}{\partial v}\right)_s dv + \left( \frac{\partial u}{\partial s}\right)_v ds

La ecuación de Gibbs (3.23) referida a la unidad de masa o de cantidad de sustancia, nos da:

.. math::

   du = Tds -p dv

Identificando términos equivalentes:

.. math::

   \left( \frac{\partial u}{\partial v}\right)_s = -p \\
   \left( \frac{\partial u}{\partial s}\right)_v  = T

Conocidas u, s, v, p, y T podemos calcular sin dificultad h, a, g y otras magnitudes que puedan interesar, como son :math:`c_v` y :math:`\kappa_s`:

.. math::

   \left( \frac{\partial^2 u}{\partial v^2}\right)_s &= \left( \frac{\partial p}{\partial v}\right)_s &= \frac{1}{k_s v}\\
   \left( \frac{\partial^2 u}{\partial s^2}\right)_s &= \left( \frac{\partial T}{\partial s}\right)_v = \frac{T}{c_v}


Como aplicación de lo expuesto anteriormente consideremos el siguiente ejercicio:


Ejercicio E6.1
^^^^^^^^^^^^^^

Para un determinado sistema se ha encontrado que la relación entre la energía interna y el volumen del mismo puede expresarse por la función:

.. math::

   U = AS^2V^{-1} exp (S/B)

En la que A y B son constantes.

El sistema se somete a una transformación isoentrópica tal que la presión queda reducida a un tercio de la presión inicial, es decir:

.. math::

   \frac{p}{p_o} = \frac{1}{3}

Determínese:

a)	Temperatura final del sistema.
b)	Volumen final.

*******

**Solución**:

Para el sistema indicado en el enunciado nos dan la dependencia funcional de la energía interna con la entropía y el volumen, es decir, nos proporcionan una ecuación característica del sistema. A partir de esta ecuación es posible obtener, para el sistema dado, las expresiones de la presión y temperatura en función de las variables mencionadas:

.. math::

   p &= -\left( \frac{\partial U}{\partial V}\right)_s = AS^2e^{S/B}V^{-2}\\
   T &= \left( \frac{\partial U}{\partial S}\right)_V = 2ASV^{-1} e^{S/B}+\frac{AS^2}{B} V^{-1}e^{S/B}\\
   &= ASV^{-1} e^{S/B}\left[ 2+ \frac{S}{B}\right]


a) Según se índica en el enunciado:


.. math::

   \frac{p}{p_o} = \frac{AS^2 e^{ S/B}V^{-2}}{ AS_o e^{S_o/B}V_o^{-2}} = \frac{1}{3}

También nos indican en el enunciado que el proceso es isoentrópico, por lo que:

.. math::

   s = S_o

Simplificando en (E6.c), obtenemos:

.. math::

   \frac{p}{p_o} = \left( \frac{V_o}{V}\right)^2 = \frac{1}{3}

Para el mismo sistema y proceso, al aplicar (E6.b) se obtiene:

.. math::

   \frac{T}{T_o} = \frac{V_o}{V}


Teniendo en cuenta (E6.d):

.. math::

   \frac{T}{T_o} = \frac{1}{\sqrt{3}}

de donde:

.. math::

   V = \sqrt{3} V_o

b) Sustituyendo (E6.f) en (E6.e), se obtiene:

.. math::

   \frac{V}{V_o} = \frac{1}{\sqrt{3}}

por lo que:

.. math::

   V=\sqrt{3}V_o

Compárense los resultados obtenidos con los que se obtendrían para un gas ideal.

********

De forma análoga si conocemos la dependencia de h en función de s y p, obtenemos:

.. math::

   dh &= \left( \frac{\partial h}{\partial s}\right)_p ds + \left( \frac{\partial h}{\partial p}\right)_s dp \\
   dh &= Tds + vdp

por lo que:

.. math::

   \left( \frac{\partial h}{\partial s}\right)_p = T \\
   \left( \frac{\partial h}{\partial p}\right)_s = v

Si disponemos de h, s, p, T y v, podemos determinar las restantes funciones termodinámicas.

Supongamos que lo que nos dan es :math:`a` en función de T y v:

.. math::

   da &= \left( \frac{\partial a}{\partial v}\right)_T dv + \left( \frac{\partial a}{\partial T}\right)_v dT \\
   da &= -pdv -s dT

por lo tanto:

.. math::

   \left( \frac{\partial a}{\partial v}\right)_T = -p\\
   \left( \frac{\partial a}{\partial T}\right)_v = -s

Teniendo los valores de a, T, v, p y s, es posible determinar cualquier otra magnitud termodinámica que nos interese.

También conocida g en función de p y T podríamos determinar cualquier otra magnitud termodinámica, ya que:	.

.. math::

   dg &= \left( \frac{\partial g}{\partial p}\right)_T dp + \left( \frac{\partial g}{\partial T}\right)_p dT \\
   dg &= vdp -s dT

de donde:

.. math::

   \left( \frac{\partial g}{\partial p}\right)_T &= v\\
   \left( \frac{\partial g}{\partial T}\right)_p &= -s

Conviene que completen el estudio de las funciones h, a, y g de la misma forma que se ha realizado el estudio de la función u.

Es fácil comprobar que tanto las magnitudes consideradas expresadas en función de otras variables termodinámicas, como cualquier otra magnitud termodinámica expresada en función de variables cualesquiera, no tienen la propiedad de ser funciones características.

***********

El nombre de potenciales termodinámicos que se asigna a las funciones que acabamos de considerar proviene del hecho de que su variación en ciertas condiciones, nos da el trabajo distinto del pdv que puede obtenerse en una determinada transformación.

En efecto, consideremos el caso de la energía interna. A partir del primer principio, supuesto que los cambios de energía mecánica son despreciables, obtenemos:

.. math::

   du = \partial q + \partial w	

Del segundo principio, sabemos que para transformaciones reversibles :math:`\partial q = T ds`, por lo que:

.. math::

   du = T ds + \partial w

Téngase en cuenta que el término :math:`\partial w` incluye tanto el trabajo :math:`-p dv` cómo cualquier otra forma de trabajo cuasiestático ( eléctrico, superficial, químico, etc.) al que representaremos por :math:`\partial w_x` sustituyendo:

.. math::

   du = T ds - p dv + \partial w_x

Si consideramos un proceso a s y v constantes:

.. math::

   du =  \partial w_x

Vemos que la variación de energía intema representa el trabajo distinto del :math:`p dv` que se realiza en una transformación a entropía y volumen constantes.

En el caso de la función de Gibbs, tenemos:

.. math::

   dg = du + p dv + v dp - T ds - s dT


Teniendo en cuenta (6.19), obtenemos:

.. math::

   du + p dv - T ds = \partial w_x

por lo que:

.. math::

   dg = v dp - s dT + \partial w_x

Si consideramos una transformación a p y T constantes:

.. math::

   dg = \partial w_x

De forma análoga podríamos proceder con h y a y su variación a p y s constantes y a v y T constantes, respectivamente, inos daría el trabajo implicado en las transformaciones correspondientes, distinto del :math:`p dv`.

En el caso del potencial dé Helmholtz se nos presenta un caso muy interesante de analizar. Para ello consideremos una transformación a T constante solamente, en vez de una isoterma e isocórica. En este caso:

.. math::

   da &= -pdv -sdT+\partial w_x\\
   da &= -pdv+\partial w_x


Por lo que la variación de la función de Helmholtz nos da el trabajo total (incluido el pdv) que se intercambia en una transformación isoterma.

A esta función también se la denomina, en ciertas publicaciones, *energia libre*. Este nombre proviene de lo que acabamos de ver, es decir, el trabajo total que podemos obtener de un sistema a T constante viene ligado a la variación de a y como :math:`u = a + Ts`, vemos que de la energia interna u sólo una parte a puede ser utilizada, quedando otra parte no disponible para efectuar trabajo, a la que se denomina energia ligada (:math:`Ts`) o termentropia.

De forma análoga podríamos justificar el nombre de entalpia libre, que también se da a la función de Gibbs.


Transformaciones de Legendre
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Como información adicional consideraremos la herramienta matemática que puede utilizarse para la deducción de los distintos potenciales termodinámicos.

Es importante tener en cuenta que los distintos potenciales termodinámicos pueden obte-erse a partir del primero, sin más que utilizar la denominada transformación de Legendre, que ertenece al grupo de las denominadas transformaciones de contacto, estudiadas en teoría de ecuaciones diferenciales.

La transformación de Legendre consiste en la sustitución de alguna o algunas de las variables por su correspondiente derivada conjugada. El resultado es que cualquiera de las funciones obtenidas (transformadas de Legendre) contienen la misma información que la ecuación de partida, pero dependen de variables diferentes. Ello representa una gran ventaja cuando se trata de funciones termodinámicas cuya forma puede cambiarse hasta que se puedan llegar a expresar en función de propiedades directamente mensurables.

Consideremos la forma de proceder al utilizar esta herramienta matemática. Para ellos supongamos que tenemos una expresión diferencial exacta del tipo:

.. math::

   dY = D_1 dX_1 + D_2 dX_2 + D_3 dX_3 + ...

Las correspondientes funciones transformadas de Legendre definen una serie de funciones relacionadas con Y, en las cuales el conjunto de variables utilizado para definir cada una de ellas contiene una o más de las :math:`D_i` (Recuerden que :math:`D_i=\left( \frac{\partial Y}{\partial X_i}\right)_{X_j}`) en lugar de las conjugadas :math:`X_i`. Para una expresión diferencial que tiene n variables existen :math:`2^n-1`  transformaciones posibles de Legendre. Si hay dos variables existirán tres transformadas de Legendre, es decir, si:


.. math::

   dY = D_1 dX_1+D_2dX_2

las transformadas serán:

.. math::

   \tau_1 &= Y - D_1X_1 \\
   \tau_2 &= Y - D_2X_2 \\
   \tau_{12} &= Y - D_1X_1 -D_2X_2

y, por tanto,

.. math::

   d\tau_1 &= DY-D_1dX_1-X_1dD_1 &=D_2dX_2-X_1dD_1 \\
   d\tau_2 &= DY-D_2dX_2-X_2dD_2 &=D_1dX_1-X_2dD_2 \\
   d\tau_{12} &= DY-D_1dX_1-X_1dD_1-D_2dX_2-X_2dD_2 &= -X_1dD_1-X_2dD_2

Concretando para el caso de la energía interna:

.. math::

   dU = T dS - p dV \\
   U \Rightarrow Y, T\Rightarrow D_1, X_1 \Rightarrow S, D_2 \Rightarrow -p, X_2 \Rightarrow V \\
   \tau_1 = U - TS\\
   \tau_2 = U+pV \\
   \tau_3 = U - TS + pV

Que corresponden a las funciones de Helmholtz, entalpia y Gibbs, respectivamente.

Relaciones de Maxwell
---------------------

Las funciones características expresadas en función de sus variables naturales proporcionan un medio para caracterizar por completo el estado termodinámico de un sistema, también estas funciones, por el hecho de ser sus diferenciales exactas, permiten la deducción de relaciones entre propiedades termodinámicas que son de gran interés en el estudio de los sistemas termodi-námicos. Recordemos que para sistemas compresibles simples:

.. math::

   du &= Tds -pdv \\
   dh &= Tds + vdp \\
   da &= -pdv -sdT \\
   dg &= vdp -sdT


Por la igualdad de las derivadas cruzadas:

.. math::

   \left( \frac{\partial T}{\partial v}\right)_s &= -\left( \frac{\partial p}{\partial s}\right)_v \\
   \left( \frac{\partial T}{\partial p}\right)_s &= \left( \frac{\partial v}{\partial s}\right)_p \\
   \left( \frac{\partial p}{\partial T}\right)_v &= \left( \frac{\partial s}{\partial v}\right)_T \\
   \left( \frac{\partial v}{\partial T}\right)_p &= -\left( \frac{\partial s}{\partial p}\right)_T \\

Estas son las denominadas relaciones de Maxwell.

Una regla nemotécnica que nos permite recordar con facilidad las relaciones anteriores, es la siguiente. Dispongamos las cuatro magnitudes que intervienen en estas relaciones en orden alfabético, formando una seudomatriz, y con ella deducimos la relación funcional como se indica a contmuacion.

.. math::

   \begin{vmatrix}
     p & s\\
     T & v
   \end{vmatrix}
   \rightarrow
   \left( \frac{\partial p}{\partial T}\right)_v = \left( \frac{\partial s}{\partial v}\right)_T

Asignemos a esta seudomatriz la propiedad de que cuando se cambia el orden de los elementos de una diagonal el signo de la correspondiente relación funcional debe cambiarse, como indicamos a continuación para el cambio de los elementos de la diagonal principal

.. math::

   \begin{vmatrix}
     v & s\\
     T & p
   \end{vmatrix}
   \rightarrow
   \left( \frac{\partial v}{\partial T}\right)_p = -\left( \frac{\partial s}{\partial p}\right)_T


Cambiando la diagonal secundaria y también el signo:

.. math::

   \begin{vmatrix}
     v & T\\
     s & p
   \end{vmatrix}
   \rightarrow
   \left( \frac{\partial v}{\partial s}\right)_p = \left( \frac{\partial T}{\partial p}\right)_s


Volviendo a cambiar la diagonal principal y el signo:

.. math::

   \begin{vmatrix}
     p & T\\
     s & v
   \end{vmatrix}
   \rightarrow
   \left( \frac{\partial p}{\partial s}\right)_v = - \left( \frac{\partial T}{\partial v}\right)_s


Para este mismo fin se utiliza el cuadro de Max Born:


.. figure:: ./img/max_born.png

La utilidad de estas relaciones se verá a lo largo de nuestro estudio, sin embargo, como una primera aplicación inmediata, consideremos el caso siguiente: supongamos que en el estudio de una determinada sustancia es preciso conocer como varia la entropía de la misma al variar el volumen a temperatura constante.

Como dijimos al principio, la entropía no es directamente mensurable, por lo que no tenemos procedimiento que nos permita determinar esta relación experimentalmente, sin embargo, según (6.34), se tiene directamente relacionada la variación de la entropía con el volumen a temperatura constante, con la correspondiente variación de la presión con la temperatura a volumen constante:

.. math::

   \left( \frac{\partial s}{\partial v}\right)_T = \left( \frac{\partial p}{\partial T}\right)_v

por lo que se tiene la posibilidad de deducir la relación que nos piden a partir de medidas experimentales de p y T. También podríamos determinar la relación mencionada si disponemos de una ecuación f (p, v, T) = 0.
