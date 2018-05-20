Potenciales termodinámicos para sistemas multicomponentes
=========================================================

Como ya se ha visto cualquier potencial termodinámico proporciona una descripción completa del estado termodinámico de un sistema. En principio, todas las propiedades de interés pueden determinarse a partir de ese potencial mediante un tratamiento matemático adecuado.

Ya se vio en el tema anterior que la energía interna de un sistema multicomponente puede ser considerada como potencial termodinámico si se expresa en función de la entropía y el volumen del sistema así como del número de moles de cada componente; esto es:

.. math::

   U = U(S,V,n_i)
   

Diferenciando esta función obtenemos:

.. math::

   dU = \left. \frac{\partial U}{\partial S} \right|_{V,n} dS + 
   \left. \frac{\partial U}{\partial V} \right|_{S,n} dV +
   \sum_{i=1}^k \left. \frac{\partial U}{\partial n_i} \right|_{S,V,n_j} dn_i
   
Esta diferencial nos expresa la variación de la energía interna del sistema cuando varía la entropía, el volumen y el número de moles de cada componente. El subíndice n en los dos primeros términos indica que todas las n permanecen fijas durante la diferenciación. Como esto implica composición fija, se sigue que:

.. math::

   T = \left. \frac{\partial U}{\partial S} \right|_{V,n} \\
   -p = \left. \frac{\partial U}{\partial V} \right|_{S,n}
   

E1 tercer término del segundo miembro de la ecuación (9.7),	:math:`\left. \frac{\partial U}{\partial n_i} \right|_{S,V,n_j} ` recibe el nombre de *potencial químico* y se lo denota con el símbolo :math:`\mu_i`. Este potencial químico es una propiedad intensiva al igual que la presión y la temperatura. Contabiliza la variación de la energía interna de un sistema multicomponente debida a la variación de la cantidad de sustancia de cada uno de los componentes si se deja variar la cantidad de materia del mismo componente considerado y se mantienen constantes las propiedades termodinámicas que definen el sistema, es decir, la entropía, el volumen y el número de moles de los restantes componentes.

Así, pues, la ecuación (9.12) podemos escribirla en la forma:


.. math::

   dU = T dS + -p dV + \sum_{i=1}^k \mu_i dn_i

La función *U* es una homogénea de grado uno en S, V y :math:`n_i` ya que:

.. math::

   U(\alpha S, \alpha V, \alpha n_i) = \alpha U(S,V,n_i)

y basándonos en el teorema de Euler de funciones homogéneas obtenemos:

.. math::

   dU = \left. \frac{\partial U}{\partial S} \right|_{V,n} S + 
   \left. \frac{\partial U}{\partial V} \right|_{S,n} V +
   \sum_{i=1}^k \left. \frac{\partial U}{\partial n_i} \right|_{S,V,n_j} n_i
   

y teniendo en cuenta las relaciones (9.13) podemos poner:

.. math::

   U = TS-pV+ \sum_{i=1}^k \mu_i n_i

A esta última ecuación se la conoce como ecuación de Euler de la energía. Si diferenciamos (9.16) obtenemos:

.. math::

   dU = TdS -pdV + \sum_{i=1}^k \mu_i dn_i + \left[ SdT - Vdp + \sum_{i=1}^k n_i d\mu_i \right]
   
y comparándola con (9.14) obtenemos la relación

.. math::

   \sum_{i=1}^k n_i d\mu_i = -SdT + Vdp
   
   
que se conoce como ecuación de Gibbs-Duhem. Esta ecuación nos da las restricciones existentes ntre las posibles variaciones de las variables intensivas T, p, y :math:`\mu_i`.

Las funciones de la forma :math:`A(T, V, n_i)`, :math:`H(S,p,n_i)` y :math:`G(T,p, n_i)` también sirven como potenciales termodinámicos para sistemas multicomponentes.

Estas funciones se obtienen aplicando la transformación de Legendre a U, de manera que las ecuaciones de Euler del potencial de Helmholtz, la entalpia y del potencial de Gibbs resultan:

.. math::

   A = U-TS \Rightarrow A = -pV + \sum_{i=1}^k \mu_i n_i \\
   H = U+pV \Rightarrow H = TS + \sum_{i=1}^k \mu_i n_i \\
   G = U-TS+pV \Rightarrow G =  \sum_{i=1}^k \mu_i n_i 
   

Si diferenciamos ahora estas funciones y tenemos en consideración la ecuación de Gibbs-Duhem (9.17), se obtendrá:

.. math::

   dA = -S dT -pdV + \sum_{i=1}^k \mu_i dn_i \\
   dH = T dS +Vdp + \sum_{i=1}^k \mu_i dn_i \\
   dG = -S dT +Vdp + \sum_{i=1}^k \mu_i dn_i 
   

Estas son las ecuaciones equivalentes para sistemas multicomponentes de :math:`da= —sdT — pdv`, :math:`dh = Tds + vdp` y :math:`dg = -sdT + vdp` para sistemas monocomponentes.

Ya hemos visto anteriormente que de la diferencial de :math:`U(S, V, n_i)` se deduce que:

.. math::

   T= \left. \frac{\partial U}{\partial S} \right|_{V,n} \\
   -p =  \left. \frac{\partial U}{\partial V} \right|_{S,n}  \\
    \mu_i = \left. \frac{\partial U}{\partial n_i} \right|_{S,V,n_j} 
   

Esto es, la temperatura, presión y potencial químico pueden obtenerse por diferenciación de :math:`U(S,V,n_i)`. Las dos primeras relaciones de la ecuación (9.20.a) son las equivalentes de :math:`T =  \left. \frac{\partial u}{\partial s} \right|_{v}`, :math:`-p =  \left. \frac{\partial u}{\partial v} \right|_{s}` de los sistemas monocomponentes.

Un procedimiento análogo con las expresiones :math:`H(S,p,n_i)`, :math:`A(T, V, n_i)` y :math:`G(T,p, n_i)` conduce a las expresiones:


.. math::

   T =  \left. \frac{\partial H}{\partial S} \right|_{p,n} \text{, } V=  \left. \frac{\partial H}{\partial p} \right|_{S,n} \text{, y} \mu_i =  \left. \frac{\partial H}{\partial n_i} \right|_{S,p,n_j}  \\
   -p =  \left. \frac{\partial A}{\partial V} \right|_{T,n} \text{, } -S =  \left. \frac{\partial A}{\partial T} \right|_{V,n} \text{, y }  \mu_i = \left. \frac{\partial A}{\partial n_i} \right|_{T,V,n_j}  \\
   -S =  \left. \frac{\partial G}{\partial T} \right|_{p,n} \text{, } V =  \left. \frac{\partial G}{\partial p} \right|_{T,n} \text{, y }  \mu_i = \left. \frac{\partial G}{\partial n_i} \right|_{T,p,n_j} 


El análisis anterior de los potenciales termodinámicos nos ha proporcionado algunas relaciones de propiedades para sistemas multicomponentes que se corresponden con relaciones obtenidas previamente para sistemas monocomponentes. Además, pueden obtenerse las correspondientes relaciones de Maxwell igualando las derivadas segundas cruzadas. Por ejemplo, de (9.19.c) obtenemos:

.. math::

   \left. \frac{\partial V}{\partial T} \right|_{p,n} = - \left. \frac{\partial S}{\partial p} \right|_{T,n}
   
De manera análoga se pueden conseguir relaciones en las que se involucra el potencial químico. De (9.19.c) también se obtiene la importante relación:

.. math::

   \left. \frac{\partial \mu_i}{\partial p} \right|_{T,n} = \left. \frac{\partial V}{\partial n_i} \right|_{p,T,n_j}


y teniendo en cuenta que la parte derecha de esta ecuación es el volumen molar parcial del componente *i*, podemos escribir:


.. math::

   \left. \frac{\partial \mu_i}{\partial p} \right|_{T,n} = \overline{v_i}

Análogamente se obtiene que:

.. math::

   \left. \frac{\partial \mu_i}{\partial T} \right|_{p,n} = - \left. \frac{\partial S}{\partial n_i} \right|_{p,T,n_j}  = - \overline{s_i}

Al ser :math:`\mu:i` una función de *T* y *p*, podemos escribir:

.. math::

   \sum_{i=1}^k n_i d\mu_i = \sum_{i=1}^k n_i \left. \frac{\partial \mu_i}{\partial T} \right|_{p,n} dT + \sum_{i=1}^k n_i \left. \frac{\partial \mu_i}{\partial p} \right|_{T,n} dp 


y comparando esta expresión con la ecuación de Gibbs-Duhem (9.17) se obtiene:

.. math::

   \sum_{i=1}^k n_i \left. \frac{\partial \mu_i}{\partial T} \right|_{p,n} = -S \\
   \sum_{i=1}^k n_i \left. \frac{\partial \mu_i}{\partial p} \right|_{T,n} = V


teniendo en cuenta (9.22), (9.23), (9.22.a) y (9.23.a) se llega a las ecuaciones:

.. math::

   \sum_{i=1}^k n_i \overline{v_i} = V \\
   \sum_{i=1}^k n_i \overline{s_i} = S
   

expresiones que ya obtuvimos anteriormente (ver ec.(9.9))

Como vimos en el tema anterior (8.10), según las variables utilizadas para expresar los potenciales termodinámicos, el potencial químico tomará la forma:

.. math::

   \mu_i = \left. \frac{\partial U}{\partial n_i} \right|_{S,V,n_i} = \left. \frac{\partial H}{\partial n_i} \right|_{S,p,n_j} = \left. \frac{\partial A}{\partial n_i} \right|_{T,V,n_j} = \left. \frac{\partial G}{\partial n_i} \right|_{T,p,n_j}
   
   
   
Sólo la última de estas derivadas parciales es una propiedad molar parcial, ya que el término molar parcial se aplica sólo a las derivadas parciales en las que las variables independientes son la temperatura, presión y número de moles de cada componente presente.

De la última de estas relaciones, y de la definición de *G* ecuación (9.18c) se obtiene que(*):

.. math::

   \mu_i = \left[ \frac{\partial}{\partial n_i}(H-TS)\right]_{T,p,n_j} = \left. \frac{\partial H}{\partial n_i} \right|_{p,T,n_j} - T \left. \frac{\partial S}{\partial n_i} \right|_{p,T,n_j} = \overline{h_i} - T \overline{s_i}

.. note::

   (*)De manera análoga puede obtenerse que h¡ =	y que á¡ = ü¡ — Ts¡, siendo á¡ la función molar parcial de Helmholtz

De (9.25) y (9.23) se obtiene que:


.. math::

   \left. \frac{\partial \frac{\mu_i}{T}}{\partial T} \right|_{p;n} = - \frac{\mu_i}{T^2}+ \frac{1}{T}\left. \frac{\partial \mu_i}{\partial T} \right|_{p,n} = - \frac{\overline{h_i}- T\overline{s_i}}{T^2} - \frac{1}{T}\overline{s_i} = - \frac{\overline{h_i}}{T^2}

ecuación utilizada con frecuencia en termodinámica química.
