Relaciones Termodinámicas Generalizadas
=======================================

(Antonio Sánchez Sánchez)

Introducción
------------

Relacionadas con la función exergía vista en el tema cinco, aunque históricamente son anteriores, podemos definir dos nuevas funciones termodinámicas, las denominadas funciones de Helmholtz y Gibbs.

La primera se definirá a partir de la que algunos textos denominan disponibilidad para sistemas cerrados (:math:`U+p_oV-T_oS`) prescindiendo del término :math:`p_oV` y suponiendo que la temperatura del sistema es igual a :math:`T_o`:

.. math::

   A=U-TS \text{ o } a=u-Ts


y la segunda a partir de la exergía para sistemas abiertos:

.. math::

   G = H-TS \text{ o } g = h-Ts

Ambas funciones están relacionadas con sistemas complejos, en los que se dan reacciones químicas y en los que puede producirse más de una forma de trabajo. La frecuencia con la que se presentan en el anáfisis termodinámico de los sistemas, es lo que justifica que a estas agrupaciones de variables termodinámicas se les haya dado nombre propio.

Cuando estudiemos sistemas multicomponentes y multifase, con y sin reacción química, veremos la importancia de estas funciones.

Con frecuencia se nos presentará en el transcurso de nuestro estudio la necesidad de disponer de valores de las magnitudes u. h, s, a, g, etc. y estas no son determinables experimentalmente, por lo que es preciso disponer de relaciones entre estas magnitudes y otras que se puedan determinar de forma empírica, como son p, v, T, cp, Cv y las relaciones de estas últimas con T.

En este tema veremos cómo pueden determinarse estas relaciones y cómo se procede para calcular valores de las distintas magnitudes a partir de las que podemos medir en el laboratorio.

Antes de efectuar la determinación de estas relaciones veremos que existe un conjunto de magnitudes características que, expresadas en función de variables adecuadas, nos permiten un conocimiento termodinámico completo del sistema sometido a estudio: estas son los potenciales , termodinámicos o funciones características. Procuraremos destacar lo que hace que estas ecuaciones sean fundamentales en el estudio de la termodinámica.

Para el estudio de esta parte de la termodinámica se supone que el alumno domina la utilización de funciones de más de una variable y por tanto las relaciones entre derivadas parciales.


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

Conocidas u, s, v, p, y T podemos calcular sin dificultad h, a, g y otras magnitudes que puedan interesar, como son Cy y ks:

.. math::

   \left( \frac{\partial^2 u}{\partial v^2}\right)_s &= \left( \frac{\partial p}{\partial v}\right)_s &= \frac{1}{k_s v}\\
   \left( \frac{\partial^2 u}{\partial s^2}\right)_s &= \left( \frac{\partial T}{\partial s}\right)_v = \frac{T}{c}


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

   \fraac{p}{p_o} = \frac{AS^2 e^{ S/B}V^{-2}}{ ASV^{ -1} e^{S_o/B}V_o^{-2}} = \frac{1}{3}

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

Si disponemos de h, s, p, T y v, podemos determinar las restantes funciones termodinámi-
cas.

Supongamos que lo que nos dan es a en función de T y v:

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
   dg &= -vdp -s dT

de donde:

.. math::

   \left( \frac{\partial g}{\partial p}\right)_T = v\\
   \left( \frac{\partial g}{\partial T}\right)_p = -s

Conviene que completen el estudio de las funciones h, a, y g de la misma forma que se ha realizado el estudio de la función u.

Es fácil comprobar que tanto las magnitudes consideradas expresadas en función de otras variables termodinámicas, como cualquier otra magnitud termodinámica expresada en función de variables cualesquiera, no tienen la propiedad de ser funciones características.

***********

El nombre de potenciales termodinámicos que se asigna a las funciones que acabamos de considerar proviene del hecho de que su variación en ciertas condiciones, nos da el trabajo distinto del pdv que puede obtenerse en una determinada transformación.

En efecto, consideremos el caso de la energía interna. A partir del primer principio, supuesto que los cambios de energía mecánica son despreciables, obtenemos:

.. math::

   du = \partial q + \partial w	(6.17)

Del segundo principio, sabemos que para transformaciones reversibles :math:`\partial q = T ds`, por lo que:

.. math::

   du = T ds + \partial w

Téngase en cuenta que el término dw incluye tanto el trabajo :math:`-p dv` cómo cualquier otra forma de trabajo cuasiestático ( eléctrico, superficial, químico, etc.) al que representaremos por :math:`\partial w_x` sustituyendo:

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

De forma análoga podríamos justificar el nombre de entalpia libre, que ftm,cióndeGibbs.
también se da a la

Transformaciones de Legendre
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Como información adicional consideraremos la herramienta matemática que puede utilizarse para la deducción de los distintos potenciales termodinámicos.

Es importante tener en cuenta que los distintos potenciales termodinámicos pueden obte-erse a partir del primero, sin más que utilizar la denominada transformación de Legendre, que ertenece al grupo de las denominadas transformaciones de contacto, estudiadas en teoría de ecuaciones diferenciales.

La transformación de Legendre consiste en la sustitución de alguna o algunas de las variables por su correspondiente derivada conjugada. El resultado es que cualquiera de las funciones obtenidas (transformadas de Legendre) contienen la misma información que la ecuación de partida, pero dependen de variables diferentes. Ello representa una gran ventaja cuando se trata de funciones termodinámicas cuya forma puede cambiarse hasta que se puedan llegar a expresar en función de propiedades directamente mensurables.

Consideremos la forma de proceder al utilizar esta herramienta matemática. Para ellos supongamos que tenemos una expresión diferencial exacta del tipo:

.. math::

   dY = D_1 dX_1 + D_2 dX_2 + D_3 dX_3 + ...

Las correspondientes funciones transformadas de Legendre definen una serie de funciones relacionadas con Y, en las cuales el conjunto de variables utilizado para definir cada una de ellas contiene una o más de las :math:`D_i` (Recuerden que :math:`D_i=\left( \frac{\partial Y}{\partial X_i}\right)_{X_i}`) en lugar de las conjugadas :math:`X_i`. Para una expresión diferencial que tiene n variables existen :math:`2^n-1`  transformaciones posibles de Legendre. Si hay dos variables existirán tres transformadas de Legendre, es decir, si:


.. math::

   dY = D_1 dX_1+D_2dX_2

las transformadas serán:

.. math::

   \tau_1 = Y - D_1X_1 \\
   \tau_2 = Y - D_2X_2 \\
   \tau_{12} = Y - D_1X_1 -D_2X_2

y, por tanto,

.. math::

   d\tau_1 &= DY-D_1dX_1-X_1dD_1 &=D_2dX_2-X_1dD_1 \\
   d\tau_2 &= DY-D_2dX_2-X_2dD_2 &=D_1dX_1-X_2dD_2 \\
   d\tau_{12} &= DY-D_1dX_1-X_1dD_1-D_2dX_2-X_2dD_2 &= -X_1dD_1-X_2dD_2

Concretando para el caso de la energía interna:

.. math::

   dU = T dS - p dV \\
   U \fatarrow Y, T\fatarrow D_1, X_1 \fatarrow S, D_2 \fatarrow -p, X_2 \fatarrow V \\
   \tau_1 = U - TS\\
   \tau_2 = U-pV \\
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


INCLUIR LA FIGURA

La utilidad de estas relaciones se verá a lo largo de nuestro estudio, sin embargo, como una primera aplicación inmediata, consideremos el caso siguiente: supongamos que en el estudio de una determinada sustancia es preciso conocer como varia la entropía de la misma al variar el volumen a temperatura constante.

Como dijimos al principio, la entropía no es directamente mensurable, por lo que no tenemos procedimiento que nos permita determinar esta relación experimentalmente, sin embargo, según (6.34), se tiene directamente relacionada la variación de la entropía con el volumen a temperatura constante, con la correspondiente variación de la presión con la temperatura a volumen constante:

.. math::

   \left( \frac{\partial s}{\partial v}\right)_T = \left( \frac{\partial p}{\partial T}\right)_v

por lo que se tiene la posibilidad de deducir la relación que nos piden a partir de medidas experimentales de p y T. También podríamos determinar la relación mencionada si disponemos de una ecuación f (p, v, T) = 0.

Relaciones generalizadas para cambios de entropía, energía interna y entalpia, de sustancias compresibles simpless
-----------------------------------------------------------------------------------------------------------------

Para el análisis termodinàmico de sistemas es importante disponer de ecuaciones que permitan evaluar los cambios en estas magnitudes a partir de los correspondientes a los valores de las magnitudes que pueden medirse directamente. A continuación deduciremos alguna de estas ecuaciones.

Comencemos con los *cambios de entropía*. Por ser un sistema compresible simple, s podemos expresarla en función de T y v, T y p, ó p y v.

Consideremos el primer par de variables, T y v:

 .. math::

    ds = \left( \frac{\partial s}{\partial T}\right)_v dT +    \left( \frac{\partial s}{\partial v}\right)_T dv


Para conseguir el fin propuesto se deben sustituir las derivadas parciales dadas en función de expresiones que solo contengan p, v, T y los calores específicos. Para ello recordemos que:

.. math::

   Tds &= du +pdv\\
   ds &= \frac{1}{T}(du +pdv) \\
   du &=    \left( \frac{\partial u}{\partial T}\right)_v dT +    \left( \frac{\partial u}{\partial v}\right)_T dv = c_vdT +    \left( \frac{\partial u}{\partial v}\right)_T  dv\\
   ds &= \frac{c_v}{T}dT+    \left( \frac{\partial u}{\partial v}\right)_T dv = c_v dT +    \left( \frac{\partial u}{\partial v}\right)_T dv \\
   ds =  \frac{c_v}{T}dT+\frac{1}{T}\left[ p + \left(  \frac{\partial u}{\partial v}\right)_T \right]


Las ecuaciones (6.36) y (6.37) son expresiones equivalente para ds, por lo que:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_v = \frac{c_v}{T}

y

.. math::

   \left( \frac{\partial s}{\partial v} \right)_T  = \frac{1}{T} \left[ p + \left( \frac{\partial u}{\partial v}\right)_T \right]

De la tercera relación de Maxwell (6.34):

.. math::

   \left( \frac{\partial s}{\partial v}\right)_T  = \left(\frac{\partial p}{\partial T}\right)_v

Sustituyendo en (6.36) la primera de las (6.38) y la (6.34), se obtiene:


.. math::

   ds =  \frac{c_v}{T}dT+ \left(\frac{\partial p}{\partial T}\right)_v dv


Vemos que ds queda en función de magnitudes fáciles de determinar.

De (6.38) y (6.34) también se puede deducir:

.. math::

   \left(\frac{\partial p}{\partial T}\right)_v  = \frac{1}{T} \left[ p + \left(\frac{\partial u}{\partial v}\right)_T \right]

de la podemos obtener :math:`\left( \frac{\partial u}{\partial v} \right)` en función de cualquier ecuación *pvT*, relación que se necesitará utilizar más adelante.

De forma análoga para la expresión en función de *p* y *T* tenemos:

.. math::

   ds = \left( \frac{\partial s}{\partial T}\right)_p dT + \left( \frac{\partial s}{\partial p}\right)_T dp

A partir de:

.. math::

   dh &= Tds + vdp\\
   ds &= \frac{1}{T}(dh -vdp)

y

.. math::

   dh = \left( \frac{\partial h}{\partial T}\right)_p dT + \left( \frac{\partial h}{\partial p}\right)_T  dp = c_p dT + \left( \frac{\partial h}{\partial p}\right)_T  dp

se obtiene:

.. math::

   ds = \frac{c_p}{T}dT + \frac{1}{T} \left[ \left( \frac{\partial h}{\partial p}\right)_T -v\right]dp

Las expresiones (6.40) y (6.41) representan la misma función, por lo que identificando términos equivalentes, se llega a la relación:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_p = \frac{c_p}{T}

De la cuarta relación de Maxwell, ecuación (6.35), se tiene:

.. math::

   \left( \frac{\partial s}{\partial p}\right)_T  = - \left( \frac{\partial v}{\partial T}\right)_p

Algo semejante se puede hacer con la expresión de s en función de p y v. Es conveniente que el alumno realice la deducción completa de esta ecuación y compruebe que se llega a:

.. math::

   ds = \frac{c_v}{T} \left( \frac{\partial T}{\partial p}\right)_v dp + \frac{c_p}{T} \left( \frac{\partial T}{\partial v}\right)_p dv

La metodología utilizada en la deducción de las correspondientes expresiones para las funciones u y h es análoga a la utilizada hasta ahora.

Para obtener la correspondiente a los cambios de energía intema, recordemos que:

.. math::

   du = T ds - p dv

Sustituyendo ds por la expresión (6.39), se obtiene:


.. math::

   du = c_v dT + \left[ T \left( \frac{\partial p}{\partial T}\right)_v -p\right] dv

De la expresión :math:`dh = T ds + v dp`, sustituyendo en ella ds de la primera ecuación (6.43a), se obtiene:

.. math::

   dh = c_p dT + \left[ v-T \left( \frac{\partial v}{\partial T}\right)_p \right] dp

Tanto la expresión de du como la de dh permiten encontrar el valor de :math:`\Delta u` e :math:`\Delta h` para un determinado proceso, sin más que conocer las correspondientes relaciones :math:`c_p(T)`  y :math:`f(p,v,T) = 0`, mediante la integración entre los estados inicial y final correspondientes.

En algunos textos es frecuente dar estas expresiones utilizando :math:`\alpha` y :math:`k_T`, para ello, recuérdese que:

.. math::

   \left( \frac{\partial p}{\partial T}\right)_v = - \frac{  \left( \frac{\partial v}{\partial T}\right)_p  } {\left( \frac{\partial v}{\partial p}\right)_T } = \frac{\alpha v}{k_T v} = \frac{v}{v}

por lo que:

.. math::

   du = c_v dT + \left[ T\frac{\alpha}{k_T} - p\right]dv\\
   dh = c_p dT + [v-T\alpha v] dp = c_p dT + [1-\alpha T]v dp

Como aplicación inmediata de lo que acabamos de ver consideremos el ejercicio siguiente:

:doc:`Ejercicio E6.2 <rpg_E6.2>`

Relaciones generalizadas para :math:`c_p, c_v \text{ y } \gamma`
----------------------------------------------------------------

En el apartado anterior hemos encontrado dos relaciones de las que pueden deducirse definiciones generalizadas para :math:`c_p` y :math:`c_v`, utilizables en cualquier región monofase en la que sean conocidos datos (s, p, v, T):

.. math::

   c_v = T \left( \frac{\partial s}{\partial T}\right)_v\\
   c_p = T \left( \frac{\partial s}{\partial T}\right)_p

Teniendo en cuenta que:

.. math::

   \left( \frac{\partial s}{\partial T}\right)_v \left( \frac{\partial T}{\partial v}\right)_s \left( \frac{\partial v}{\partial s}\right)_T = -1\\
   \left( \frac{\partial s}{\partial T}\right)_p \left( \frac{\partial T}{\partial p}\right)_s \left( \frac{\partial p}{\partial s}\right)_T = -1

y las relaciones de Maxwell correspondientes, se obtiene:

.. math::

   c_v = -T \left( \frac{\partial v}{\partial T}\right)_s \left( \frac{\partial p}{\partial T}\right)_v\\
   c_p = T \left( \frac{\partial p}{\partial T}\right)_s \left( \frac{\partial v}{\partial T}\right)_p

Un método alternativo para la determinación de valores de cp y cv en un amplio intervalo de presiones y temperaturas está basado en el hecho experimental de que es fácil determinar ..calores específicos- í presiones bajas, ^ no lo es tanto a presiones-elevadas. Ya se mencionó la posibilidad de utilizar los métodos espectroscópicos para la determinación de calores específicos de gases a baja presión y la variación de este calor específico con la temperatura. Tales datos se denominan calores específicos a presión cero.

Para hacer que estos datos sean aplicables en cualquier intervalo, no sólo de temperatura, sino también de presión, es preciso que podamos determinar como varían estos calores específicos con la presión a temperatura constante.
Esta evaluación deberá basarse nuevamente en la utilización de datos p, v, T, determinados en el intervalo adecuado de estados de equilibrio.

Desde el punto de vista matemático lo que buscamos es una expresión para :math:`\left( \frac{\partial c_p}{\partial p} \right)_T` y en casos menos frecuentes :math:`\left( \frac{\partial c_v}{\partial v} \right)_T`. Ecuaciones generalizadas para estas dos expresiones se obtienen a partir de las ecuaciones s(T, p) (6.43a) y s (T,v) (6.39) deducidas antes.

Nos centraremos en la primera, ya que la segunda tiene un tratamiento análogo, que se recomienda realizar al alumno.

Teniendo en cuenta (6.43) y aplicando a la misma la condición de diferencial exacta, se obtiene:

.. math::

   \left( \frac{\partial \left( \frac{c_p}{T}\right)}{p} \right)_T = - \left( \frac{\partial ^2 v}{\partial T^2}\right)_p



de donde:

.. math::

   \left( \frac{\partial c_p}{\partial p} \right)_T = - \left( \frac{\partial ^2 v}{\partial T^2}\right)_p

Para obtener el valor de :math:`c_p` a una presión elevada tendremos que integrar la ecuación anterior a lo largo de una isoterma desde la presión cero al valor deseado. Por lo que:

.. math::

   c_p-{c_p}_o = -T \int_0^p \left( \frac{\partial^2 v}{\partial T^2}\right)_p dp

En esta expresión :math:`{c_p}_o` es el calor específico a presión cero o calor específico de gas ideal. La integración del segundo miembro requiere que dispongamos de información del comportamiento *pvT* de la sustancia en forma analítica o tabular.

Diferencias :math:`c_p` - :math:`c_v`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Otra relación termodinámica de gran interés es la que da la diferencia de los calores específicos a presión constante y a volumen constante. Una razón que justifica este interés es, que como ya hemos dicho, los valores de :math:`c_p` son mucho más fáciles de medir que los de :math:`c_v`. De hecho, los valores de :math:`c_v` sólo pueden evaluarse de forma rigurosa a partir de datos de :math:`c_p` y :math:`pvT`.

Para realizar esta evaluación recordemos que la variación de cualquier propiedad termodinámica (variable de estado) no depende del método de evaluación (camino recorrido), por lo que podremos igualar las dos ecuaciones obtenidas para ds, ecuaciones (6.39) y (6.43), obteniendo:

.. math::

   \frac{c_v}{T}dT+ \left(\frac{\partial p}{\partial T}\right)_v dv = \frac{c_p}{T}dT - \left(\frac{\partial v}{\partial T}\right)_p dp

y de ésta se puede obtener:

.. math::

   \frac{c_p-c_v}{T}dT = \left(\frac{\partial v}{\partial T}\right)_p dp +  \left(\frac{\partial p}{\partial T}\right)_v dv

de donde:

.. math::

   dT = \frac{T}{c_p-c_v} \left[ \left(\frac{\partial v}{\partial T}\right)_p dp + \left(\frac{\partial p}{\partial T}\right)_v dv \right]


Es decir, hemos obtenido una expresión de T considerada como función de p y v. Para esta función debe cumplirse:


.. math::

   dT = \left(\frac{\partial T}{\partial p}\right)_v dp + \left(\frac{\partial T}{\partial v}\right)_p  dv

Identificando coeficiente homólogos, se obtiene:

.. math::

   \left(\frac{\partial T}{\partial p}\right)_v = \frac{T}{c_p-c_v} \left(\frac{\partial v}{\partial T}\right)_p


por lo que:

.. math::

   c_p-c_v = T \left(\frac{\partial p}{\partial T}\right)_v \left(\frac{\partial v}{\partial T}\right)_p


Se hubiese llegado al mismo resultado utilizando la equivalencia de los otros coeficientes.

Si utilizando la relación cíclica sustituimos :math:`\left(\frac{\partial p}{\partial T}\right)_v`:

.. math::

   \left(\frac{\partial p}{\partial T}\right)_v = - \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial p}{\partial v}\right)_T

en (6.55), llegamos a la expresión:

.. math::

   c_p-c_v = -T \left(\frac{\partial p}{\partial v}\right)_T \left(\frac{\partial v}{\partial T}\right)_p^2


De esta ecuación se pueden deducir inmediatamente un conjunto de resultados importan-
tes.

Ante todo y sobre la base de datos experimentales, se sabe que :math:`\left(\frac{\partial p}{\partial v}\right)_T` es siempre negativa para todas las sustancias en todas las fases. Ya que la primera derivada parcial está elevada al cuadrado, se deduce que :math:`c_p-c_v` debe ser siempre positivo o cero.

Esta diferencia se hace cero en dos ocasiones. La primera de estas es, evidentemente, cuando T es el cero de la escala termodinámica, si los restantes términos permanecen finitos en este estado. Consecuentemente, los calores específicos a presión constante y a volumen constante
a 0K son idénticos.

El segundo caso en el que se anula la diferencia :math:`c_p-c_v` es cuando se anula la derivada parcial :math:`\left(\frac{\partial v}{\partial T}\right)_p`. Esto ocurre cuando el fluido tiene un valor extremo del volumen específico (máximo o mínimo). Si consideramos como sistema el agua líquida, este caso se presenta en el entorno de 4 °C, por ser a esta temperatura su densidad máxima. J1

sólidos y líquidos se suele

Es importante destacar que cuando se considera el estudio de hablar de calor específico y no se hace referencia a que el proceso considerado sea a presión o a volumen constante. Esto se debe a que los valores de :math:`\left(\frac{\partial v}{\partial T}\right)_p` son pequeños para la mayoría de los estados de equilibrio de las sustancias en estas fases. Generalmente los datos tabulados son valores de :math:`c_p`.

Es frecuente que encontremos expresada la diferencia de calores específicos para sólidos y líquidos en función del coeficiente de dilatación a y del coeficiente de compresibilidad isoterma :math:`k_T`, ya definidos. Sustituyendo en (6.56), se obtiene:

.. math::

   c_p - c_v = -T \frac{(\alpha v)^2}{-k_T v} = T \frac{\alpha^2 v}{k_T}

La utilización de :math:`\alpha` y :math:`k_T` resulta muy cómoda en la mayor parte de los cálculos que tienen que realizarse con estos sistemas, ya que sus valores pueden considerarse prácticamente constantes en casi todos los procesos considerados.

Expresión generalizada de :math:`\gamma`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para determinar :math:`\gamma` a partir de datos *pvT*, sustituyamos :math:`c_p` y :math:`c_v` por sus definiciones generalizadas:

.. math::

   \gamma = \frac{c_p}{c_v} = \frac{ T \left(\frac{\partial p}{\partial T}\right)_s \left(\frac{\partial v}{\partial T}\right)_p  }{ -T \left(\frac{\partial v}{\partial T}\right)_s \left(\frac{\partial p}{\partial T}\right)_v} = - \left(\frac{\partial p}{\partial v}\right)_s \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v


teniendo en cuenta que:

.. math::

   \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v \left(\frac{\partial p}{\partial v}\right)_T = -1\\
   \left(\frac{\partial v}{\partial T}\right)_p \left(\frac{\partial T}{\partial p}\right)_v = - \left(\frac{\partial v}{\partial p}\right)_T

Sustituyendo en (6.58) y recordando que :math:`k_T= -\left(\frac{1}{v}\right)\left(\frac{\partial v}{\partial p}\right)_T` y :math:`k_s = -\left(\frac{1}{v}\right)\left(\frac{\partial v}{\partial p}\right)_s`, se obtiene:

.. math::

   \gamma = -\left(\frac{\partial p}{\partial v}\right)_s \left( -\frac{\partial v}{\partial p}\right)_T = \frac{\kappa_T}{\kappa_s}

Es decir, podemos relacionar el cociente de calores específicos con el cociente de las compresibilidades de la sustancia a temperatura y entropía constante.

Coeficiente de Joule-Thomson o Joule-Kelvin
-------------------------------------------

Consideremos el flujo de un fluido a través de un conducto que tiene un obstáculo o limitación al paso del fluido. Esta limitación puede ser un estrechamiento o algún tipo de tapón poroso como lana de acero, lana de vidrio o algodón. El efecto de esta limitación es producir una caída notable de presión a través del obstáculo. Un esquema de la instalación se muestra en la figura 6.1. La interacción trabajo entre las superficies de control 1 y 2 es nula y el conducto a través del que se produce el flujo está aislado térmicamente.



Figura 6.1 Experiencia de Joule-Thomson

Figura 6.2: Resultados del experimento de Joule-Thomson

Consecuentemente, la interacción térmica es nula o despreciable. El flujo del fluido se
ajusta a las condiciones de estado estacionario. Además, los cambios en energía cinética y potencial de la corriente fluida entre 1 y 2, pueden también considerarse despreciables. Por lo que aplicando el primer principio para sistemas abiertos, se obtiene:

.. math::

   h_1 = h_2

Como ya mencionamos en la aplicación del primer principio a sistemas abiertos, los procesos en los que la entalpia de entrada es igual a la entalpia de salida, se denominan procesos de estrangulación. El efecto de estrangulación tiene un gran número dé aplicaciones tanto desde el punto de vista, técnico como teórico, a este tipo de experiencias también se les denomina efecto Joule-Thomson o Joule-Kelvin.

El efecto Joule-Kelvin tiene gran importancia, fundamentalmente, por dos hechos:

a)	Se pueden referir a él otras propiedades termodinámicas, que pueden evaluarse a partir de este efecto, como: volúmenes específicos, calores específicos y temperaturas.

b)	El resultado de la estrangulación, en ciertas condiciones, es una reducción en la temperatura del fluido, de forma que podemos tener un enfriamiento mediante un sistema sin partes móviles. De hecho, bajo condiciones adecuadas, es posible que uno o más componentes de una corriente fluida pase a la fase líquida durante el proceso de estrangulación, de forma que puede utilizarse el sistema para proceder a la separación de componentes de una mezcla gaseosa.

Como acabamos de decir, se ha visto experimentalmente que mediante el efecto Joule-Kelvin un fluido puede llegar a una temperatura final con un valor mayor o menor que el valor correspondiente de la temperatura inicial, dependiendo de los valores de :math:`p_1`, :math:`T_1` y :math:`p_2`. Una evaluación matemática adecuada de este efecto se realiza mediante el coeficiente de Joule-Kelvin :math:`\mu_{JT}`, que se define mediante la ecuación:

.. math::

   \mu_{JT} = \left( \frac{\partial T}{\partial p}\right)_h


De acuerdo con esta ecuación es fácil ver que :math:`\mu_{JT}` se puede determinar mediante las gráficas experimentales de procesos a entalpia constante, en un diagrama :math:`T_p`.

Para obtener estas gráfica experimentalmente, se fijan los valores de:math:`p_1T_1` corriente arriba de la estrangulación y se hace variar la presión :math:`p_2`. Para cada valor de :math:`p_2` se determina experimentalmente :math:`T_2`. Bajo condiciones de estrangulación, cada uno de los estados medidos corriente abajo tiene la misma entalpia que los estados corriente arriba del obstáculo. Después de hacer un número de medidas adecuado corriente abajo, para un estado dado en la parte anterior del obstáculo, se puede trazar una línea que corresponde a estados del sistema con la misma entalpia, sobre un diagrama :math:`T_p`. Es necesario hacer notar que lo único que decimos es que cada estado representado por puntos de la linea tienen la misma entalpia, lo cual no quiere decir que el proceso que tiene lugar cuando se produce el paso de un fluido por un estrechamiento sea isoentálpico.

Para obtener otra curva de entalpia constante, se altera o la presión o la temperatura inicial y se repite el procedimiento anterior para este nuevo valor de la entalpia.

De esta forma se traza una familia de líneas de entalpia constante sobre un diagrama :math:`T_p`. Un resultado típico se muestra en la figura 6.2. La pendiente de una línea de entalpia constante, para cualquier estado, es una medida del coeficiente de Joule-Kelvin correspondiente a ese estado, es decir, una medida de :math:`\mu_{JT}`.

En la figura 6.2, en donde se han representado las lineas de entalpia constante, vemos que algunas de ellas presentan un máximo. La linea que une estos máximos se denomina linea de inversión, y el valor de la temperatura para este estado se denomina temperatura de inversión. Una linea de presión constante cortará a la curva de inversión en dos puntos, de aquí que se hable de temperatura de inversión superior e inferior para una presión dada, en la zona de existencia de la curva de inversión.

La línea de inversión tiene un significado físico importante. A la derecha de la curva de inversión en un diagrama Tp el coeficiente de Joule-Kelvin es negativo. Es decir en esta región particular la temperatura se incrementará cuando la presión decrezca y a través del estrechamiento se produce un efecto de calentamiento. Por otro lado, a la izquierda de la curva de inversión el coeficiente es positivo, lo que significa que tendrá lugar un enfriamiento por expansión en esta región.

Vemos, por tanto, que en la estrangulación de un fluido, la temperatura final después del tapón poroso puede ser mayor que, igual a, o menor que la temperatura inicial, dependiendo, para un conjunto dado de condiciones iniciales, de la presión final. Por ejemplo, en la figura mencionada un estado típico inicial puede ser el punto w y la expansión hasta la curva de inversión (punto z) produce un calentamiento del fluido. Si se permite una expansión posterior hasta el punto y, se producirá un enfriamiento, pero no será suficiente para que el fluido recupere su temperatura inicial. Sin embargo, si la expansión progresa hasta el punto x, entonces será posible un enfriamiento suficiente para que la temperatura final sea inferior a la correspondiente al estado inicial.

Debe también destacarse que, para algunos estados iniciales, es imposible un proceso de enfriamiento. La parte superior de la curva de inversión corta a la línea de presión cero en un valor finito de temperatura, para todas las sustancias. Consecuentemente, las líneas de entalpia constante correspondientes a temperaturas muy altas nunca pasan a través de la línea de inversión, como puede verse en la mencionada figura y para estas líneas el coeficiente de Joule-Kelvin es siempre negativo para cualquier presión. Ejemplos de gases que tienen coeficientes negativos a temperaturas ordinarias y presiones bajas son el hidrógeno y el helio. De aquí que, si se quieren enfriar estos gases utilizando un dispositivo de estrangulación, previamente habrá que disminuir su temperatura considerablemente antes de poder conseguir mediante la estrangulación un enfriamiento adicional. No obstante, para la mayor parte de los gases, a temperaturas ordinarias, el coeficiente de Joule-Kelvin es negativo para presiones altas y positivo para presiones bajas.

En la figura 6.2 puede verse que, para una disminución de presiones determinada, el máximo efecto de enfriamiento se consigue si el estado inicial se encuentra sobre la línea de inversión. Si el estado inicial está a la derecha de la cura de inversión, parte de la expansión produce calentamiento, lo que está en contra del efecto deseado.

Es interesante que consideremos el coeficiente de Joule-Kelvin desde el punto de vista de una ecuación generalizada, es decir, su relación con las variables p, v, T y los calores específicos. Esto se obtiene fácilmente recordando la ecuación generalizada para la entalpia

.. math::

   dh = c_p dT + \left[ v - T \left( \frac{\partial v}{\partial T}\right)_p \right] dp

considerando una transformación entre dos estados con el mismo valor de la entalpia , :math:`dh = 0`, se obtiene:

.. math::

   \left( \frac{\partial T}{\partial p} \right)_h = \frac{1}{c_p} \left[ T \left( \frac{\partial v}{\partial T}\right)_p - v\right]


Por lo que el coeficiente de Joule-Kelvin, para un fluido determinado, puede calcularse a partir de la relación *pvT* del fluido y del calor específico a presión constante para el estado considerado. En la práctica, se utiliza el coeficiente de Joule-Kelvin, que puede medirse con facilidad, para evaluar calores específicos a presiones elevadas.

De la ecuación anterior se puede deducir una expresión para la temperatura de inversión, sin más que tener en cuenta que, en la curva de inversión, es igual a cero, de donde:

.. math::

   T_i \left( \frac{\partial T}{\partial p} \right)_p -v = 0

por lo que:


.. math::

   T_i = \frac{v}{\left( \frac{\partial T}{\partial p} \right)_p} = \frac{1}{\alpha_i}


A partir de esta relación, una vez conocida la ecuación *pvT* del gas, se podría determinar el valor de la temperatura de inversión del mismo.

.. toctree::
   :maxdepth: 1
   :caption: Contenido:
   
   rtg_ejercicios