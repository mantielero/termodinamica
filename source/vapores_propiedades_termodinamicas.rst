Propiedades termodinámicas del aire húmedo
==========================================

Al estudiar procesos que involucren al aire húmedo y tener que aplicar tanto el primer principio como el segundo bien a sistemas abiertos bien a sistemas cerrados, nos encontramos con que hay que evaluar variaciones tanto de energía interna como de entalpia y/o entropía. Por ello en esta sección vamos a ver cómo se pueden evaluar estas propiedades termodinámicas además de dar la expresión de la densidad del aire húmedo. En general, todas estas propiedades se dan por unidad de masa de aire seco que es el componente de la mezcla que se mantiene constante en, prácticamente, todos los procesos. Al final de la sección se dirá cómo se pasa de la unidad de aire seco a la unidad de mezcla.


Densidad del aire húmedo
------------------------


La densidad del aire húmedo depende de la temperatura *T*, de la presión *p* y de la humedad :math:`\omega`. De la definición de densidad tenemos que:

.. math::

   \rho = \frac{m_a+m_v}{V}
   

Si sustituimos en (10.9) el valor de *V* obtenido de las ecuaciones (10.2), :math:`V = \frac{(m_a R_a + m_v R_v)T}{p}`, se obtiene:

.. math::
 
   \rho = \frac{m_a + m_v}{m_a R_a + m_v R_v} \frac{p}{T}


y de la definición de humedad (ec. 10.3) podremos escribir:

.. math::
 
   \rho = \frac{1 + \omega}{1 + \tilde{\omega}} \frac{p}{R_a T}

Como :math:`(1 + \omega)` es siempre menor que :math:`(1 + \tilde{\omega})`, al aumentar la humedad del aire disminuye la densidad del mismo.

En vez de la densidad, a menudo se trabaja con su inversa el volumen específico del aire húmedo. Cuando se maneja esta propiedad suele usarse como magnitud de referencia la cantidad de aire seco :math:`m_a`. Por definición, el volumen específico con referencia a la cantidad de aire seco, es:

.. math::

   v_a = \frac{\text{volumen de aire húmedo}}{\text{masa de aire seco}} = \frac{V}{m_a} = (1+\tilde{\omega}) \frac{R_a T}{p}

El volumen específico así definido difiere de la definición corriente, en la que la magnitud
de referencia es la masa de la mezcla:

.. math::

   v_a = \frac{\text{volumen de aire húmedo}}{\text{masa de aire húmedo}} = \frac{V}{m_a+m_v}


Entre va y v existe la relación:

.. math::

  va_ = (l + ºomega)v
  

siendo  :math:`(1 + \omega)` la relación ------;------. Evidentemente entre p y va existe la relación:

masa de aire seco
(1 +w)
a —
V,
P
(10.14)
Mezclas de gases y vapores. Psicrometría
7

Entalpia, energía interna y entropía del aire húmedo
----------------------------------------------------

De manera análoga al volumen específico, cuando se utilizan valores específicos de estas propiedades termodinámicas se hace por unidad de aire seco y no por unidad de masa de mezcla.
El estado de referencia elegido para poder evaluar estas propiedades, mejor dicho sus variaciones, es un estado de equilibrio termomecánico, pero no de equilibrio químico. Es un estado en el que a temperatura 9rej = 0,01°C y pTej — 100 kPa el aire seco y el agua líquida están separados y para los cuales ha(0ref) = 0, h¡(9ref, pref) = 0, sa(9ref, pref) = 0y s,(9ref) = 0 (Hay que hacer notar que al dar estos valores se está suponiendo comportamiento perfecto para el gas y para el líquido).

De acuerdo con (9.65), la entalpia del aire h 'medo podemos expresarla como:

H ----	"f" Tlyhy

que, por unidad de sustancia de aire seco, toma la forma:

h — ha ujhv
(10.15.a)

en la que ha y hv son, respectivamente, las entalpias molares del aire seco y del vapor a la temperatura de la mezcla. Teniendo en cuenta que — = u'y que = 0,622, al pasar a
na

valores específicosj)or unidad de masa de airé seco he obtiene:

(10.15.b)

En (10.15.b) la entalpia del aire húmedo, h, viene expresada por unidad de aire seco.
Con el estado de referencia mencionado anteriormente y en la consideración de comportamiento de gas perfecto (aire y vapor de agua) y de líquido incompresible (agua líquida), la entalpia del aire húmedo ( ecuación (10.15)) que está a una temperatura T (K) y a una presión
p (kPa) se expresa en la forma:

✓¿fe
f~
T

9 + u ( &I1Ù—hit)
Pi


y+:M0,01°o) + Cp^)J )	(10.16)
---------—-----J___

En la expresión anterior el término -------------T— es despreciable (su valor es -0,099 kJ-
Pi
kg_1) frente a cualquiera de los otros dos términos (hiv(9rej) = 2501,4 kJ- kg 1 y cPv0 = 1,82 kJ- kg-1 si 9 — 1°C), por lo que para el aire húmedo no saturado y saturado puede ponerse :
jjh = Cp

— CVa ^	^ tylvi^ref ) 4“ C-
■4
(10.17)

Para el aire húmedo sobresaturado, distinguiremos dos casos según que 9 sea mayor o menor que 0,01 °C; esto es, según que el condensado sea líquido o sólido.
Para el primer caso (9 > 0,01°C):

8
Mezcléis de gases y vapores. Psicrometría
h = ha +usath¿ + (u>-u>sat)hp	(10.18)

donde /i¡ es la entalpia del líquido a la temperatura y presión (T, p) del aire húmedo saturado y hg es la entalpia del vapor saturado a la temperatura (T); esto es, la expresión que nos da el valor de esta entalpia, teniendo en cuenta el estado de referencia elegido, es:

hi = c,6 + P~Preí	(10.19)
Pi

y si despreciamos el término de la presión en la evaluación de la entalpia del líquido nos quedará:

h = cpJ + usat [h¡v(9ref) + cPv9] + (u - usat) c¡9	(10.20)
Y	para el segundo caso (9 < 0,01°C):
h — ha i^sat^g d" (u? UJsat')(10.21)

siendo h„ la entalpia del condensado sólido a la temperatura y presión (T, p) del aire húmedo saturado y que podemos evaluarla con:

= P‘(«„/)~Pr., +	+ cJ + P-p’ÍOre,)	(10.22)
'	Pl	Ps

Y	si, como hemos hecho hasta ahora, también en este caso despreciamos la contribución de la presión a la entalpia del sólido nos quedará finalmente:

^ — Cpa9 &sat [^/u(^re/)	1“ (^ ^saí) [^!s(^re/) d"
(10.23)

Los valores numéricos de los calores específicos, dado el intervalo de temperaturas utilizado en los problemas de aire húmedo, y los de las entalpias de cambio de fase son:

Cpa = 1,005 kJ • kg"1 • K-1 cPv = 1,82 kJ • kg“1 • K-1
-1 tz-l
c, = 4,18 kJ-kg'1 -K
cs = 2,05 kJ • kg 1 • K 1.
hiv(9ref) = 2501,4 kJ-kg 1 his(9Tej) - -333,4 kJ-kg 1

El término (lo - u3at) que aparece en las ecuaciones anteriores representa, respectivamente, la cantidad de condensado líquido y sólido existente en la mezcla.
Vamos a evaluar, ahora, la energía interna de una muestra de aire húmedo. Con el estado
de referencia elegido, ure¡ no es nulo, sino que vale uTe¡ — uarcf + u)!í„r . siendo uarc —
V f	1

~PrefVarcj = -RaTref y uVrcJ =--------ya que, por definición, hrej = uref + (pv)Tef = 0. Con
esto la expresión de la energía interna será:

Mezclas de gases y vapores. Psicrometría
9
u — ua +uuv = cVa6 -\-u[u¡v(9Tef) + cVv6] - ^RaTref	(10.24)

Una forma alternativa, y quizás más sencilla, de evaluar la energía interna del aire húmedo es partiendo de u = h — pv por la que:

'___________=-__-■	— , :.../ ' /	--------t
u = ua + Louv = ha - RaT + w (hv - RVT)
(10.25.a)

que puede reagruparse para escribir:

(10.25.b)

u = ha + uhv - Ra (1 + ü) T = cPa0 + u[hiv(0re/) 4-cPv0] - 7üa(l +ü)T Puede verse fácilmente que ambas expresiones, (10.24) y (10.25), coinciden.

Cuando el aire húmedo está sohresat aradoras expresiones de la energía interna del mismo
son:

^ — ha 4“ ^sathg	Ra (1 4" ^sat ) R 4” (^ ^sat)
hf(T) -
P*(T)
Pi
si 0>O,O1°C	(10.26)
n — Ha 4“ tdsathg Ra (1 4" &sat ) R 4" (^	^sa¿)
hs(R)
P*{T)
si 0<O,O1°C	(10.27)

La entalpia del líquido saturado h¡(T) se calcula de (10.19) sin más que poner las condiciones de saturación y de manera análoga, a partir de (10.22) se obtiene la entalpia para el condensado sólido (hielo) hs(T).

Para evaluar la entropía de una muestra de aire húmedo utilizaremos la expresión R — k
^^n¿s,(T,p¿). Así pues, para el aire húmedo, y por unidad de masa de aire seco, teniendo en ¿=i
cuenta el estado de referencia se tendrá:
con
y

(10.28)
(10.28.a)
sv
hlv(Tref)
4- Cp„ ln
- re/
■ref
Rv ln
Pv
P*(Rref)
(10.28.b)

Esta última expresión puede ponerse, sin más que sumar y restar .R„ln p*(R) y teniendo en cuenta (10.7), en la forma:

10
Mezclas de gases y vapores. Psicrometría
hlv(Tref)	,	, T „ , .	P*(T)
Su — —~	b c„v	ln m	— Rv ln	^/ÍT,	x -ñu ln <p
c re/
'■ref
P*(Tref)
= sa(T) - ñuln <(>

Así, pues, podremos escribir para la entropía del aire húmedo:

(10.28.C)
, T n , Pa s - cPa ln —-------ña ln---------b w
Tref	Pref
hlv(Tref) Tref
P*(T)
+ cPv ln —1-----------ñu ln	7 N - ñu ln 0
J- i
(10.29)
[re/	P*(Tref)

Si el aire húmedo está sobresaturado las expresiones de la entropía para ese aire serán: Si 6 > 0,01°C
s = sa +w3aiSp + (w - u3at)s¡	(10.30.a)
donde sa viene dado por (10.28.a), sg se obtiene de (10.28.c) haciendo <f) — 1 y s¡ es:

si = c, ln-— = sf(T)
1 ref
(10.30.b)
sí e < o,oi°c
s = sa + 0J,atsg + (¡Jj - u,at)s,	(10.31.a)

sa, en este caso, también viene dada por (10.28.a) y sg es la misma que en el caso anterior. La expresión de ss es:

ss =	+ cs ln	(10.31.b)
ref	r rej

Aire húmedo en equilibrio con agua líquida

Habrá ocasiones en las que el aire húmedo se encuentre en equilibrio con agua h'quida, y para esos casos conviene analizar la influencia que sobre la presión de saturación del agua tiene la presencia del aire seco.

Partimos del hecho de que el aire seco no está, prácticamente, disuelto en el agua líquida*; esto es, podemos considerar el agua líquida, en presencia de aire húmedo saturado, como una sustancia pura. Como hay equilibrio entre el agua en fase líquida y fase vapor se debe verificar que:

P-l(T, p) — flv(T, Pv.aat)

y como ya vimos en el tema anterior, para un sistema monocomponente p = h — Ts, luego tendremos para el agua líquida y para el agua vapor los valores:
*De la ley de Henry se obtiene que las fracciones molares de Oí y Ni disueltas en el agua liquida son %o2 — 4.76 • 10-6 y xjv2 = 9.14 • 10~6, lo cual supone que hay 8,5 gramos de Oí y 14,1 gramos de Ni disueltos en 1 m3 de agua. Estas cantidades son lo suficientemente pequeñas como para poder considerar el agua como una sustancia pura

Mezclas de gases y vapores. Psicrometría
11
m = h¡- Ts,
= hf(T) + P~P*(T>) -Ts}(T) Pt
Pv — *^v	TSV{T, Pv%sat)
= h9(T) - T
sg(T)-Rv ln^fi P .

En la que p* es la presión de saturación del agua como sustancia pura. Y como hg(T) — h¡(T) = T[sg{T) — sj(T)}, la condición de igualdad de los potenciales químicos implica:

= RvTinP^Í
Pt	P*
esto es:
Pv, sai
= exp
P ~ P*(T)
RvTpi ,
1 +
P ~ P*(T)
RvTpi
p - p*(T)

si  ------—- < 1, cosa que sucede si, en el intervalo de temperaturas normales de trabajo, p <
RvTpi
P ~ P*(T)
140 MPa. Y si ponemos que pVySat = P*{T) el error que se comete es del orden de —------X
-L^V-L Pl

100. Así pues, en todos nuestros análisis de procesos de aire húmedo, cuando tengamos el aire en equilibrio con agua líquida tomaremos como presión de saturación la correspondiente al agua como sustancia pura.
