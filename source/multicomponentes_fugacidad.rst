Fugacidad y coeficiente de fugacidad
====================================

Hemos visto que la energía libre de Gibbs, y por tanto el potencial químico p desempeñan un papel muy importante en el estudio de los sistemas multicomponentes. Otra magnitud, relacionada con la anterior, y que también conviene tenerla en cuenta en este estudio es la denominada fugacidad.

La definiremos a partir de la consideración de sistemas monocomponentes y posteriormente ampliaremos esta definición a sistemas multicomponentes.

Sistemas monocomponentes
------------------------

Vamos a comenzar por el caso más sencillo de un sistema que consta de un solo componente. En este caso, la ecuación (9.18.c) se reduce a:

.. math::

   G = \mu n

o lo que es lo mismo:

.. math::

   \mu = \frac{G}{n} = g = h- Ts
   

Esto es, para un componente puro el potencial químico es igual a la función de Gibbs por mol. Con esto, la ecuación

.. math::

   \left. \frac{\partial G}{\partial p} \right|_T = V

escrita en base molar queda en la forma:

.. math::

   \left. \frac{\partial \mu}{\partial p} \right|_T = v

Para el caso particular de un gas ideal, :math:`pv = R_u T d(\ln p)` y la ecuacción (9.29) toma la forma:

.. math::

   d\mu_T^* = R_u T d(\ln p)
   
donde con (*) se indica gas ideal. Integrando a temperatura constante la ùltima ecuación se obtiene:

.. math::

   \mu^* = R_u T \ln p + C(T)

donde C(T) es una función de integración. Como la presión puede tomar valores comprendidos entre cero e infinito, el término ln p de esta expresión y, por lo tanto el potencial químico, tiene f un intervalo de valores entre :math:`-\inf` y :math:`\inf`. La ecuación (9.31) muestra también que el potencial químico puede determinarse a falta de un parámetro dependiente de la temperatura.

Para un gas real (en general para una sustancia compresible simple), y a fin de mantener el formalismo matemático utilizado para los gases ideales, definimos p mediante la expresión:

.. math::

   d\mu_T &= R_u T \frac{df}{f} \\
   &= R_u T d(\ln f)
   

en la que *f* es la fugacidad.

La integracióñ'dé esta ecuación proporciona:

.. math::

   \mu = R_u T \ln f + C(T)

Comparando las ecuaciones (9.33) y (9.31), se ve que la fugacidad juega, en el caso de gases reales, el mismo papel que la presión en el caso de un gas ideal. La fugacidad tiene la mismas imensiones que la presión.


Sustituyendo (9.32) en (9.29) se tiene:

.. math::

   R_u T \left. \frac{\partial \ln f}{\partial p} \right|_T = v
   
La integración de (9.34), manteniendo constante la temperatura, nos determina la fugacidad con sólo una constante indeterminada. Sin embargo, como el comportamiento de gas ideal se da cuando la presión tiende a cero, el término constante puede determinarse exigiendo que la fugacidad de un componente puro sea igual a la presión en el límite :math:`p\rightarrow 0`. Esto es:

.. math::

   \lim_{p\rightarrow 0}\frac{f}{p} = 1

Las ecuaciones (9.34) y (9.35) determinan, pues, completamente la función fugacidad.


Evaluación de la fugacidad para gases a partir de datos p, v, T
---------------------------------------------------------------

Consideraremos ahora cómo puede evaluarse la fugacidad partir de la correspondiente ecuación térmica de estado. Si a la ecuación (9.34) le restamos :math::`R_u T \left. \frac{\partial \ln p}{\partial p} \right|_T = \frac{R_u T}{p}` se obtiene:

.. math::

   R_u T \left. \frac{\partial \ln \frac{f}{p}}{\partial p} \right|_T = v-\frac{R_u T}{p}

Al cociente :math:`\frac{f}{p}` le conoce como coeficiente de fugacidad y se le denota con el símbolo :math:`\nu` (o :math:`\phi`), de modo que la ecuación anterior puede escribirse en la forma


.. math::

   R_u T \left. \frac{\partial \ln \nu}{\partial p} \right|_T = v-\frac{R_u T}{p}

Integrando desde :math:`p\rightarrow 0` hasta la presión considerada a *T* constante (para :math:`p\rightarrow 0 \hspace{1cm} \nu = 1`), se obtiene:

.. math::

   \ln \nu = \int_{p\rightarrow 0}^p \left( \frac{v}{R_u T} - \frac{1}{p}\right) dp
   
   

Esta ecuación nos permite obtener :math:`\nu` y por lo tanto *f* una vez conocida la relación :math:`p=p(v,T)`. Si lo que queremos es utilizar el modelo de estados correspondientes con: :math:`z = \frac{pv}{R_u T}`, multiplicando y dividiendo por *p* la ecuación anterior

.. math::

   \ln \nu = \int_0^p \left( \frac{pv}{R_u T} - 1\right) d(\ln p) = \int_0^p \left( z - 1\right) d(\ln p)


Si esta ecuación la expresamos en términos de la presión reducida, :math:`p_R= \frac{p}{p_c}` nos queda:

.. math::

   \ln \nu = \int_0^{p_R} (z-1) d(\ln p_R)

Dado que el factor de compresibilidad *z* depende de la temperatura reducida :math:`T_R` y de la presión reducida :math:`p_R`, se tiene que el segundo miembro de (9.36) va a depender sólo de esas propiedades. Así pues, :math:`\ln \nu` o :math:`\ln \frac{f}{p}` es sólo función de esas dos propiedades reducidas. Haciendo uso de la ecuación de estado generalizada que da *z* en función de :math:`T_R` y :math:`p_R`, :math:`\ln \frac{f}{p}` puede evaluarse fácilmente con un ordenador. Disponiendo del diagrama de :math:`\nu` generalizado puede utilizarse para el cálculo de esta magnitud empleando como variables de entrada :math:`p_R` y :math:`T_R`.

Ejemplo
^^^^^^^

Para ilustrar el uso de esa representación gráfica, consideremos dos estados del :math:`CCl_2F_2` a la misma temperatura de 420K. En el estado inicial la presión es de 2MPa y en el estado final de 4 MPa. El cambio en el potencial químico entre estos dos estados puede determinarse haciendo uso de la ecuación (9.33):

.. math::

   \mu_2-\mu_1 &= R_u T \ln \frac{f_2}{f_1} \\
   &= R_u T \ln \left[ \frac{f_2}{p_2} \cdot \frac{p_2}{p_1} \cdot \frac{p_1}{f_1} \right]

Haciendo uso de los valores críticos de la temperatura y presión del :math:`CCl_22F_2` (:math:`T_c=385K`, :math:`p_c=41.2bar`):

.. math::

   \begin{array}
   \text{estado 1} & p_{R1} = 0.5 &  T_{R1} = 1.09 & \frac{f}{p}=0.89 \\
   \text{estado 2} & p_{R2} = 0.99 & T_{R1} = 1.09 & \frac{f}{p} = 0.77
   \end{array}

Los valores de :math:`\frac{f}{p}` se han obtenido del gráfico generalizado de fugacidad. Así pues :math:`\mu_2-\mu_1 = 1915\frac{kJ}{kmol}`.

Para un componente puro el potencial químico es igual a la función de Gibbs por mol, :math:`\mu = g = h-Ts`. Como la temperatura es la misma en los estados 1 y 2, el cambio en el potencial químico puede expresarse como :math:`\mu_2-\mu_1 = h_2-h_1 - T(s_2 — s_1)`. Haciendo uso de los datos tabulares para el :math:`CCl_2F_2`, obtenemos el valor de :math:`1927.6 \frac{kJ}{kmol}` que es un valor muy próximo al calculado con el diagrama generalizado del coeficiente de fugacidad.

Evaluación de la fugacidad cuando el sistema se presenta como líquido o sólido
-----------------------------------------------------------------------------

Ya hemos visto un procedimiento para la evaluación de la fugacidad de un sistema cuyo estado de agregación es el de gas. La importancia de la fugacidad en el estudio de disoluciones es de tal naturaleza que se hace imprescindible disponer de métodos que nos permitan calcularla en el caso de que el sistema se presente como líquido o sólido.

Para ello recurramos a la ecuación (9.32!) y consideremos un pequeño cambio a temperatura constante.

Si aplicamos esta expresión para calcular el cambio de :math:`\mu` a *T* constante cuando el sistema pasa de la fase *I* (supongamos gas) a la fase *II* (líquido), coexistiendo ambas fases en equilibrio, integrando (9.32):

.. math::

   \mu_{II} - \mu_I = R_u T \ln \frac{f_{II}}{f_I} = 0 \hspace{2cm} f_{II} = f_I

Pero cuando se produce el paso de una fase a otra en equilibrio, ya vimos que se cumple que :math:`\mu_{II} = \mu_I`, por lo que

.. math::
 
   R_u T \ln \frac{f_{II}}{f_I} = 0 \hspace{2cm} f_{II} = f_I

Por lo tanto la fugacidad de un líquido en condiciones de saturación es igual a la fugacidad /del vapor en las mismas condiciones y ésta ya la sabemos calcular.

Consideremos ahora el caso de un líquido comprimido. Haciendo aplicación de la ecuación (9.34) se tendrá:

.. math::

   \left. \frac{\partial \ln f_f}{\partial p} \right|_T = \frac{v_f}{ R_u T}

Teniendo esto en cuenta imaginemos un sistema que evoluciona isotérmicamente desde una presión muy baja, :math:`p^*`, hasta la presión *p* pasando por un valor intermedio correspondiente a la presión de saturación a esa temperatura, :math:`p_{sat}`.

i Despejando de la expresión anterior :math:`d(\ln f)` e integrando entre :math:`p^*` y *p* (recuérdese que para :math:`p^* \rightarrow 0`, :math:`p^* = f^*` y para el valor *p* corresponde el valor :math:`f_f`) se obtendrá:

.. math::

   \ln \frac{f_f}{p^*} = \int_{p^*}^{p_{sat}} \frac{v_g}{R_u T } dp + \int_{p_{sat}}^p \frac{v_f}{R_u T} dp


Para evitar problemas de falta de continuidad en el límite cuando :math:`p^* \rightarrow 0`, restemos a  ambos miembros de la ecuación la expresión:

.. math::

   \ln \frac{p_{sat}}{p^*} = \int_{p^*}^{p_{sat}} \frac{1}{p} dp

con lo que se obtendrá la ecuación:

.. math::

   \ln \frac{f_f}{p_{sat}} = \int_{p^*}^{p_{sat}} \left( \frac{v_g}{R_u T} - \frac{1}{p} \right)dp + \int_{p^*}^{p_{sat}} \frac{v_f}{R_u T} dp

Esta ecuación puede aplicarse directamente.

En el caso de sólidos procedimiento a seguir es completamente análogo.

Ejemplo
^^^^^^^

Como aplicación vamos a determinar la fugacidad del agua líquida a 200°C y 50 bars.

De las tablas de propiedades termodinámicas del agua obtenemos, para 200°C y las presiones que se especifican, los siguientes valores:


.. math::

   p, bars	v, m3/kg	v/RT, bar 1	(v/RT - 1/
   0,06	36,383	16,648	-1,845-10-2
   0,70	3,108	1,422	-6,406-10-3
   1,5	1,444	0,660	-5,918T0-3
   5,0	0,4259	0,195	-5,116-10-3
   10	0,206	9,426-10-2	-5,738-10—3
   15,54	0,127	5,811-10—2	-6,237-10—3
   15,54	1,156-10—3	5,289-10"4
   25	1,155-10-3	5,285-10-4
   50	1,153-10—3	5,276-10—4

El valor de R para el agua es :math:`\frac{0.08314}{18} \frac{bar \cdot m^3}{kg \cdot K}

Tomando como valor de :math:`\left( \frac{v}{RT} — \frac{1}{p} \right)` la media, :math:`-5.833 \cdot 10^{.3}`, de la última expresión obtenemos para la primera integral el valor:

.. math::

   \int_0 ^{p_{sat}} \left( \frac{v_g}{R_u T} - \frac{1}{p}\right) dp = -5.833 \cdot 10^{-3} \cdot 15.54 = -9.14 \cdot 10^{-2}


Para la segunda integral

.. math::

   \int_{p_{sat}}^p \frac{v_f}{R_u T} dp = 5.283 \cdot 10^{-4} (50-15.54) = 0.0182


Por lo que obtendríamos para la fugacidad del agua en las condiciones dadas:

.. math::

   \ln \frac{f_f}{p_{sat}} = -0.073

esto es:

.. math::

   f_f = 15.54 \cdot e^{-0.073} = 14.44bar

Por otro lado, si consideramos como fugacidad del líquido la correspondiente al vapor saturado a la temperatura del líquido y utilizamos para su determinación el diagrama de fugacidad generalizado, obtenemos:

.. math::

   \left.
   \begin{array}
   p_R = \frac{15.54}{220.9} = 0.0703 \\
   T_R = \frac{473}{647.3} = 0.731 
   \eng{array}
   \right}
   \rightarrow 
   
   \nu = 0.96= \frac{f}{15.54} \rightarrow f = 14.92bar
  

Vemos que el valor de la fugacidad del líquido saturado difiere en menos de un 4% del valor obtenido para el líquido comprimido, por lo que es frecuente utilizar como valor de la fugacidad del líquido comprimido el correspondiente al vapor saturado a la temperatura del líquido comprimido.

Sistemas multicomponentes
-------------------------

La fugacidad del componente *i* en una mezcla puede definirse por un procedimiento en todo análogo al seguido para el de un componente puro. La fugacidad :math:`\overline{f_i}` para el componente *i* se introduce con:

.. math::

   \mu_i = R_u T \ln \overline{f_i} + C(T)

que es pareja a la (9.33). El par de ecuaciones que, en este caso de sistema multicomponente, nos permiten evaluar :math:`\overline{f_i}` son:

.. math::

   R_u T \left. \frac{\partial \ln \overline{f_i}}{\partial p} \right|_{T,n} = \overline{v_i} \\
   \lim_{p\rightarrow 0} \frac{\overline{f_i}}{x_I p } = 1



E1 símbolo :math:`\overline{f_i}` representa la fugacidad del componente *i* en la mezcla y debe distinguirse claramente en lo que sigue de :math:`f_i`el cual representa la fugacidad del componente puro *i* a la misma presión y temperatura.

Refiriéndonos a la ecuación (9.38.b), hay que destacar que en el límite de gas, ideal, la fugacidad :math:`\overline{f_i}}` no se exige que sea igual a la presión, como en el caso de un componente puro, sino que es igual a la cantidad *x*, *p*. Para ver que ésta es la cantidad límite apropiada, consideremos un sistema que consiste en una mezcla de gases que ocupa un volumen *V* a una presión *p* y temperatura *T*. Si toda la mezcla se comporta como un gas ideal, podemos escribir:

.. math::

   p = \frac{nRT}{V}

siendo *n* es el número total de moles de la mezcla. Ya que un gas ideal puede considerarse como compuesto de moléculas que ejercen, unas sobre otras, fuerzas despreciables y cuyo volumen (el de las moléculas) es despreciable frente al volumen total, podemos pensar que cada componente *i* se comporta como un gas ideal que estuviese él solo a la temperatura *T* ocupando todo el volumen *V*. Así, la presión ejercida por cada componente *i* no sería la de la mezcla *p*, sino la presión :math:`p_i` dada por:

.. math::

   p_i = \frac{n_iRT}{V}

siendo :math:`n_i` el número de moles del componente *i*. Dividiendo estas dos últimas expresiones se obtiene:

.. math::

   \frac{p_i}{p} = \frac{n_i}{n} = x_i

de donde despejando :math:`p_i`

.. math::

   p_i = x_i p

Sumando en ambos miembros de (9.39) sobre todos los componentes obtenemos:

.. math::

   \sum_{i=1}^k p_i = \sum_{i=1}^k x_i p = p \sum_{i=1}^k x:i

o, como la suma de las fracciones molares es igual a la unidad,

.. math::

   p = \sum_{i=1}^k p_i

Dicho en palabras, la ecuación (9.40) establece que la suma de las presiones :math:`p_i` es igual a la presión de la mezcla. De este hecho surge la denominación de presión parcial para :math:`p_i`. Con esto vemos que la ecuación (9.38.b) exige que la fugacidad del componente *i* se aproxíme a la presión parcial del componente *i* cuando la presión *p* tiende a cero.

Vamos a considerar a continuación, cómo puede expresarse la fugacidad de un componente *i* en una mezcla en función de cantidades evaluables. Para un componente puro *i*, la ecuación (9.34) da:

.. math::

   RT\left. \frac{\partial (\ln f_i)}{\partial p} \right|_T = v_i
   
donde :math:`v_i` es el volumen específico molar de la sustancia pura *i*. Restando (9.41) de (9.38.a),

.. math::

   RT\left. \frac{\partial \ln \left( \frac{\overline{f_i}}{f_i}\right)}{\partial p} \right|_{T,n} = \overline{v_i}-v_i
 
Integrando desde :math:`p^*` (que es una presión lo suficientemente baja como para considerar el comportamiento de gas ideal) a *p*, manteniendo constante la temperatura y la composición de
la mezcla

.. math::

   RT \left. \ln \left( \frac{\overline{f_i}}{f_i}\right) \right]_{p^*}^p   = \int_{p^*}^p (\overline{v_i}- v_i) dp
   


En el límite :math:`p^* \rightarrow 0`, se tendrá

.. math::

   RT \left[  \ln\left( \frac{\overline{f_i}}{f_i}\right) - \lim_{p^* \rightarrow 0} \ln \left( \frac{\overline{f_i}}{f_i} \right) \right] = \int_0^p (\overline{v_i} - v_i) dp 

Como cuando 

.. math::

   \lim_{p^* \rightarrow 0} \Rightarrow f_i\rightarrow p^* \text{   y  } \overline{f_i} \rightarrow x_i p^*
   
   
luego:

.. math::

   \lim_{p^* \rightarrow 0} \ln \left(  \frac{\overline{f_i}}{f_i}  \right)  \rightarrow \ln \left( \frac{x_i p^*}{p^*} \right) = \ln x_i



Así pues, podemos escribir:

.. math::

   RT \left[  \ln\left( \frac{\overline{f_i}}{f_i}\right) - \ln x_i  \right] = \int_0^p (\overline{v_i} - v_i) dp 

ó

.. math::

   RT \ln\left( \frac{\overline{f_i}}{x_i f_i}\right) = \int_0^p (\overline{v_i} - v_i) dp 

en donde :math:`\overline{f_i}` es la fugacidad del componente *i* en la mezcla, de composición, presión y temperatura dadas, y :math:`f_i` es la fugacidad del componente puro a la misma presión y temperatura. La ecuación (9.43) expresa la relación entre :math:`\overline{f_i}` y :math:`f_i` en función de la diferencia entre :math:`\overline{v_i}` y :math:`v_i` que es una cantidad mensurable.
