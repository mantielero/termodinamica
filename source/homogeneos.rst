Sistemas Homogéneos Monocomponentes
===================================

Antonio Sánchez Sánchez.


Introducción
------------


Una vez que hemos considerado los principios fundamentales de la termodinámica, las propiedades que definen el estado termodinámico de un sistema y la forma de manejar matemáticamente las relaciones que existen entre ellas, vamos a estudiar con cierto detalle la aplicación de lo visto hasta ahora al análisis de los distintos sistemas que nos podemos encontrar en el trabajo de cada día.

Los sistemas objeto de estudio, según su constitución, podemos clasificarlos en homogéneos y heterogéneos.

Decimos que un sistema es homogéneo. cuando su composición química y propiedades físicas son iguales en todas sus partes o varían de un modo continuo de un punto del sistema a otro. Como ejemplo característico podríamos considerar una columna de aire. En este sistema y debido a la gravedad, con la altura cambian de un modo continuo, tanto su composición química como sus propiedades físicas.

Cuando un sistema está constituido por dos o más partes homogéneas distintas se denomina heterogéneo: A cada una de las partes homogéneas que forman un sistema heterogéneo se le denomina fase. Las superficies que delimitan cada fase se denominan interfases y en ellas se da un cambio brusco en las propiedades (físicas, químicas o en ambas) que caracterizan cada fase. Hay casos en los que es conveniente considerar la interfase no como una superficie matemática, sino como una capa delgada en la que se transforma rápidamente el valor de las propiedades que definen cada fase (hielo-agua, agua-acetona, mercurio-acetona).

Tanto los sistemas homogéneos como los heterogéneos, pueden estar compuestos por una sola especie química (materia de composición química definida) o por más de una especie química. Entre los primeros podemos citar: agua líquida, disolución de agua y azúcar, aire (gas) y cualquier mezcla gaseosa. Entre los heterogéneos: agua(l) + hielo(s) [una sola especie química, sistema monocomponente]; aire(g)+aire(l) [sistema multicomponente y composición química distinta en la fase gas y líquido].

En ingeniería se trabaja con frecuencia con el término sustancia pura, entendiendo por tal la que tiene composición química uniforme en todos sus puntos. Un sistema que contenga agua y hielo es una sustancia pura, aunque sea heterogéneo, también es una especie química, ya que cualquier porción elemental del sistema responderá a la formula :math:`H_2O`. El aire, aunque sea una mezcla de gases, en tanto en cuanto mantenga su composición, puede considerarse una sustancia pura, pero no una especie química. El sistema formado por aire(g) + aire(l) no es una sustancia pura, por ser su composición distinta en la fase gas y líquido.

Hay quien utiliza como sinónimos especie química y sustancia pura, en tal caso el aire seria una mezcla de sustancias puras y el sistema :math:`H_2O+ClNa` ó :math:`H_2O+\text{azúcar}`, no saturados, serian disoluciones de sustancias puras.

Tanto las sustancias puras como las mezclas pueden encontrarse en tres estados de agregación: gas, líquido y sólido.

.. note::

   Se considera un cuarto estado de agregación en el que existen presentes iones y electrones libres, es el denominado plasma. Este estado se presenta en condiciones muy especiales y no vamos a estudiarlo.

En este tema nos dedicaremos al estudio de las propiedades termodinámicas de cada una de las fases y en el siguiente haremos el estudio de las condiciones de equilibrio de los sistemas homogéneos y de las transiciones de fase.

Gases
-----

La relación más sencilla entre las variables p, v, T de un sistema gaseoso, es la correspondiente al gas ideal, que ya hemos considerado. Esta relación es de manejo muy cómodo, pero no representa adecuadamente el comportamiento de los gases reales, por lo que para estudiar estos, hay que recurrir a las tablas de propiedades, a ecuaciones empíricas propias de cada gas o a las gráficas de factor de compresibilidad generalizado. Algo semejante ocurre cuando estudiamos el comportamiento de otros sistemas (Equidos, sólidos, etc.).

Comenzaremos con las relaciones empíricas.

Ecuación de estado del virial
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Entre las ecuaciones analíticas que se utilizan para expresar el comportamiento pvT de un gas tenemos la denominada ecuación del virial. La forma de esta ecuación surge del estudio de las curvas isotermas obtenidas en la experimentación con gases.

Supongamos que se mide la presión p y el volumen V de n moles de un gas, mantenidos a una temperatura determinada, para un amplio intervalo de valores de la presión, y representamos el producto pv, siendo :math:`v = \frac{V}{n}`, en función de *p*.

Experiencias de esta clase fueron realizadas por vez primera por Amagat [#Amagat]_ en Francia en 1870 (Antes, en el periodo 1857-69 T. Andrews [#Andrews]_ realizó estudios sobre diversas isotermas del CO2, viendo que al incrementar T disminuye la diferencia vg — v¡). Estas experiencias se han repetido en diversos laboratorios y en diversa épocas.

.. rubric:: Investigadores

.. [#Amagat] Emile Hilaire Amagat (1841-1915). Físico francés, autor de importantes investigaciones acerca de las propiedades de líquidos y gases.
.. [#Andrews] Thomas Andrews (1813-1885). Médico inglés. Fue profesor de Química en Belfast. Realizó las primeras investigaciones sobre compresibilidad de los gases reales a distintas temperaturas. Sus experimentos con el dióxido de carbono le llevaron a la noción de temperatura crítica al encontrar que por encima de 31,1°C era imposible licuarlo. Sus resultados fueron publicados en 1869 y confirmados en 1877 por el físico suizo Raúl Picter.

Fig. 7.1

En la Fig.7.1 se representan un conjunto de isotermas típicas de un gas como el nitrógeno.


Como se ve, estás curvas pueden representarse analíticamente mediante una expresión polinómica (o desarrollo del viriaL) en la forma:

.. math::

   pv = A \left( 1 + B'p +  C'p^2 + \cdots \right)

en la que A,B'. C', etc, son los denominados coeficientes del vinal, que dependen de la temperatura y de la naturaleza del gas. Es mucho más frecuente, sin embargo, utilizar el desarrollo del virial en función de potencias de :math:`\frac{1}{v}`, en la forma

.. math::

   pv = A \left( 1 + \frac{B}{v} +  \frac{C}{v^2} +  \frac{D}{v^3} + \cdots \right)

en la que A,B,C, etc., también se denominan coeficientes del virial. Dichos coeficientes como se ha citado anteriormente, únicamente dependen, para una sustancia dada, de la temperatura.

En el intervalo comprendido entre 0 y 40 bares, la relación entre :math:`pv` y :math:`\frac{1}{v}` es prácticamente lineal, de modo que sólo los dos primeros términos del desarrollo son significativos. En general cuanto mayor es el intervalo de presiones, mayor es el número de términos necesarios en el desarrollo del virial para describir adecuadamente el comportamiento del gas.

El desarrollo del virial no sólo es la descripción matemática de las curvas empíricas obtenidas en el estudio de los gases, sino que también puede deducirse teóricamente por los métodos de la mecánica estadística, en cuyo caso se puede asignar significado físico a cada uno de sus términos: :math:`\frac{B}{v}` nos expresa la interacción entre dos moléculas, :math:`\frac{C}{v^2}` tiene en cuenta las interacciones entre tres moléculas, etc. En principio los coeficientes del virial pueden calcularse utilizando expresiones de la mecánica estadística deducidas de consideraciones sobre los campos de fuerza entre las moléculas del gas.

El desarrollo del virial y el significado físico atribuido a los distintos términos de la serie pueden utilizarse para aclarar el comportamiento del gas en el límite cuando la presión tiende a cero a una determinada temperatura. Sabemos que conforme la presión se hace más pequeña a temperatura constante, el volumen tiende a crecer, por lo que los sucesivos términos de la ecuación anterior: :math:`\frac{B}{v}`, :math:`\frac{C}{v^2}`, etc., tienden a ser cada vez más pequeños y en el límite, cuando :math:`p\rightarrow 0`, se anularán, es decir, se anularán los campos de fuerza intermoleculares, por lo que

.. math::

   pv = A

pero cuando ocurre esto, el gas se comporta com/) ideal, por lo que

.. math::

   a= RT


y por tanto

.. math::

   pv = RT

cuando :math:`p\rightarrow 0`.

Ecuación de Van der Waals
^^^^^^^^^^^^^^^^^^^^^^^^^

El primer intento serio de encontrar una explicación teórica al comportamiento de los gases reales fue realizado con cierto éxito por van der Waals [#VanDerWaals]_ en 1873. Basándose en razonamientos elementales de la teoría cinética llegó a la conclusión de que habría que corregir la hipótesis de comportamiento puntual de las moléculas, utilizado en el modelo de gas ideal, ya que, cuando la presión aumenta, el volumen real de las moléculas puede ser una fracción importante del volumen total ocupado por el gas, de aquí que haya de considerarse un volumen efectivo, igual a :math:`(v — b)`, en donde *b* es un parámetro que depende del gas considerado y al que se denomina covolumen.

.. rubric:: Investigadores

.. [#VanDerWaals] Johannes Direrick Van der Waals (1837-1923). Físico holandés. Profesor de Física teórica desde 1877 en la Universidad de Amsterdam. En 1910 obtuvo el Premio Nobel de Física.

De forma análoga, si tenemos en cuenta que la atracción hacia el gas sobre las moléculas del mismo, que se encuentran en el límite del sistema, en contacto con la pared, ha de ser proporcional al número de moléculas por unidad de volumen y que el número de choques con la pared, también será proporcional a este número, tendremos que la presión efectiva (que ejercería el gas vendrá dada por :math:`\left(p +\frac{a}{v^2}\right)` en la que el valor de *a* depende del campo de fuerzas intermolecular y, en primera aproximación podemos considerarlo característico de cada gas.

Según lo anterior, van der Waals propuso que la ecuación de gases ideales debía ser modificada sustituyendo el volumen específico por el covolumen y la presión debería ser reemplazada por el término :math:`\left(p +\frac{a}{v^2}\right)`, quedando la ecuación de van der Waals:


.. math::

   \left(p +\frac{a}{v^2}\right)(v-b) = RT


Hemos de tener cuidado de expresar tanto *a* como *b* en unidades que seán compatibles con las utilizadas para *p*, *v* y *T*.


En esta ecuación es importante destacar:

a) En el límite, cuando :math:`p\rightarrow 0` y el volumen específico tiende a infinito, los términos de corrección son despreciables y la ecuación se convierte en la de los gases ideales

.. math::

   pv = RT

b) Cuando la presión crece, el término que más rápidamente contribuye a la desviación del comportamiento ideal es el :math:`\frac{a}{v^2}`.

La ecuación de van der Waals tiene un campo de aplicación restringido, ya que tanto *a* como *b*, no sólo dependen de la naturaleza del gas, sino que también dependen de la temperatura y en menor grado de la presión, por lo que habría que determinarlas experimentalmente para cada gas, en cada cierto intervalo de presión y temperaturas.

A pesar de lo dicho, esta ecuación tiene un merecido interés histórico porque permitió la deducción de los parámetros característicos que definen el comportamiento de cada gas (a, b), sin más que tener en cuenta el comportamiento genérico de las sustancias puras. Al principio del tema hemos citado las experiencias de Andrews con gases, fundamentalmente con :math:`CO_2`, siendo los resultados obtenidos una red de isotermas como la esquematizada en la fig. 7.2.

Fig 7.2

Aunque en el próximo tema consideraremos con más detenimiento este tipo de isotermas destaquemos que en las dos regiones señaladas, gas y líquido-gas, encontramos una isoterma que representa el límite de esta última zona, es decir, el punto en el que coincide el volumen específico del líquido y el gas. A este punto se le denomina punto crítico y a la isoterma se la denomina isoterma crítica. El punto crítico está caracterizado por las coordenadas termodinámicas presión crítica :math:`p_c`, temperatura crítica :math:`T_c`, y volumen crítico :math:v_c``

Como vemos la isoterma crítica presenta un punto de inflexión, por lo que en el se cumplirá


.. math::

   \left( \frac{\partial p}{\partial v}\right)_{T_c} = 0\\
   \left( \frac{\partial^2 p}{\partial v^2}\right)_{T_c} = 0

Estas ecuaciones nos permiten calcular las constantes de cualquier ecuación de estado con dos constantes. En el caso de la ecuación de van der Waals expresada como

.. math::

   p = \frac{RT}{v-b} - \frac{a}{v^2}


tenemos

.. math::

   \left( \frac{\partial p}{\partial v}\right)_{T_c} = - \frac{R T_c}{(v_c-b)^2} + \frac{a}{v_c^3} = 0 \\
   \left( \frac{\partial^2 p}{\partial v^2}\right)_{T_c} = \frac{2RT_c}{(v_c-b)^3}-\frac{6a}{v_c4} = 0

Pasando los términos en :math:`\frac{1}{v_c}` al segundo miembro y dividiendo una entre otra, obtenemos


.. math::

   \frac{2}{v_c-b} = \frac{3}{v_c}

de donde

.. math::

   v_c = 3b

y sustituyendo en la ecuación (7.6) se obtiene

.. math::

   T_c = \frac{8a}{27Rb}

y de la ecuación (7.4) aplicada en el punto crítico:

.. math::

   p_c = \frac{R\frac{8a}{27Rb}}{2b} - \frac{a}{9b^2} = \frac{a}{27b^2}

de donde

.. math::

   a = \frac{27}{64}\frac{R^2T_c^2}{p_c}\\
   b = \frac{RT_c}{8p_c}

y

.. math::

   z = \frac{p_cv_c}{RT_c}=\frac{3}{8} = 0,375

Estas ecuaciones nos permiten calcular *a* y *b* a partir de :math:`p_c` y :math:`T_c` que se determinan experimentalmente, pero, como ya hemos dicho, esto no es de un gran valor puesto que *a* y *b* varían con la temperatura si queremos que la ecuación de van der Waals nos explique el comportamiento de los gases reales.

La comprobación de lo que acabamos de decir la encontramos en el valor que toma la relación :math:`\frac{p_cv_c}{RT_c}`. De acuerdo con la ecuación de van der Waals el valor de esta relación es 0,375, como ya hemos visto, sin embargo los valores experimentales para la mayoría de los gases están comprendidos entre 0,2 y 0,3. Esto nos confirma que la ecuación que estamos considerando puede conducir a errores importantes, aunque mejora mucho los valores a los que conduce la ecuación de los gases ideales.

:doc:`Ejercicio E7.1 <homogeneos_E7.1>`

Otras ecuaciones de estado
^^^^^^^^^^^^^^^^^^^^^^^^^^

Los trabajos de van der Waals sugirieron otros muchos, encaminados a mejorar la precisión de los resultados que proporciona su ecuación de estado.

Una de las primeras consecuencias de estos trabajos fue la publicación por Dieterici en 1899 de la ecuación que lleva su nombre y que viene dada por la expresión:

.. math::

   p = \frac{RT}{v-b}\cdot e^{\left(-\frac{a}{vRT}\right)}

Esta ecuación proporciona una mayor aproximación a la relación :math:`\frac{p_cv_c}{RT_c}` de los gases reales. El valor obtenido con esta ecuación es 0,27 que podemos considerar un valor medio de los valores obtenidos experimentalmente.

Mucho más precisa que las ecuaciones anteriores es la propuesta en 1949 por Redlich y Kwong

.. math::

   p = \frac{RT}{v-b}-\frac{a}{T^{\frac{1}{2}v(v+b)}}

Aplicada esta ecuación en el punto critico nos conduce a los valores para *a* y *b* en función de :math:`T_c` y :math:`p_c`

.. math::

   a = 0,4275 \frac{R^2T_c^{2,5}}{p_c}

y

.. math::

   b = 0,08664 \frac{RT_c}{p_c}


Aunque es evidente, conviene no olvidar que *a* y *b* para cada ecuación de estado, con dos constantes, son distintas. Entre las ecuaciones con dos constantes, la que tiene mayor aceptación es la de Redlich y Kwong.

Se han formulado ecuaciones que se ajustan con bastante precisión al comportamiento de cierto tipo de gases, pero requieren el concurso de un gran número de constantes. Entre ellas se puede citar la ecuación de estado desarrollada por Benedict, Webb y Rubin. Esta ecuación tiene ocho constantes, además de la constante del gas, y es muy útil en predecir el comportamiento *pvT*, fundamentalmente de hidrocarburos ligeros. La ecuación de estado de Benedict, Webb y Rubin es

.. math::

   p = \frac{RT}{v}+ \left( BRT-A-\frac{C}{T^2}\right)\frac{1}{v^2}+\frac{bRT-a}{v^3}+\frac{a \alpha}{v^6}+\frac{c}{v^3T^2}\left( 1 + \frac{\gamma}{v^2}\right)e ^{-\frac{\gamma}{v^2}}

Otras ecuaciones se han desarrollado llegando incluso a intervenir hasta 50 constantes.


:doc:`Ejercicio E7.2 <homogeneos_E7.2>`

Factor de compresibilidad y estados correspondientes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Para gases reales ya hemos visto que a presiones altas y temperaturas bajas, la extrapolación a presión cero, es decir la ecuación pv = RT, no es una buena aproximación. Para expresar la desviación del comportamiento ideal se utiliza el factor de compresibilidad

.. math::

   Z= \frac{pv}{RT} = \frac{v}{\frac{RT}{p}} = \frac{v_{real}}{v_{ideal}}

En la fig 7.3 se muestra el factor de compresibilidad para varios gases que se utilizan con frecuencia. En ella podemos observar que

- El :math:`N_2` y el Ar hasta 100 bares se desvía un 3% o menos.
- El :math:`CO_ 2` a 300K y el vapor de agua a 600K se desvían rápidamente.
- El vapor de agua habría que mantenerlo a 1100K, para que su desviación del comportamiento ideal fuese menos del 2% hasta 100 bares.

Para muchas sustancias sólo se han medido unos pocos valores de datos *pvT* en intervalos limitados de presión y temperatura. Esto hace que la disponibilidad de este tipo de datos no cubra las necesidades que de ellos se tiene. Un método que A podría paliar esta deficiencia seria el poder dispones de una función :math:`Z = Z(p,T)`.

Dos magnitudes que se utilizan a continuación son la presión reducida :math:`p_R` y la temperatura reducida :math:`T_R`. Viniendo dada la presión reducida por la relación siguiente

.. math::

   p_R = \frac{p}{p_c}

y la temperatura reducida por

.. math::

   T_R = \frac{T}{T_c}

Es importante destacar que las presiones y temperaturas a que se hace referencia en las relaciones anteriores son presiones y temperaturas absolutas.

Volviendo al factor de compresibilidad, y afortunadamente, en ausencia de datos reales, dicho factor de compresibilidad de un gas puede predecirse por aplicación de lo que se conoce como el principio de los estados correspondientes! (atribuido a van der Waals). Este principio establece xue el factor Z para todos los gases puede considerarse el mismo cuando los gases tienen la misma presión y temperatura reducidas.

Si utilizamos la ecuación de van der Waals [ecuación (7.3)] y sustituimos las coordenadas termodinámicas p, v, y T, en función de las correspondientes magnitudes reducidas se obtiene

.. math::

   \left( p_R \frac{a}{27b^2} + \frac{a}{v_R^29b^2}\right)(v_R3b-b)= RT_R \frac{8a}{27Rb}

y agrupando términos

.. math::

   \left( p_R + \frac{3}{v_R^2} \right)(3v_R -1)= 8T_R

Según esto, para sustancias de este tipo, la relación entre :math:`p_R`, :math:`T_R` y :math:`v_R` es independiente del gas considerado, es decir para una determinada :math:`p_R`, :math:`T_R` y :math:`v_R` es el mismo para cualquier gas. Generalizando este resultado podríamos decir que dos gases que estuviesen a la misma :math:`p_R` y :math:`T_R` (estados correspondientes) tienen el mismo valor de *Z*, de acuerdo con lo enunciado en el principio de estados correspondientes.

Como ya hemos visto, esto sólo sería cierto si el comportamiento del gas viniera dado por la ecuación utilizada, como esto no es así, el método seguido consiste en promediar los resultados, para lo cual, recordemos que:

.. math::

   Z = \frac{pv}{RT} = \frac{p_cv_c}{RT_c}\frac{p_Rv_R}{T_R} = Z_c\frac{p_Rv_R}{T_R}

Esto ha llevado a realizar una representación de Z en función de :math:`p_R`, tomando :math:`T_R` como parámetro, para valores determinados de :math:`Z_c`. Las gráficas obtenidas se denominan gráficas de coeficiente de compresibilidad generalizadas. En las gráficas que se utilizan normalmente se toma para :math:`Z_c` el valor 0.27 (figuras 7.4, 7.5 y 7.6). También en el diagrama se representan líneas de :math:`v_R' = v \frac{vp_c}{RT_c}` (volumen seudoreducido), en vez de las correspondientes de :math:`v_R` que no se utilizan.

El gráfico de factor de compresibilidad generalizado tiene muy diversas aplicaciones a la hora de evaluar algunas de las magnitudes que se desean calcular, una vez que se conozcan :math:`p_c` y :math:`T_c` y alguna de las coordenadas del gas. A pesar de la gran precisión que pueden llegar a alcanzar estos cálculos, nunca pueden sustituir a los datos experimentales obtenidos para el gas que se quiera estudiar.



FIGURA Presión reducida, pn



FIGURA Presión reducida, /;/?



FIGURA Factor do compresibilidad,



Presión reducida

Fig. 7.6

:doc:`Ejercicio 7.3 <homogeneos_E7.3>`


Gráficas termodinámicas generalizadas
'''''''''''''''''''''''''''''''''''''

El principio de los estados correspondientes también es muy útil en la predicción de valores distintos a los *pvT*. Estos tres valores acabamos de correlacionarlos mediante el factor de compresibilidad y las propiedades reducidas :math:`p_R, T_R y v_R'`..

Es importante destacar que el factor de compresibilidad y las coordenadas reducidas pueden utilizarse para evaluar propiedades tales como la entalpia, la entropía y el calor específico a presión constante, para gases a presiones elevadas. La utilidad de este método radica en que únicamente se requiere la presión crítica y la temperatura crítica de cualquier sustancia, viniendo las correlaciones entre estas propiedades representadas de nuevo en forma de gráficas. El método de evaluación implica las ecuaciones generalizadas desarrolladas previamente.

Recuérdese que la entalpia de una sustancia homogénea simple, puede evaluarse a partir de la ecuación generalizada

.. math::

   dh = c_pdT + \left[ v-T \left( \frac{\partial v}{\partial T}\right)_p \right]

La variación de la entalpia de un gas con la temperatura se puede calcular con facilidad, ya que sólo se necesita conocer la variación de :math:`c_p` con la temperatura a la presión deseada. De aquí que el primer término del segundo miembro de la ecuación anterior no es demasiado difícil de evaluar en un gran número de casos. No pasa lo mismo con la variación de h con la presión, ya que se requiere del conocimiento del comportamiento *pvT* de cada sustancia considerada. Debido a que el conocimiento detallado de datos sobre muchas sustancias no es conocido, se hace preciso disponer de un método más general que sea aplicable, con la suficiente precisión, al cálculo de esta variación en cualquier sustancia.

De la ecuación anterior se deduce que a temperatura constante el cambio de entalpia está dado por

.. math::

   dh_T = \left[ v - T \left( \frac{\partial v}{\partial T}\right)_p \right]


Utilizando la relación de compresibilidad

.. math::

   pv = ZRT

encontraremos que

.. math::

   v = \frac{ZRT}{p}
   \left( \frac{\partial v}{\partial T}\right)_p = \frac{ZR}{p}+ \frac{RT}{p}\left( \frac{\partial Z}{\partial T}\right)_p dp

por lo que, sustituyendo en la ecuación (7.12), obtenemos

.. math::

   dh_T = \left[ \frac{ZRT}{p} - \frac{ZRT}{p} - \frac{RT^2}{p}\frac{RT}{p}\left( \frac{\partial Z}{\partial T}\right)_p\right] dp = - \frac{RT^2}{p}\left( \frac{\partial Z}{\partial T}\right)_p dp

Antes de integrar esta ecuación debemos transformarla a coordenadas reducidas, de forma que en una primera aproximación, resulte de validez general. Hemos visto que, por definición

.. math::

   T = T_c T_R

y


.. math::

   p = p_cp_R

por lo que

.. math::

   dT = T_cdT_R \\
   dp = p_C dp_R

Sustituyendo estas expresiones en la ecuación (7.13), obtenemos

.. math::

   dh_T = -\frac{RT_c^2T_R^2}{p_Cp_R} \left( \frac{\partial Z}{T_c \partial T_R}_{p_R}\right) d(\ln p_R)

e integrando a temperatura constante se obtiene la expresión

.. math::

   \frac{\Delta h_T}{T_c} = -R \int_i^f T_R^2  \left( \frac{\partial Z}{\partial T_R}_{p_R}\right) d(\ln p_R)

donde i y f indican los límites inicial y final de integración para :math:`p_R`. Debido a que es fácil determinar la variación de entalpia con la temperatura a presión constante, cuando la presión es baja, la integración anterior debe realizarse desde el estado de gas ideal (:math:`p\rightarrow 0`), al estado de gas real a la misma temperatura.

FIGURA

La entalpia de un gas ideal se representa normalmente utilizando como superindice un asterisco, es decir, :math:`h^*`, o también mediante el subíndice (pg), :math:`h_{pg}` (correspondería a la denominación gas perfecto, considerado como sinònimo de gas ideal, sin tener en cuenta la dependencia :math:`c_p` con T). El límite superior es la entalpia reai del gas, h, a una presión determinada. De aquí

.. math::

   \frac{h^*-h}{T_c} = R \int_0^{p_R} T_R^2 \left( \frac{\partial Z}{\partial T_R}_{p_R}\right) d(\ln p_R)

El valor de la integral se obtiene por integración gráfica, utilizando datos de la gráfica de compresibilidad generalizada. El resultado de la integración conduce a valores de :math:`\frac{h^*-h}{T_c}` como función de :math:`p_R` y :math:`T_R`, estos datos se representan en forma de gráficas denominadas gráficas de entalpia generalizada. En la figura 7.7 se reproduce una de estas gráficas.

La variación de entropía se puede calcular de forma semejante partiendo de la ecuación generalizada para ds de una sustancia simple, es decir

.. math::

   ds = \frac{c_p(T,p)}{T}dT - \left( \frac{\partial v}{\partial T}_p \right) dp


Procediendo como antes para un cambio a T constante

.. math::

   (s_p-s_0^*)_T = - \int_0^p \left( \frac{\partial v}{\partial T}_p \right) dp

Continuando con el proceso, realizaríamos la integración gráfica partiendo de datos de la gráfica de compresibilidad generalizada, :math:`p_R` y :math:`T_R`, pero no merece la pena continuar por este camino, ya que la entropía de gas ideal correspondiente a presión cero es infinita. Para evitar este inconveniente podemos aplicar la ecuación (7.16) al gas que estamos estudiando como si el modelo de gas ideal fuese aplicable en todo el intervalo de presiones (que no se comporte realmente como tal gas ideal no quiere decir que no podamos definir hipotéticamente este comportamiento). Suponiendo que se verifica esta hipótesis, tendríamos

.. math::

   (s_p^*-s_0^*)_T = - \int_0^p \left( \frac{\partial v}{\partial T}_p \right) dp = -R \int_0^p \frac{dp}{p}

El estado representado por :math:`s_p^*` es un estado hipotético, puesto que corresponde a comportamiento ideal a presión p, distinta de cero.

Si restamos de la ecuación (7.17) la ecuación (7.16), obtenemos

.. math::

   (s_p^*-s_p)_T = - \int_0^p \left[ \frac{R}{p}- \frac{\partial v}{\partial T}_p \right] dp

Recordemos que

.. math::

   v = \frac{ZRT}{p} \\
    \left( \frac{\partial v}{\partial T}_p \right) = \frac{ZR}{p}+\frac{RT}{p} \left( \frac{\partial Z}{\partial T}_p \right)

y sustituyendo en la ecuación (7.18) obtenemos

.. math::

   (s_p^*-s_p)_T = - R\int_0^p \left[ \frac{1-Z}{p}- \frac{T}{p}\frac{\partial Z}{\partial T}_p \right] dp

FIGURA

que expresada en función de las propiedades reducidas queda

.. math::

   (s_p^*-s_p)_T = - R\int_0^{p_R} \frac{1-Z}{p_R}dp_R+  R T_R \int_0^{p_R} \left( \frac{\partial Z}{\partial T_R}\right)_{p_R} \frac{dp_R}{p_R}




Teniendo en cuenta la ecuación (7.14), podemos expresar la ecuación anterior como

.. math::

   \frac{(s_p^*-s_p)_T}{R} = \frac{h^*-h}{RT_RT_c}-\int_0^{p_R} (1-Z) \frac{dp_R}{p_R}

De nuevo, utilizando coordenadas reducidas y valores del diagrama de compresibilidad generalizado podemos obtener valores para la desviación de la entropía del comportamiento ideal. Estos valores se representan de forma análoga a lo que se ha hecho con la entalpia, obteniendo las correspondientes gráficas generalizadas [figura (7.8)].

Es conveniente destacar que ambas gráficas generalizadas están basadas en el principio de estados correspondientes, por lo que representan exclusivamente una aproximación. Siempre que sea posible se deben utilizar los datos de la ecuación de estado para la sustancia objeto de análisis. Las gráficas generalizadas sólo proporcionan un medio para resolver los problemas que están fuera del intervalo de datos disponibles, lo cual se presenta con frecuencia en el análisis de ingeniería.

Aunque sólo hemos presentado dos gráficas generalizadas, debe tenerse en cuenta que puede disponerse de cualquier número de ellas, siempre que se disponga de la ecuación generalizada de la propiedad que interese, en función de *p* y *T*. Por ejemplo, se dispone de gráficas generalizadas que permiten la estimación de valores de :math:`c_p` a alta presión o también es corriente en ingeniería química la utilización de gráficas generalizadas de fugacidad (se suele representar :math:`\frac{f}{p}`, coeficiente de fugacidad, frente a :math:`p_R`, utilizando :math:`T_R` como parámetro).

En general, cuando no se disponen de datos *pvT* para una sustancia, las gráficas generalizadas son una herramienta muy adecuada para estimar el valor de las propiedades de un fluido, sea gas o líquido.

:doc:`Ejercicio 7.4 <homogeneos_E7.4>`

Sólidos y líquidos
------------------

Vimos que en los gases ideales la energía potencial de interacción se consideraba nula y la energía total de sus moléculas era energía cinética. En el caso de gases reales el término de energía potencial es mayor, pero se mantiene muy por debajo del término de energía cinética. Cuando tratamos con líquidos y sólidos nos encontramos que la contribución de la energía potencial a la energía total del sistema va creciendo: en el caso de los Equidos es del mismo orden de magnitud la energía cinética y potencial y en el caso de los sólidos el término de energía cinética se hace casi despreciable.

La contribución creciente del término de energía potencial se manifiesta porque cada molécula no es libre en su movimiento, sino que esta restringida por sus vecinos más próximos con los que interactua fuertemente. Estas interacciones se manifiestan como un equilibrio entre fuerzas intensas de cohesión y repulsión, por lo que, tanto sólidos como líquidos, pueden soportar grandes variaciones de presión sin que varié prácticamente su volumen.

Debido fundamentalmente a la intensidad de las fuerzas intermoleculares, los sólidos y líquidos son poco sensibles a los cambios de temperatura y especialmente insensibles a los cambios de presión. Esto es cierto, en el caso de los líquidos, cuando consideramos temperaturas por debajo de la temperatura crítica.

Desde un punto de vista fenomenológico podemos dar a estas observaciones un carácter cuantitativo diciendo que para estas sustancias tanto a como kj son tan pequeñas que, a efectos prácticos, podemos considerar que, para estos estados de agregación, la ecuación de estado puede expresarse por::

   v = constante ó p - constante (Independiente de T y p)	(7.20)

Aun más, se ha visto experimentalmente que los valores medidos de :math:`T, v, \alpha, \kappa_T y c_p` son tales que la relación :math:`\frac{T\alpha^2v}{\kappa_T C_p}` es mucho menor que la unidad y a efectos prácticos puede suponerse que

.. math::

   \frac{T\alpha^2v}{\kappa_T C_p} = 0

En el intervalo de temperaturas y presiones en el que son válidas las relaciones (7.20) y (7.21), decimos que las sustancias se comportan como líquidos incompresibles ideales o sólidos incompresibles ideales.

Tanto para líquidos como para sólidos incompresibles ideales, teniendo en cuenta la ecuación
(7.21)	y la expresión para la diferencia de calores específicos a presión y volumen constante de sistemas compresibles simples, obtenemos

.. math::

   c_p - c_v =\frac{T\alpha^2v}{\kappa_T}

y

.. math::

   1 - \frac{c_v}{c_p} = \frac{T\alpha^2v}{\kappa_T C_p} = 0

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

   u=u(T), s=s(T) y h=h(T,p)


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

Ejercicios
----------

1) Utilizando las ecuaciones de:

a)	Gas ideal.
b)	van der Waals.
c)	Redlich - Kwong.
d)	Factor de compresibilidad generalizado.

Determínese el volumen específico y compárese con el valor encontrado experimentalmente.

El valor determinado experimentalmente para el volumen específico del vapor de agua a 10 MPa y 360°C es 23,31-10-3 m3/kg, también se conocen, Tc — 647,3Á', pc = 220,9 bares, y las constantes de van der Waals: a = 5,507 bar(m3/kgmol)2 y b = 0,0304 m3 / kgmol.

Solución:

a)	29,24-10-3 m3/kg, 125
b)	24,46•10-3 m3/kg, 105
c)	23,72•10"3 m3/kg, 101
d)	23,68 • 10"3 m3/kg, 101,6

2) Se desea almacenar oxigeno a 10 MPa y -73 °C en un tanque de 3 m3. Determínese la masa de gas que podría contener el tanque, según se utilice la ecuación de:

  a)	Gas ideal.
  b)	Van der Waals.
  c)	Redlich - Kwong.
  d)	Factor de compresibilidad generalizado.

Para el oxigeno:

Tc = 154,4 A', pc = 50,5 bares.
Constantes de van der Waals:
a = 1,369 bar

Solución:

m
kg mol
b = 0,0315
m
kg mol
a) 577,34 kg. b) 888.89 kg. c) 826,7 kg. d) 826,77 kg.

3) Se comprime etano reversiblemente desde 5 a 98 bares a 30 °C, estacionariamente. Determínese:

  a)	Trabajo de compresión.
  b)	Calor transferido en el proceso. Para el etano: Tc = 305,4A' y pc = 48,8 bares.

Solución:

a) q = - 15 810,1 kJ / kg mol. b) w = 5 222,1 kJ/kg mol.
r
