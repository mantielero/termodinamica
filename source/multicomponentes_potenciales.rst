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
dA = —SdT — pdV A y>dn¿
t=i
k
dH = TdS + Vdp + £>,■*»<
<=i
k
! dG = —SdT Vdp A ptdnt
(9.19.a)
(9.19.6)
(9.19.c)
;=i
Estas son las ecuaciones equivalentes para sistemas multicomponentes de da — —sdT — pdv, dh = Tds A vdp y dg — -sdT A vdp para sistemas monocomponentes.
Ya hemos visto anteriormente que de la diferencial de Í7(5, V, n¿) se deduce que:
dU		dU			dU
ds	V,n	V~ dV	í S,n	y	/i‘ “ dn¡
(9.20.a)
s,v, ny
Esto es, la temperatura, presión y potencial químico pueden obtenerse por diferenciación de U(S,V,rii). Las dos primeras relaciones de la ecuación (9.20.a) son las equivalentes de
T =
du
ds
du
-P=dï
de los sistemas monocomponentes. '
Un procedimiento análogo con las expresiones H(S,p, n¿), A(T, V, n¿) y G(T,p, tii) conduce a las expresiones:
T=™ dS	í p,n	r-%	î S,n	y	pí	_ dH drii
dA ~P~ dV	í T,n	ç dA dT	? V}n	y	Pi	dA dn
c dG dT	•> p,n	dp	i T,n	y	pí	_ dG dru
SiPini
T,V,ny
T,p,ny
(9.20.b)
(9.20.c)
(9.20.d)
El análisis anterior de los potenciales termodinámicos nos ha proporcionado algunas relaciones de propiedades para sistemas multicomponentes que se corresponden con relaciones obtenidas previamente para sistemas monocomponentes. Además, pueden obtenerse las correspondientes relaciones de Maxwell igualando las derivadas segundas cruzadas. Por ejemplo, de (9.19.c) obtenemos:
dV_
dT
p,n
ds_
dp
(9.21)
T,n
De manera análoga se pueden conseguir relaciones en las que se involucra el potencial químico. De (9.19.c) también se obtiene la importante relación:
Sistemas multicomponentes. Mezcla no reactiva de gases
9
U
o ‘
y teniendo en cuenta que la parte componente i, podemos escribir:
dp¡	¡dV — (
dp	T,n &TIi
p,T,n> jJ
derecha de esta ecuación es el volumen molar parcial del
dfu
dp
T,n
(9.22)
Análogamente se obtiene que:
dpi
dT
p,n
dS_
drii
= ~Si
P,T,n j
Al ser p,i una función de T y p, podemos escribir:
(9.23)
y comparando esta expresión con la ecuación de Gibbs-Duhem (9.17) se obtiene:
V 1

t=i
dpi
dT
= -S
p,n
v-^ dpi
> n» -5-
Él 9”
= V
T,n
teniendo en cuenta (9.22), (9.23), (9.22.a) y (9.23.a) se llega a las ecuaciones:
(23.a)
(22.a)
k	k
Y^n¡Vi = V y ^mSi^S	(9.24)
i'=i	¿=i
expresiones que ya obtuvimos anteriormente (ver ec.(9.9))
Como vimos en el tema anterior (8.10), según las variables utilizadas para expresar los potenciales termodinámicos, el potencial químico tomará la forma:
dU	_ dH	_ dA	_ dG
dni	S,V,rij d71'	s,p,n, " dni	T,Vn¡ drii
(9.25)
Sólo la última de estas derivadas parciales es una propiedad molar parcial, ya que el término
Ímolar parcial se aplica sólo a las derivadas parciales en las que las variables independientes son la temperatura, presión y número de moles de cada componente presente.
|De la última de estas relaciones, y de la definición de G ecuación (9.18c) se obtiene que*
*De manera análoga puede obtenerse que h¡ =	y que á¡ = ü¡ — Ts¡, siendo á¡ la función molar parcial
de Helmholtz
10
Sistemas multicomponentes. Mezcla no reactiva de gases
Mi
£sh-ts)
- dJL
~ dn± P,r,n,
= h{ — Tsí
- T
■ T,p,nj
as
drii
P,T,nj
De (9.25) y (9.23) se obtiene que
d(m/T)
dT	p,n
_Mi_ 1 dgj T2 + T dT
p, n
hi - Tsí 1 _
— — ji2	~ TS'
= 'k\
jr2 \
ecuación utilizada con frecuencia en termodinámica química.
