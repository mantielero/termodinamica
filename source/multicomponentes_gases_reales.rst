Mezcla de gases reales
======================

Cuando los componentes de la mezcla no pueden ser tratados como gases ideales el problema de dar una ecuación térmica de estado para la mezcla o de calcular las variaciones de energía interna, entalpia o entropía que experimenta la mezcla en un proceso se complica sobremanera. Se pueden distinguir dos casos:

a.	El comportamiento de cada componente de la mezcla es el que corresponde a un gas real y su influencia sobre los otros componentes es apreciable, en cuyo caso tendremos una mezcla real de gases reales.
b.	Cada componente se comporta como gas real, pero su interacción con los restantes componentes es despreciable. Se tendrá en este caso una mezcla ideal de gases reales.

El estudio que se realiza a continuación se centrará es este segundo caso, ya que la aplicación de la adecuada ecuación de estado a cada componente, o bien el método de los estados correspondientes, permiten estimar con suficiente precisión tanto la ecuación térmica de estado como la variación de las distintas propiedades trmodinámicas.

Relaciones p, v, T para mezclas de gases reales
-----------------------------------------------

A la hora de dar una ecuación térmica de estado para una mezcla de gases reales utilizando el método de estados correspondientes (o cualquier ecuación térmica de estado), nos encontramos con dos alternativas. 0 generalizamos la ley de Dalton en lo que se conoce como ley de aditividad de la presiones o lo hacemos con la ley de Amagat, ley de la aditividad de los volúmenes.

La primera es simplemente decir que la presión de la mezcla es la suma de las presiones de cada uno de los componentes suponiendo que cada uno de ellos ocupa él solo todo el volumen a la temperatura de la mezcla. Esto es:

.. math::

   p = \sum_{i=1}^k \left. p_i \right|_{V,T}
   

A partir del modelo de estados correspondientes :math:`p_i = \frac{n_i Z_i RT}{V}`, luego

.. math::

   p = \frac{RT}{V} \sum_{i=1}^k n_i \left. Z_i \right|_{V,T} \\
   = \frac{nRT}{V} \sum_{i=1}^k x_i \left. Z_i \right|_{V,T} \\
   = \frac{nRT}{V} Z_m

donde se ha puesto que :math:`Z_m = \sum_{i=1}^k x_i \left. Z_i \right|_{V,T}`. El subídice (V,T) se ha puesto para destacar el que cada :math:`Z_i` se debe calcular para el volumen total y temperatura de la mezcla, esto es, :math:`Z_i=Z_i(v_{Ri}', T_{Ri})`. El problema de esta aproximación de la ley de aditividad de las presiones es que en muchos casos, en concreto en todos aquellos en los que no se conozca la densidad o el volumen molar de cada componente, es preciso un método iterativo ya que los :math:`Z_i` son función de :math:`v_{Ri}' = \frac{p_{ci} v_i}{R T_{ci}}`, :math:`T_{Ri} = \frac{T}{T_{ci}}` y se desconocen, en principio, los valores de :math:`v_{Ri}'`. También es necesario utilizar un método iterativo si el estado termodinàmico viene determinado por la temperatura y la presión.

La generalización de la ley de Dalton predice, a bajas presiones, valores del factor de compresibilidad de la mezcla mayores que los obtenidos experimentalmente, mientras que a altas presiones los predice algo menores. Este inconveniente se obvia utilizando lo que se conoce como regla de Bartlett de la aditividad de las presiones. Esta regla no es más que una modificación de la de Dalton generalizada, modificación consistente en utilizar, al evaluar los :math:`Z_i`, el volumen molar de la mezcla en lugar del volumen molar del componente; esto es, :math:`Z_i = Z_i(v_{Rm}', T_{Ri})` con :math:`v_{Rm,i}' = \frac{p_{ci} v_m}{R T_{ci}}`.


La generalización de la regla de Amagat conduce, como ya se ha indicado, a la ley de la adi-tividad de los volúmenes que puede utilizarse como método de aproximación al comportamiento de las mezclas de gases reales. Esta ley establece que:

.. math::

   V = \sum_{i=1}^k \left. V_i \right|_{p,T}

Si recordamos (9.47) vemos que esta aproximación es simplemente suponer que la mezcla es ideal. El hecho de que los componentes no se comporten como gases ideales nos lleva a dar, al igual que con la ley de la aditividad de las presiones, a cada componente el modelo de estados correspondientes obteniendo para el factor de compresibilidad de la mezcla:

.. math::

   \sum_{i=1}^k \left. x_i Z_i \right|_{p,T} = Z_m


En este caso los :math:`Z_i`, se calculan con :math:`p_{Ri} = \frac{p}{p_{ci}}`, :math:`T_{Ri} = \frac{T}{T_{ci}}`. Esta generalización de la regla de Amagat conduce a mejores resultados, cuando las presiones son altas, que la generalización de la regla de Dalton.

Existe otro método apropiado para determinar el factor de compresibilidad para una mezcla, que es el conocido como regla de Kay. Para calcular el factor de compresibilidad de la mezcla con la regla de Kay se define lo que se llama temperatura pseudocritica y presión pseudocrítica a partir de los valores de la temperatura y presión críticas de cada uno de los componentes de la mezcla. Estos valores pseudocríticos se definen de la forma:

.. math::

   T_c' = \sum_{i=1}^k x_i T_{ci} \\
   p_c' = \sum_{i=1}^k x_i p_{ci}

El factor de compresibilidad de la mezcla será, pues

.. math::
 
   Z_m = Z\left( \frac{T}{T_c'},\frac{p}{p_c'}  \right)


Una vez calculado el factor de compresibilidad, la ecuación térmica de estado para la mezcla es:

.. math::

   pV = Z_m nRT


Propiedades termodinámicas para mezclas de gases reales
-------------------------------------------------------

A la hora de calcular las variaciones de energía interna, entalpia y entropía de una mezcla ideal de gases reales hay que tener en cuenta el modelo elegido para determinar la ecuación térmica de estado de cada componente, ya que debe existir coherencia entre ese modelo térmico y el que se utilice para calcular las variaciones de esas propiedades termodinámicas.

Cualquier modelo de los estudiados anteriormente para determinar la ecuación térmica de estado involucra el modelo de estados correspondientes por lo que vamos a ver si podemos aplicar este modelo para calcular :math:`\Delta U`, :math:`\Delta H` e :math:`\Delta S` de la mezcla.

Para obtener la ecuación generalizada de la variación de entalpia para un gas se partía de la ecuación (6.9):

.. math::

   dh = Tds + vdp
   
Si esta ecuación la escribimos para la mezcla tendremos:

.. math::

   dh_m = T_m ds_m + v_m dp_m

Por tratarse de una mezcla ideal, se verifican las ecuaciones (9.65) y si durante el proceso no varía la composición de la mezcla podremos escribir la ecuación anterior en la forma:


.. math::

   d \left( \sum_{i=1}^k x_i h_i \right) = T_m d \left( \sum_{i=1}^k x_i s_i \right) + d \left( \sum_{i=1}^k x_i v_i \right) dp_m

o

.. math::

   \sum_{i=1}^k x_i (dh_i -T_m ds_i - v_i dp_m) = 0 

y por lo tanto:

.. math::

   dh_i = T_m ds_i + v_i dp_m

Vemos que este resultado, formalmente idéntico al dado en (6.9), es la ecuación que se utilizaría para desarrollar la correspondiente expresión generalizada para cada uno de los componentes de la mezcla por separado. Es importante destacar que en la ecuación aparece la variación de la presión de la mezcla y no la del componente. Así pues, podremos utilizar los diagramas generalizados para la corrección de la entalpia y entropía por efecto de compresibilidad utilizando la presión de la mezcla para calcular la presión reducida de cada componente de la mezcla. Esto es, podremos poner para la mezcla:

.. math::

   \Delta h = \sum_{i=1}^k x_i \Delta h_i \\
   \Delta s = \sum_{i=1}^k x_i \Delta s_i 


con

.. math::

   \Delta h_i &= \Delta h_i^* - \Delta h_{i2}^c \left( \frac{p_2}{p_{ci}}, \frac{T_2}{T_{ci}} \right) + \Delta h_{i1}^c \left( \frac{p_1}{p_{ci}}, \frac{T_1}{T_{ci}} \right) \\
   \Delta s_i &= \Delta s_i^* - \Delta s_{i2}^c \left( \frac{p_2}{p_{ci}}, \frac{T_2}{T_{ci}} \right) + \Delta s_{i1}^c \left( \frac{p_1}{p_{ci}}, \frac{T_1}{T_{ci}} \right) 

siendo (:math:`p_2`,:math:`T_2`) el estado final del proceso y (:math:`p_1`,:math:`T_1`) el estado inicial del mismo. Nótese que al ser un proceso en el que no varía la composición de la mezcla el término :math:`\Delta S_{\text{mezcla}}` de la expresión de la variación de entropía se anula.

Hay que resaltar el hecho de que en la forma en que se han deducido las expresiones (9.76) a (9.78) subyace la hipótesis de la ley de aditividad de los volúmenes, de modo que la ley de aditividad de las presiones no es válida para calcular las variaciones de energía interna, entalpia y entropía de una mezcla ideal de gases reales utilizando el modelo de estados correspondientes.

También puede utilizarse el modelo de Kay para calcular las variaciones de las propiedades termodinámicas de las que nos estamos ocupando. En este caso la mezcla se considera como un único gas real que tuviese como valores críticos de presión y temperatura los dados por (9.74), siendo en este caso las variaciones de entalpia y entropía:

.. math::

   \Delta H = n \left[ \right]

(9.80)
(9.81)
Si de una mezcla de gases reales conocemos la temperatura, tanto la inicial como la final del proceso, y el volumen final, para poder utilizar las expresiones (9.80) o (9.81), es preciso
k
primero estimar pm =	mediante la ley de la aditividad de las presiones y una vez obtenida,
¿ = 1
ya podemos utilizar esas expresiones.

