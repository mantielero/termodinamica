Sólidos y líquidos
------------------

Vimos que en los gases ideales la energía potencial de interacción se consideraba nula y la energía total de sus moléculas era energía cinética. En el caso de gases reales el término de energía potencial es mayor, pero se mantiene muy por debajo del término de energía cinética. Cuando tratamos con líquidos y sólidos nos encontramos que la contribución de la energía potencial a la energía total del sistema va creciendo: en el caso de los Equidos es del mismo orden de magnitud la energía cinética y potencial y en el caso de los sólidos el término de energía cinética se hace casi despreciable.

La contribución creciente del término de energía potencial se manifiesta porque cada molécula no es libre en su movimiento, sino que esta restringida por sus vecinos más próximos con los que interactua fuertemente. Estas interacciones se manifiestan como un equilibrio entre fuerzas intensas de cohesión y repulsión, por lo que, tanto sólidos como líquidos, pueden soportar grandes variaciones de presión sin que varié prácticamente su volumen.

Debido fundamentalmente a la intensidad de las fuerzas intermoleculares, los sólidos y líquidos son poco sensibles a los cambios de temperatura y especialmente insensibles a los cambios de presión. Esto es cierto, en el caso de los líquidos, cuando consideramos temperaturas por debajo de la temperatura crítica.

Desde un punto de vista fenomenológico podemos dar a estas observaciones un carácter cuantitativo diciendo que para estas sustancias tanto a como :math:`\kappa_T` son tan pequeñas que, a efectos prácticos, podemos considerar que, para estos estados de agregación, la ecuación de estado puede expresarse por:

.. math::

   v = \text{constante ó } \\ \rho = \text{constante  (Independiente de T y p)}

Aun más, se ha visto experimentalmente que los valores medidos de :math:`T`, :math:`v`, :math:`\alpha`, :math:`\kappa_T` y :math:`c_p` son tales que la relación :math:`\frac{T\alpha^2v}{\kappa_T c_p}` es mucho menor que la unidad y a efectos prácticos puede suponerse que

.. math::

   \frac{T\alpha^2v}{\kappa_T c_p} = 0

En el intervalo de temperaturas y presiones en el que son válidas las relaciones (7.20) y (7.21), decimos que las sustancias se comportan como líquidos incompresibles ideales o sólidos incompresibles ideales.

Tanto para líquidos como para sólidos incompresibles ideales, teniendo en cuenta la ecuación
(7.21)	y la expresión para la diferencia de calores específicos a presión y volumen constante de sistemas compresibles simples, obtenemos

.. math::

   c_p - c_v =\frac{T\alpha^2v}{\kappa_T}

y

.. math::

   1 - \frac{c_v}{c_p} = \frac{T\alpha^2v}{\kappa_T c_p} = 0

de donde deducimos que

.. math::

   c_p = c_v = c

Procediendo de forma análoga con las expresiones para ds, du y dh se obtiene

.. math::

   ds = \frac{c}{T}dT + \left( \frac{\partial p}{\partial T}\right)_v dv = \frac{c}{T}dT + \frac{\alpha}{\kappa_T} dv = \frac{c}{T}dT\\
   du = cdT+ \left( \frac{T\alpha}{\kappa_T} - p\right)dv = cdT \\
   dh = Tds + vdp = cdT + vdp


Es decir, para los sólidos y líquidos ideales

.. math::

   u=u(T) \\
   s=s(T) \\
   h=h(T,p)


por lo que, para comportamiento incompresible ideal, podemos escribir

.. math::

   du = c(T)dT\\
   ds =\frac{c(T)}{T}dT\\
   dh = c(T) dT + vdp

y para comportamiento ideal y perfecto, es decir, cuando podamos suponer que el calor específico es una constante independiente de T

.. math::

   u -u_0 &= c(T - T_0)\\
   s - s_0 &= c\ln\left( \frac{T}{T_0}\right)\\
   h- h_0 &= c(T - T_0) + v(p - p_0)

en las que :math:`u_0`, :math:`s_0` y :math:`h_0` son los valores correspondientes al estado a (:math:`T_0,p_0`).

Coeficientes térmicos de los sólidos: dependencia del volumen con la presión y la temperatura
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En general se denominan ¡coeficientes termodinámicos a expresiones de la forma :math:`\left( \frac{\partial x}{\partial y}\right)_z`, en la que *x*, *y*, *z*, pueden ser cualesquiera de las magnitudes *T*, *p*, *v*, *s*. Los coeficientes termodinámicos que describen propiedades características del sistema, por ejemplo :math:`\left( \frac{\partial v}{\partial T}\right)_p` y :math:`\left( \frac{\partial v}{\partial p}\right)_T` están relacionados, respectivamente, con el coeficiente de dilatación :math:`\alpha` y el coeficiente de compresibilidad isotérmico :math:`\kappa_T`.

A estos coeficientes se les denomina térmicos, mientras que a los que incorporan en su definición :math:`c_v` o :math:`c_p` se les suele denominar energéticos o caloríficos.

En el estudio experimental dé sólidós^es un hecho conocido que su volumen es prácticamente independiente de la presión. Sólo a presiones muy altas (decenas de millares de megapascales) se hace notar el efecto de la presión sobre el volumen.

A temperatura constante, podemos expresar el cambio de volumen con la presión mediante la expresión

.. math::

   dv = \left( \frac{\partial v}{\partial p}\right)_T dp = -\kappa_T vdp

de donde

.. math::

   \frac{dv}{v} = -\kappa_T dp

Teniendo en cuenta que :math:`\kappa_T` es del orden de :math:`10^{-10}` a :math:`10^{-12} Pa^{-1}`, es evidente que la variación de volumen por unidad de volumen, con la presión es despreciable. Para un cambio finito de presión y suponiendo :math:`\kappa_T` constante en el intervalo de presión elegido

.. math::

   \ln \frac{v_2}{v_1} = - \kappa_T (p_2 - p_1)

y por tanto

.. math::

   v_2 = v_1 e^{-\kappa_T\Delta p}

Es decir que para los valores obtenidos para :math:`\kappa_T`, de la ecuación (7.25) se deduce que para :math:`\Delta p` no muy grande

.. math::

   v_2 = v_1

Esto se cumple especialmente bien para el diamante hasta presiones de :math:`10^4MPa`, a esta presión experimenta una reducción del 1.5%.

En cuanto a la dependencia del volumen con la temperatura, puede decirse que todos los sólidos se dilatan al calentarse, por lo que su coeficienle de dilatación cúbica :math:`\alpha = \frac{1}{v}\left( \frac{\partial v}{\partial T}\right)_p` es siempre positivo. El valor de :math:`\alpha` para temperaturas no muy próximas a puntos en los que se produce cambio de fase (ferromagnéticos, ferroeléctricos, superconductores, etc.,) es del orden de :math:`10^{-5}K^{-1}`.

Es importante destacar que para la mayor parte de los sólidos se da el coeficiente de dilatación lineal :math:`\alpha_L` que está relacionado con el coeficiente de dilatación cúbica a por la expresión

.. math::

   \alpha = 3 \alpha_L


o, si el coeficiente de dilatación depende de la dirección, viene dado por

.. math::

   \alpha = \alpha_x + \alpha_y + \alpha_z

Para demostrar la primera relación supongamos que podemos definir el volumen como una magnitud proporcional al cubo de una longitud característica L, es decir

.. math::

   v = kL^3

por lo que

.. math::

   \alpha = \frac{1}{v}\left( \frac{\partial v}{\partial T}\right)_p = \frac{1}{kL^3} \left( \frac{\partial v}{\partial L}\right)_p \left( \frac{\partial L}{\partial T}\right)_p = \frac{3kL^2}{kL^3}\left( \frac{\partial L}{\partial T}\right)_p = 3 \alpha_L


La segunda relación se obtiene a partir de considerar que :math:`v = xyz`. A partir de esto, tenemos

.. math::

   dv = xydz + xzdy + yzdx


de la que se deduce

.. math::

   \left( \frac{\partial v}{\partial T}\right)_p  = xy \left( \frac{\partial z}{\partial T}\right)_p  + xz \left( \frac{\partial y}{\partial T}\right)_p + yz \left( \frac{\partial z}{\partial T}\right)_p

con lo que podemos obtener la expresión de :math:`\alpha`

.. math::

   \alpha = \frac{1}{v}\left( \frac{\partial v}{\partial T}\right)_p = \frac{1}{z}\left( \frac{\partial z}{\partial T}\right)_p  + \frac{1}{y}\left( \frac{\partial y}{\partial T}\right)_p + \frac{1}{x}\left( \frac{\partial x}{\partial T}\right)_p

y reordenando

.. math::

   \alpha = \alpha_x + \alpha_y + \alpha_z

Teniendo en cuenta datos experimentales, la variación de :math:`\alpha` con la temperatura es muy pequeña, por lo que para intervalos de temperaturas no muy grandes, podemos suponer que :math:`\alpha` ves constante, por lo que

.. math::

   \alpha = \frac{1}{v}\left( \frac{\partial v}{\partial T}\right)_p  = \left( \frac{\partial \ln v}{\partial T}\right)_p

de donde

.. math::

   \ln \frac{v}{v_0} = \alpha (T-T_0)

o lo que es lo mismo

.. math::

   v = v_0 e^{\alpha(T-T_0)}

También en este caso *v* depende exponencialmente de *T*, como antes vimos respecto a *p*.

Coeficientes energéticos de los sólidos: Ley de Grüneisen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Experimentalmente se ha demostrado que hasta temperaturas de unos 150K los valores de :math:`c_p` y :math:`c_v` de los sólidos son prácticamente idénticos. A temperaturas más altas, mientras que :math:`c_p` sigue creciendo :math:`c_v` se acerca a un valor constante 3R, que se denomina valor de Dulong [#Dulong]_ y Petit [#Petit]_. Estos físicos en 1819 enunciaron una regla empírica, según la cual el producto del calor másico de un elemento químico en estado sólido por su masa atómica es aproximadamente el mismo para todos los elementos y es del orden de :math:`25\frac{kJ}{kmol \cdot K}`. En un principio se creyó que este valor se refería al calor molar a presión constante en vez de a volumen constante como después se ha confirmado.

.. rubric:: Investigadores

.. [#Dulong] Pierre Louis Dulong (1785-1838) y Alexis Thérése Petit (1791-1820). En 1819 formularon la ley que lleva su nombre. Son importantes sus trabajos sobre la dilatación de líquidos.

   Dulong investigó también sobre las leyes del enfriamiento y sobre la presión máxima de los vapores y en Química descubrió el cloruro de nitrógeno en cuya preparación sufrió varios accidentes.

.. [#Petit] Petit fue un talento precoz, puesto que a los 10 años pudo seguir estudios en la Escuela Politécnica, de la que fue nombrado profesor a los 23 años.

En el caso de sólidos moleculares puede aplicarse la regla de Kopp-Neumann (1864): el calor molecular de un compuesto químico sólido es igual a la suma de los calores atómicos de los elementos cuyos átomos entran en la composición de la sustancia considerada (si suponemos que hay n átomos distintos, :math:`c_v = 3nR` para el calor molar).

Tanto la regla de Dulong y Petit, como la de Kopp-Neumann sólo tienen carácter aproximado.

Los valores que se miden de capacidad calorífica son los correspondientes a :math:`c_p`. Para calcular :math:`c_v` a partir de estos, podemos recurrir a la relación

.. math::

   c_p - c_v = -T \left( \frac{\partial p}{\partial v}\right)_T\left( \frac{\partial v}{\partial T}\right)_p^2

En general se ve que la diferencia entre :math:`c_p` y :math:`c_v` para sólidos es muy pequeña, del orden del 3 al 5% del valor de :math:`c_v`.

Ley de Grüneisen
''''''''''''''''

Del estudio experimental de los metales, Grüneisen dedujo en 1908 que había una dependencia entre el calor específico y el coeficiente de dilatación cúbica que, para cualquier temperatura, podría representarse mediante la expresión

.. math::

   \frac{\alpha}{c_p} = \Gamma


en la que :math:`\Gamma` es una constante característica del metal.

Esta relación que, como hemos dicho, se enunció a partir de resultados experimentales, puede justificarse teóricamente mediante la física estadística, aunque no toma exactamente la misma forma.

Veamos, desde el punto de vista termodinámico, que información podemos obtener de esta relación.

Recordemos que

.. math::

   \frac{c_p}{T} = \left( \frac{\partial s}{\partial T}\right)_p = - \left( \frac{\partial p}{\partial T}\right)_s \left( \frac{\partial s}{\partial p}\right)_T = \left( \frac{\partial p}{\partial T}\right)_s \left( \frac{\partial v}{\partial T}\right)_p

y por tanto

.. math::

   \frac{c_p} = T \left( \frac{\partial p}{\partial T}\right)_s \left( \frac{\partial v}{\partial T}\right)_p = Tv \left( \frac{\partial p}{\partial T}\right)_s \frac{1}{v} \left( \frac{\partial v}{\partial T}\right)_p

A partir de lo cual vemos que :math:`c_p` y :math:`\alpha` están relacionados. Sustituyendo en la ecuación (7.26), obtenemos

.. math::

   \frac{\frac{1}{v} \left( \frac{\partial v}{\partial T}\right)_p}{c_p} = \frac{1}{Tv\left( \frac{\partial p}{\partial T}\right)_s} = \Gamma

de donde

.. math::

   \left( \frac{\partial T}{\partial p}\right)_s = \Gamma Tv

Por lo que, para los metales en los que se cumple que :math:`\Gamma` es constante, la variación de la temperatura con la presión, a entropía constante, es proporcional a la temperatura y al volumen.

.. note::

   Para completar la información de esta sección es importante que consulten el capitulo 6 de la Termodinámica de Kirillin y los capítulos 9 y 11 de Calor y Termodinámica de Zemansky.

Coeficientes térmicos y energéticos de los líquidos
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Como ya hemos dicho, los líquidos en puntos alejados de los cambios de fase, también podemos considerarlos sustancias incompresibles, no obstante los valores de :math:`\alpha` y :math:`\kappa_T`, sobre todo el primero, son mayores que para los sólidos.

Para los líquidos es importante considerar el valor de :math:`\left( \frac{\partial p}{\partial T}\right)_v`, es decir, el incremento de presión producido por un incremento dado de temperatura. Recordemos que

.. math::

   \left( \frac{\partial p}{\partial T}\right)_v = \frac{\alpha}{\kappa_T}

Si tenemos en cuenta que :math:`\alpha` es del orden de :math:`10^{-3}` a :math:`10^{-4}K^{-1}` y :math:`\kappa_T` es del orden de :math:`10^{-10}Pa^{-1}`, tendremos que

.. math::

   \left( \frac{\partial p}{\partial T}\right)_v \approx 10^6 \frac{Pa}{K}

y para el caso del agua a 50°C

.. math::

      \left( \frac{\partial p}{\partial T}\right)_v = 1.036 \cdot 10^6\frac{Pa}{K}

lo que quiere decir que si un recipiente de volumen constante, se llena completamente de agua y se calienta 10°C, el incremento de presión será

.. math::

   \Delta p = \int_{T_1}^{T_2} \left( \frac{\partial p}{\partial T}\right)_v dT \approx    \left( \frac{\partial p}{\partial T}\right)_v \Delta T = 1.036\cdot 10^7Pa \approx 10^2bar

****************

Pasemos a introducir un concepto que puede ser de gran utilidad en el estudio de líquidos. Dicho concepto es el de presión interna. Para definir este concepto procederemos de la forma mostrada a continuación.

En primer lugar, sabemos que para un sistema compresible simple el trabajo realizado contra las fuerzas exteriores puede expresarse por la relación

.. math::

   \partial w = pdv

teniendo en cuenta que esta es la expresión del trabajo realizado por el sistema, no sobre el sistema (:math:`—pdv`).

También hemos visto que para este tipo de sistemas la energía interna puede expresarse como una función de *T* y *v*, es decir, :math:`u = u(T, v)`, por lo que

.. math::

   du =  \left( \frac{\partial u}{\partial T}\right)_v dT +    \left( \frac{\partial u}{\partial v}\right)_T dv

Para un proceso a temperatura constante

.. math::

   du =    \left( \frac{\partial u}{\partial v}\right)_T dv

Vimos que el término :math:`\left( \frac{\partial u}{\partial v}\right)_T` es el que nos expresaba la variación de energía interna debido al cambio de posición relativa de las moléculas, es decir, es el término que tiene en cuenta la existencia del campo de fuerzas moleculares, por lo que, si la temperatura no cambia durante el proceso, podemos suponer que la variación de energía interna es debida al trabajo realizado por el sistema contra las fuerzas interiores, es decir, si consideramos :math:`p_{int}` la presión generada por estas fuerzas

.. math::

   p_{int} =    \left( \frac{\partial u}{\partial v}\right)_T

Recordemos que du también podíamos expresarla mediante

.. math::

   du = c_v dT + \left[ T    \left( \frac{\partial p}{\partial T}\right)_v  -p\right]dv

por lo que

.. math::

      \left( \frac{\partial u}{\partial v}\right)_T = T    \left( \frac{\partial p}{\partial T}\right)_v -p

En la expresión anterior p es la presión que el medio ambiente ejerce sobre la sustancia considerada, por lo que

.. math::

      T \left( \frac{\partial p}{\partial T}\right)_v  = p + p_{int}

Al término :math:`T  \left( \frac{\partial p}{\partial T}\right)_v` se le conoce a veces como presión total o térmica. Es importante tener en cuenta que la :math:`p_{int}` es muy pequeña para gases reales y nula para ideales, pero en los líquidos puede alcanzar valores muy altos, del orden de :math:`10^2MPa`.

Coeficiente de dilatación y calor específico
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Como ya hemos visto, los líquidos tienen un coeficiente de dilatación cúbica muy superior al de los sólidos, de aquí que al calentarse, su volumen varíe mucho más que el de estos. En algunos líquidos, como el aguq/, se da un comportamiento anómalo y en ciertos intervalos de temperaturas (para el agua entre 0 y 3.98°C a presión atmosférica) al incrementarse esta, disminuye el volumen y a partir del extremo superior del intervalo considerado el comportamiento es normal.

Respecto a las capacidades caloríficas de los líquidos, no se ha establecido una teoría consistente, como puede ser la de Debye [#Debye]_ para sólidos, por lo que hay que recurrir a la experimentación para su determinación o a relaciones termodinámicas que las den en función de otras propiedades.

.. note::

   Debe leerse la parte del capitulo 6 de la Termodinámica de Kirillin dedicada a líquidos.

.. rubric:: Notas

.. [#Debye] Peter J.W. Debye fue un físico de nacionalidad alemana, aunque nació en Holanda en 1884. Profesor de varias Universidades de Suiza, Holanda y Alemania, y en 1935 en la de Berlín, siendo a su vez Director del Instituto de Física. Posteriormente fue Profesor en la Universidad Cornell de Ithaca, en el Estado de New York. Premio Nobel de Química de 1936 por su contribución al conocimiento de la estructura de las moléculas.
