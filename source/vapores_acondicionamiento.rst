Acondicionamiento de aire
=========================

Por acondicionamiento de aire se entiende cualquier proceso o conjunto de procesos que actuando sobre el aire atmosférico lo hace más adecuado para su uso en una aplicación determinada que requiere unas condiciones predefinidas. Esas condiciones pueden ser necesarias para obtener un cierto bienestar fisiológico en personas, animales o plantas, preservar materiales almacenados, etc.

En general, las condiciones del aire que se obtiene en el proceso de acondicionamiento vendrán dadas por unos valores determinados de temperatura y humedad. Por tanto todos los sistemas y procesos que se utilizen en el acondicionamiento irán dirigidos a obtener esas condiciones.

En esta sección es estudian algunos procesos típicos de acondicionamiento de aire haciendo uso de las propiedades del aire húmedo, así como de los diagramas de Mollier y del diagrama psicrométrico desarrollados anteriormente. Conviene señalar que los valores de las propiedades termodinámicas del agua y del aire seco pueden tomarse de las correspondientes tablas de propiedades termodinámicas de las respectivas sustancias.

Como se ha citado anteriormente, en un sistema de acondicionamiento, dependiendo de las condiciones del aire atmosférico, se tendrán que utilizar de forma conjunta diversos procesos que den como resultado las condiciones deseadas. En general los procesos utilizados en acondicionamiento de aire son: deshumidificación, humidificación, calentamiento y enfriamiento, y mezcla adiabática de corrientes de aire húmedo. Dichos procesos se estudian de forma individualizada, para dar finalmente algunas ideas sencillas de como agruparlos para conseguir el fin requerido.



Introducción a los procesos con aire húmedo
-------------------------------------------

Antes de proceder al estudio de los procesos elementales para el acondicionamiento de aire citados anteriormente, conviene describir un gráfico adicional que aparece en algunos diagramas psicrométricos, así como la escala que aparece en el diagrama de Mollier y que proporcionan el valor de la relación entre las diferencias de entalpia y diferencias de humedad entre dos estados.

1.	El gráfico que aparece en el diagrama psicrométrico (fig.6) proporciona la relación entre las diferencias de entalpia y diferencias de humedad entre los estados inicial y final de cualquier proceso. Es decir

.. math::

   q' = \frac{\text{variación de entalpía}}{\text{variación de humedad}} = \frac{h_2 - h_1}{\omega_2 - \omega_2} = \frac{\Delta h}{\Delta \omega}


Es útil para determinar dichos estados (inicial o final), o el calor transferido en el proceso, como se verá posteriormente con algún ejemplo.

.. figure:: ./img/diag_psicrometrico.png

   Diagrama psicrométrico

   
Para ver que es lo que exactamente representa, supongamos que tenemos un cierto sistema (fig.7) en el que entra una corriente de aire en unas condiciones 1 y sale en unas condiciones 2. A través de la frontera del sistema hay un cierto intercambio de calor y al sistema se le añade o quita una cierta cantidad de agua.
Fig. 7

.. figure:: ./img/acondicionamiento_fig7.png

Aplicando al sistema el principio de conservación de la masa y de conservación de la energía (sistema abierto en régimen estacionario) se obtiene:

a)	Conservación de la masa:

    * para el aire seco
    
    .. math::
    
       \dot{m}_{a_1} = \dot{m}_{a_2} = \dot{m}_a


    * para el agua
    
    .. math::
       
       \dot{m}_{v_1} + \sum_e \dot{m}_{w_e} = \dot{m}_{v_2} + \sum_s \dot{m}_{w_s}

b)	Conservación de la energía (suponiendo que las variaciones de las energías potencial son despreciables):

.. math::

   \dot{Q} = \dot{m}_{a_2} h_{a_2} + \dot{m}_{v_2} h_{v_2} + \sum_s (\dot{m}_w h_w)_s - \dot{m}_{a_1} h_{a_1} - \dot{m}_{v_1} h_{v_1} - \sum_e (\dot{m}_w h_w)_e
   

Teniendo en cuenta que

.. math::

   \dot{m}_{v_1} = \omega_1 \dot{m}_{a_1} \\
   \dot{m}_{v_2} = \omega_2 \dot{m}_{a_2}

de la ecuación (10.46) se obtiene

.. math::

   \sum_e \dot{m}_{w_e} - \sum_s \dot{m}_{w_s} = \dot{m}_{a} (\omega_2 - \omega_1)

y de la ecuación (10.47) se obtiene

Q — rila ( ha2 hal ) + rila(hy 2^2 hyl ^1 ) "f" ^ ^ i^riílyjllyj )g ^ ( riflyj hyj )
5	e

Esta última ecuación se puede expresar como

Q + Y^ {diwhw)e - ^(m»/!«,), = rha(/i2 - hi)
e	s
y con el valor de ma obtenido en la ecuación (10.48)
Q + Y (riiwhw)e	y ^ (ririyjhyj)$
______e_____________3____________ _	^2 - frl
Y”lw‘~Ylh^»	U2-U!
e	s

que es precisamente el valor q' que da el diagrama psicrométrico, es decir

/	^2 h\ Qneto
q = -------- = -------
w2 - uq mWneto
(10.45)
(10.46) cinética y
(10.47)
(10.48)
S
(10.49) (10.49a)

Por lo tanto, de lo anterior se concluye que dado, por ejemplo, el estado del aire húmedo a la entrada, todos los demás posibles estados del aire a la salida estarán sobre una recta cuya pendiente es q' y que pasa por el punto dado por las condiciones a la entrada.


En el diagrama de Mollier aparece una escala que proporciona, igual que en el caso anterior, el valor de la relación entre las diferencias de entalpia y diferencias de humedad entre dos estados de un proceso (fig.8).

Fig.8

2.	En el mismo gráfico que aparece en el diagrama psicrométrico, citado anteriormente, hay otra escala que proporciona el ”Factor de calor sensible” (FCS) y que da el cambio de entalpia asociado con un cambio en la temperatura seca dividido entre el cambio de entalpia total. Para el proceso entre un estado 1 y un estado 2 (fig.9)

Fig.9
donde 02¡ = 02 y u2i = u>\.
FCS
h2i — h\ h2 — h\

Para ver el significado del FCS una manera más simple, volvamos al sistema introducido en el punto anterior. Si se supone que no se añade, ni se quita agua, del sistema (mWc =

= 0) resulta un proceso ficticio tal que a partir de la ecuación (10.49)
, h Q
h,2> — h\ = —— ma

mientras que en el proceso real /12 - Ai vendría dado por la ecuación (10.49) conservando todos los términos. Por tanto el factor FCS se puede definir como la relación entre el calor neto que se comunica al sistema y la energía total añadida al sistema (incluyendo la cantidad de energía que posee el agua añadida y que vendría dada por su entalpia), quedando

Ó
]?(j § — _______________—________________
Q 4“ X)e (^w^to)e {jdlulhw^s

Deshumidificación
-----------------

El proceso mediante el cual se consigue disminuir la humedad de una mezcla de aire-vapor de agua se denomina deshumidificación.

Si una corriente de aire húmedo se enfría a presión constante hasta alcanzar una temperatura menor que su temperatura de rocío (9 < 9r), parte del vapor de agua se condensa, quedando
Como el aire que se obtiene está a una temperatura menor que la del aire antes de la deshumidificación, y en general se requiere utilizar el aire a una temperatura parecida a la de la corriente inicial, se suele proceder posteriormente a calentar dicha corriente hasta alcanzar la temperatura deseada, proceso que se estudiará posteriormente (calentamiento).

Fig. 10

La instalación, como se muestra en la fig.10, constará de un cambiador de calor (por el que circulará un fluido refrigerante) con el que se enfría la corriente de aire.

Fig. 11
Fig. 12


En las fig.ll y 12 se representa el proceso, seguido por el aire, en el diagrama de Mollier y en el diagrama psicrométrico, respectivamente, mientras que en la fig.13 se representa el proceso seguido por el agua en un diagrama (T-s).

En un proceso real hay que hacer notar que:

a)	El aire no se enfría todo a la misma temperatura, ya que el aire que pasa cerca de la superficie del refrigerador estará a menor temperatura que el aire que pasa a una cierta distancia.
b)	El agua que se condensa no lo hace todo a la misma temperatura. La razón de esto, es que cuando la mezcla alcanza la temperatura de rocío [0r) de las condiciones iniciales, parte se condensa a esa temperatura. La mezcla continua posteriormente condensándose y variando su temperatura desde 9r a 02- (fig.12)

Lo anterior nos lleva a establecer dos hipótesis simplificadoras antes de proceder a realizar el análisis del proceso:
a) Todo el aire húmedo se enfría a la misma temperatura antes de dejar el sistema.
b) Todo el líquido condensado se enfría a la temperatura de salida del aire húmedo antes de salir del sistema, es decir,

9¡ = 02
El error introducido con esta hipótesis es pequeño debido a que la entalpia del agua líquida es pequeña frente a la entalpia de la corriente de aire.

Para el proceso, en régimen estacionario, se tienen las siguientes ecuaciones:

a)	Conservación de la masa:
•	para el aire seco
rn-m = dia2 = ma	(10.50)
•	para el agua
mVl = ñu + mV2	(10.51)


b)	Conservación de la energía (suponiendo que las variaciones de las energías cinética y potencial son despreciables):

Q = ma2ha2 + mV2hV2 + m¡h¡ - maihai - mVlhVi	(10.52)


Teniendo que cuenta que

mv j = uq mQl
TTiy^ — ^2^a2
y con la ecuación (10.51) se obtiene
m¡ = róa(uq - u2)
y la ecuación (10.52) se reduce a
Q = m0(/ia2 - hai) + ih¡h¡ + ma(hv2u2 - hv\ui)
que se puede expresar como
Q = ma(h2 - hi) + ma(üJi - u2)h¡
(10.53)

El último término de esta expresión representa la cantidad de energía extraída del sistema, debida a la condensación del agua. En general, este término, comparado con el primero se puede despreciar en muchos cálculos.

Ejercicio 10.1

Para cierto proceso se necesita tener aire saturado con una humedad de 0,007 kg/kg. Se utiliza 0,5 kg/s de aire atmosférico a 25°C y con una humedad relativa del 60%.

Calcular la cantidad de calor que se necesita extraer del aire para obtener las condiciones deseadas.
La presión atmosférica es 1 bar.

Solución

El calor que hay que extraer se calcula a partir de la ecuación (10.53)
Q = ma(h2 - hi) + ma(ux - LJ2)h¡
Se necesita conocer el valor de ma, y puesto que
resulta que
m = ma + mv = ma(l + u>)
ma
m
1+^2
0,5kg/s 1 + 0,007kg/kg
0,4965kg/s

De la ecuación (10.6)

y de la ecuación (10.4)

Pv — 4>i ' p*(25°C)
pVl = 0,6-0,031696ar = 0,019014¿>ar
u>\ - 0,622-
Pv 1
ui\ = 0,622-
P-Pvx
0,019014
= Q,Q\2kg¡kg
1-0,019014

También es preciso calcular 82. Como a la salida el aire está saturado, de la ecuación (10.4)

P2 =
P-lj2
1-0,007
= 0,01138óar
0,622 -^2	0,622 - 0,007

Con este valor y la tabla de propiedades termodinámicas del agua en saturación

82 = 8,9 °C

El valor de la entalpia es

h2 = cPa02 + w2[M0re/) + Cp„02] = 1,005 - 8,9 + 0,007(2501,4+ 1,82 - 8,9] = 26,57kJ/kg
hi = cPa81 + wi [h¡v(8ref) + cp„0i] = 1,005 ■ 25 + 0,012(2501,4 + 1,82-25] = 55,69kJ/kg
h¡ = c¡8¡ = 4,18-8,9 = 37,2 kJ/kg

De lo anterior se obtiene

Q = 0,4965(26,57 - 55,69) + 0,4965(0,012 - 0,007) • 37,2 Q = -14,37 kj/s

Humidificación
--------------

La humidificación es el proceso contrario al estudiado anteriormente, es decir, consiste en el aumento de humedad de una mezcla de aire-vapor de agua.

Para lograrlo se pueden utilizar varios i	2	procedimientos: inyectar vapor de agua o pul-
verizar agua líquida en la corriente de aire (fig-14).

Según se utilice uno u otro procedimiento la temperatura a la salida (82) será mayor o menor que la temperatura a la entrada (#i), por lo que este proceso nos permite, según los casos, obtener un efecto simultáneo de calefacción o refrigeración (calentamiento o enfriamiento del aire tratado).

Fig. 14

En el caso de inyectar vapor de agua a alta temperatura, la humedad y temperatura a la salida ((^2,^2) aumentan, estando representado el proceso, en el diagrama de Mollier y en el diagrama psicrométrico, como se muestra en las fig.15 y 16 respectivamente.

Si por el contrario, lo que se hace es inyectar agua en estado líquido, la temperatura a la salida ($2) será menor que la temperatura a la entrada ($i), quedando el proceso representado en los diagramas de Mollier y psicrométrico como se muestra en las fig.17 y 18.

Las ecuaciones que gobiernan el proceso de humidificación son las siguientes:

a)	Conservación de la masa:
•	para el aire seco
ma 1 = ma2 = ma	(10.54) •
•	para el agua
m„ j + m¡ = mV2	(10.55)

En este caso m¡ puede representar el gasto de agua líquida o vapor aportado.

b)	Conservación de la energía en régimen estacionario (suponiendo que las variaciones de las energías cinética y potencial son despreciables):

0 —	4"	4“ Th¡h¡ rrid^ha? 771 ^hv2	(10.56)
También h¡ puede representar la entalpia del líquido o vapor aportado, según los casos.

Teniendo en cuenta las ecuaciones (10.54) y (10.55) y que

m» j = uimai mU2 = u>2ma2

la ecuación (10.56) se reduce a

m¡h¡ —	hai) T ^ha(k^2^u2 ^í^vi)

o lo que es lo mismo

hi = íi—(10.57)

Las ecuaciones (10.55) y (10.57) nos permiten, conocidas las condiciones del aire a la entrada y salida del sistema, determinar la cantidad y condiciones en las que es preciso introducir el agua o el vapor. Si por el contrario, se conoce la cantidad y condiciones en las que se introduce el agua y uno de los estados inicial o final, el otro se determinaría utilizando la ecuación de la energía (10.56) y la de conservación de la masa (10.54, 10.55) o de forma semigráfica a partir de la ecuación (10.57), teniendo en cuenta que

h¡
h2 — h\ , — Q
U)2 —

y utilizando el transportador del diagrama psicrométrico o del diagrama de Mollier. Para ello, conocida h¡, y por tanto la pendiente de la recta que une el estado 1 y el estado 2, se traza dicha recta en el diagrama adjunto al psicrométrico y posteriormente una paralela a esta que pase por el punto 1 o 2 (el que esté determinado) en el diagrama psicrométrico, el otro punto estará situado sobre dicha recta y para determinarlo se necesita otra condición adicional.

Ejercicio 10.2

Cierto día se alcanza una temperatura de 34°C , con una humedad relativa del 20%. Para acondicionar una vivienda se utiliza un sistema de humidificación adiabática.

Si a la salida se requiere tener una temperatura de 21°C, determinar de forma analítica y con el diagrama psicrométrico la cantidad de agua que hay que añadir al aire y la humedad relativa del mismo.

La presión atmosférica es de 1 bar y el agua se suministra a la temperatura de salida del aire.

Solución

De la ecuación (10.6) se obtiene

Pv = <f> ■ P*

p* de las tablas de propiedades termodinámicas del agua en saturación a 0 — 34°C es

p*(34°C) = 0,053245ar
pv- 0,2-0,05324 = 0,0106486ar


De la ecuación (10.4)
un = 0,622 • —= 0,622 •	= 6,694 • 10~3kg/kg
P-Pv
1 - 0,010648

De la ecuación (10.57)

h2 - hi = (lj2 - u>i )h¡ y con las ecuaciones (10.17) y (10.18)
h = cpJ + u[hlv(0rej) + cPv0]
P ~ Pref
h¡ = c¡6 -f
Pl
(17)
(18)
U)2 -
CpJ 2 + w2 [hlvjrej) + CpJ2] ~ CpJl - Wj [h¡v(6ref) +'cp„01] = (w2 - V\ )cfi¡
_ [hlyjref) + cpJ\ - C¡0[] -f Cpa(6i - Oj) hlvjref) + cpJi - c¡0,
cPv — 1,82kJ ■kg~1K~1
cPa = 1,005&J • kg~1K~1	p*(21°C) = 0,02487¿>ar
c¡ = 4,18kJ ■ kg 1K 1
29,6359 2451,84
u>2 =

De la ecuación (10.4) y de la ecuación (10.6)

Pv
= 0,012087kg/kg
u • p
u2p
0,622 u 0,012087-1
, _ Py , _ _
9 p* 92	(0,622 -f w2)p*	(0,622 + 0,012087) -0,02487
— = (w2 - wi) = 5,39 • 10~3kg/kg ma

La resolución utilizando el diagrama psicrométrico se deja como ejercicio.

= 0,7665 = 76,65%

Ejercicio 10.3

Para tratar una corriente de aire húmedo a una temperatura seca de 21 °C y una temperatura húmeda de 8°C, se inyecta adiabáticamente vapor saturado a 110°C, hasta que su temperatura de rocío es \“i0C.
El gasto músico de aire seco es de 90 kg/min.
Determinar el gasto músico de vapor, en kg/h, necesario y la temperatura final del aire obtenido.
Se puede suponer que la presión total se mantiene constante en un valor de 1 bar. Solución
A partir de la ecuación (10.55) se obtiene

rhi = rnV7 - mvi = (u2 - uq )ma

y por tanto es necesario calcular la humedad del aire a la entrada y salida del humidificador.

Para calcular uq, como conocemos la temperatura húmeda a la entrada y utilizando su definición, al aplicar el principio de conservación de la energía a ese proceso (1 — 2') se obtiene

h i + (u>2' — uq)/q = h2i
hai + í*q/i„i + (u2i — uq)/q = h2i -f- u>2'hv2i
cPa01 + «i [hlv(9re/) + cVv61] + (u2> - u>i)c¡9, = cPa62- + u>2» [hlv(9ní) + cpJ2,] cPa(02, - 6i) + u>2, [hiv(9ref) + cPv02- - c¡9¡]
(jJ-^	_ _______________________________________
^iu(^re/) d" Cpv91 ~ C¡9¡
El valor de u2< se calcula a partir de la ecuación (10.4)
u>2< = 0,622	= 0,622—-—
P ~ Pv2,	P~P*

obteniendo p* de las tablas de propiedades termodinámicas del agua en saturación (p* = 0,01072óar).

u2i = 0,622-	- = 6,74 • 10~3kg/kg
1 - 0,01072
_ 1,005(8- 21)6,47-10~3(2501,4 + 1,82-8 -4,18-8)
Wl “	2501,4 + 1,82-21 - 4,18-8
u>i = 1,46 • I0~3kg/kg



Paxa calcular la humedad a la salida (w2), a partir de la ecuación (10.4) y teniendo en cuenta que la presión de vapor a la salida es igual a la presión de vapor saturado a la temperatura de rocío (13°C), de las tablas de propiedades termodinámicas del agua en saturación p*(13°C) = 0,01497¿>ar y por tanto pv = 0,014976ar, quedando

u;2 = 0,622 —	= 0,622	= 9,45 - 10~3fc^/^
p — pv	1 — 0,01497

m, = rna(u>2 - uq) = 90 • 60(9,45 • 10"3 - 1,46 • 10“3) = 43,15kg/h Para calcular la temperatura a la salida, mediante la ecuación (10.57)
h2- hi = h¡(u2 - wi)
cPa^2 + U2[hlv(0ref) + cp„^2] _ cpa^l —'	\hlv(@ref ) 4" cp„$l] = [h¡v{0ref ) + Cpv #/](uJ2 ~ Wj)
„ [h¡v(9ref) + cPtl0¡](iJ2 - wi) + cPa9\ + u)i[h¡v(9ref) + cPv#i] - cj2h;v(0re/)
“2 — ---------------------------- ;
CPa + W2 Cp„
(2501,4 + 1,82-110)(9,45 - 1,46)- 10~3 + 1,005-21 2_	1,005 + 9,45-10-3-1,82	+
1,46 • 10_3(2501,4 + 1,82 • 21) - 9,45 • 10~3 • 2501,4 +	1,005 + 9,45-10-3 • 1,82
92 = 22,27°C

Calentamiento y enfriamiento
----------------------------

El calentamiento y el enfriamiento son procesos muy sencillos, en los que su único fin es aumentar o disminuir la temperatura del arre húmedo sin variar su humedad. Para conseguir esto se hace pasar el aire húmedo por un cambiador de calor por el que circula un fluido caliente o un refrigerante según sea el caso. En la fig.19 se representa un esquema de la instalación y en las fig.20 y 21 se representa, en el diagrama de Mollier y en el diagrama psicrométrico, el proceso que tiene lugar.

Fig. 19


Las ecuaciones que resuelven el problema son

a)	Conservación de la masa:

•	para el aire seco
mQl = ráa2 = ma	(10.58)
•	para el vapor de agua
rhvi = rhv 2	(10.59)

b)	Conservación de la energía (suponiendo que las variaciones de energía cinética y potencial son despreciables):

Q — ñia2/i02 T	di.a^ha^ iriy^hy^	(10.60)

Teniendo en cuenta que

mvi = uqmai mV2 = u2rna7

de la ecuación (10.58) y (10.59) resulta que

U>1 — U) 2


como se había indicado anteriormente. De la ecuación (10.60) se obtiene

T
Q = ma(h2 - hi)
(10.61)

y por tanto el calor que es necesario comunicar o extraer es igual a la variación de entalpia de la corriente de aire húmedo.

En general es un proceso a presión total constante, y por tanto, en el diagrama (T-s) para el agua, el proceso tendrá lugar en la región de vapor sobrecalentado como se puede ver en la fig.22.

Fig.22


Ejercicio 10.4

Se desea obtener 0,83 kg/s de aire a una temperatura de 35°C. Para ello, se utiliza aire atmosférico a una temperatura de 4°C y con una humedad de 0,0045 kg/kg, que se hace pasar por un cambiador de calor que aumenta su temperatura hasta el valor deseado. Calcular la cantidad de calor que es necesario suministrar para realizar dicho proceso.

La presión atmosférica es 1 bar.

Solución

El valor pedido se calcula a partir de la ecuación (10.61)

Q = m0(/i2 - hi)

Puesto que y por tanto

m
ma
m = rha + rhv — ma( 1 + w) 0,83kg/s
1 + w 1 + 0,0045kg/kg
= 0,826kg/s
De la ecuación (10.17)
h — cPa6 + w [h¡v(u>ref -)- Cpv6]
queda
/ii = 1,005-4 + 0,045(2501,4 + 1,82-4] = I5,3kj/kg h2 = 1,005-35+ 0,0045(2501,4+ 1,82-35] = 46,7kJ/kg y por tanto la cantidad de calor que hay que suministrar es
Q — 0,826kg/s(46,7kJ/kg — I5,3kj / kg) = 25,9 kJ/s

Mezcla adiabática de corrientes de aire húmedo
----------------------------------------------

Otro proceso que es de interés técnico es la mezcla de corrientes de aire húmedo. El estudio se realiza para el caso del mezclado de dos corrientes, pudiéndose extrapolar fácilmente a cualquier otro número.

Se supone que el proceso es adiabático y que las variaciones de energía cinética y potencial son pequeñas En general se conocen las condiciones (gasto y estado) de cada una de las corrientes que se mezclan y se pretende calcular el gasto y el estado de la corriente que se obtiene.

Fig.23


Las ecuaciones de las que se dispone para resolver el problema, igual que en casos anteriores
son:

a)	Conservación de la masa:

•	para el aire seco
mai + m0¡ = ma3	(10.62)
•	para el vapor de agua
mVl + m„2 = m„3	(10.63)

b)	Conservación de la energía:

0 — maihai 4“ hv^ 4"	2 4“	(10.64)
Teniendo que cuenta las ecuaciones (10.62) y (10.63) y que
mVl = uqmai Tíl y 2 — ^2 TTla.2
TTl\)$ — ^3^1(13

resulta que

U>3 —
u>imai +u2ñia2
maj 4” di(j2

De la ecuación (10.64) se obtiene
.	j/ir 4“ dia2/12
= —:------—:-------
Tila i i Tila2
(10.65)
(10.66)

De las dos ecuaciones anteriores, conocidas las condiciones de entrada, se puede calcular la humedad y entalpia de la corriente de salida.

En el diagrama psicrométrico el proceso podría venir dado por cualquiera de los indicados en las fig.24 ó 25, dependiendo de las condiciones a la entrada. En las condiciones mostradas en la fig.25, el proceso vendría representado en el diagrama de Mollier como se muestra en la fig.26.

Fig.26



A partir de las ecuaciones anteriores, combinándolas adecuadamente, se obtienen las relaciones
ñrai _ hj, — /¿2 _	~ u2
171(12	— ^3	— u 3
(10.67)

De estas relaciones se obtiene una interesante interpretación geométrica en el diagrama psicrométrico y que puede observarse en las fig.24, 25 ó 26. Las relaciones citadas nos indican que el estado de la corriente a la salida se encuentra sobre la recta que une los puntos de las condiciones a la entrada.

Ejercicio 10.5

En el proceso de acondicionamiento de un edificio se han de mezclar adiabáticamente 75 m3/min de aire exterior a 30°C y 80% de humedad relativa con 100 m3/mm de aire interior tratado a 19°C y 30% de humedad relativa.

Determinar para la mezcla resultante:

a)	Humedad.
b)	Temperatura seca.
c)	Temperatura húmeda.
d)	Humedad relativa.

Resolver el problema analítica y gráficamente suponiendo que la presión se mantiene igual a 1 bar.

Solución

Antes de nada vamos a calcular los gastos, humedad, y entalpia en las entradas.
De la ecuación (10.6)

Pv =
y con los valores de p* obtenidos de las tablas de propiedades termodinámicas del agua en saturación
p\ = 0,042466ar	p*2 = 0,021986ar
pVi = 0,8-0,04246 = 0,0339686ar	pV2 = 0,3 • 0,02198 = 0,0065946ar
y por tanto
pai = 1 — 0,033968 = 0,9666ar
Pa2 = 1 — 0,006594 = 0,9936ar


De la ecuación de estado p ■ V = m • R ■ T para el aire queda

.	_ paiVx 0,966 • 105 • 75
ma2 =
RaTi 287•303 Pa2V2 _ 0,993-105-100
= 83,31 kg/min — 118,5 kg/min

RaT2 287•292 Para calcular la humedad recurrimos a la ecuación (10.4) puesta en la forma
,Pv

u = 0,622-
Po.
aq = 0,622°’0Q39369668 = 0,02187%/%

u>2 = 0,6220 q^4 = 0,00413%/fcg Para calcular las entalpias recurrimos a la ecuación (10.17)

h = cPa9 + u [hlv(6ref) + cPv9]
hi = 1,005-30+ 0,02187 [2501,4 + 1,82-30] = 86,05kJ/kg h2 = 1,005 • 19 + 0,004130 [2501,4 + 1,82 • 19] = 29,57kJ/kg a) De la ecuación (10.65)
+ ma2üj2 83,31-0,02187+ 118,5-0,004130 u>3 = ——---—------= ---------„„ „„ . „	„---------= 0,01145kg/kg
rilai + 777(22

b) De la ecuación (10.66)

ha -
83,31+118,5
mai h\ + 77^(22 h-2
mai + ma j
y como h3 = cPa03 + cj3 [h¡v(6ref) + cp„03] queda
0.3 =
dla\k\ + 77la2 ^2 777a2	"7a2
- W3h;„(0re/)
9a =
CVa + W3Cp„
83,31-86,05 + 118,5-29,57 83,31 + 118,5______________
- 0,01145-2501,4
1,005 + 0,01145-1,82 e3 = 23,6 °C
h3 = 52,88kJ/kg



c) Utilizando la definición de temperatura húmeda y para el proceso de saturación 3 — 3'

h-3 + (w3' ~ <^3 )h¡ = hy
y con
w3- = 0,622 Pv*' = 0,622-^—
P - Pv3,	P-P*
queda
52,88 + ( 0,622——---- 0,01145 ) 4,1803- = 1,00503' + 0,622—1-— [2501,4 + 1,8203-]
V 1 - P*	J	1 - P*

y reordenándola queda

0 = 50,225+ —^—[1,39403, - 1477,8] - 03» = y
1 — p

Para resolverla se utiliza el método de prueba y error, calculando p* en las tablas de propiedades termodinámicas del agua en saturación.

03-(°C)	p*(bar)	y
20,0	0,02339	-4,50
18,0	0,02064	1,61
19,0	0,02198	-1,39
18,5	0,02131	0,11

Por lo que tomamos Ohúmeda3, = 18,5°C d) De la ecuación (10.6)

P

y de la ecuación (10.4)

u = 0,622
P,T
Pv
P-Pv

y con p*(23,6°C) = 0,029156ar se obtiene

ujp	0,01145-1
<t> =
(0,622 + u>)p*	(0,622 + 0,01145) • 0,02915
<f> = 62%

La resolución gráfica se deja como ejercicio.

0,62


Ejercicio 10.6

Se mezclan 2 m3/s de aire a una temperatura seca de 4°C y una temperatura húmeda de 2°C con 7 m3/s de aire a una temperatura de 25°C y con una humedad relativa del 50%.

Determinar la temperatura seca y húmeda de la corriente resultante.

Solución


Entrando en el diagrama psicrométrico con la temperatura seca (4°C) y la temperatura húmeda (2°C) de la corriente se obtiene un valor del volumen específico de

v\ - 0,789m3/kg

Entrando en el diagrama psicrométrico con la temperatura seca (25°C) y con el valor de la humedad relativa (50%) de la otra corriente se obtiene un valor del volumen específico de

V2 — 0,858m3/kg

De lo anterior se obtiene que

7Hn i —
771 o o —
0,789
= 2,53kg/s
= 8,16kg/s

y con la ecuación (10.67)

02	0,858
u>3 - u>2 _ m0l _ 2,53kg/s - u>3 ma2	8,16kg/s
= 0,31

De igual forma

uq - u3 ma2
m„
8,16
= 0,76
ui - u>2 ma3 mai + ma2 2,53 + 8,16

y por tanto para calcular el punto 3, que estará en la recta que une el punto 1 y 2, simplemente hay que tener en cuenta que la distancia entre los puntos 1 y 3 es 0,76 veces la distancia entre el punto 1 y 2.
De lo anterior se obtiene que 03 = 20,2°C 0húmedo3 = 13 C




Sistemas de aire acondicionado
------------------------------

Cualquier sistema de acondicionamiento de aire estará integrado por un conjunto de los procesos estudiados anteriormente. Los procesos utilizados podrán variar más o menos respecto a los descritos, pero su fundamento será el mismo.

• Acondicionamiento de verano:

En general la temperatura y la humedad relativa suelen ser bastante altas por lo que se procede a acondicionar el aire disminuyendo su temperatura y humedad. Para conseguir lo anterior se realiza un proceso de deshumidificación hasta conseguir un valor de humedad tal que, si la temperatura resultante es demasiado baja, al proceder a realizar un calentamiento, la humedad resultante sea la adecuada. En la fig.27 se representa el proceso en un diagrama de Mollier.

Si la temperatura fuese elevada y la humedad relativa baja (clima continental o desértico) se puede obtener un enfriamiento adecuado sin más que hacer pasar el aire por una cámara de saturación adiabática (humidificación), proceso que se conoce como enfriamiento por evaporación.

Si el clima (como suele suceder en invierno) es seco y frió se procede a realizar un calentamiento, seguido de un proceso de humidificación, hasta conseguir la humedad deseada, y por último otro proceso de calentamiento. En el diagrama de Mollier el proceso vendría representado como se muestra en la fig.28.

Fig.28

En los sistemas de acondicionamiento se suele recurrir además a mezclar dos corrientes de aire, una procedente del interior del espacio a acondicionar y la otra procedente del exterior.

En la fig.29 se esquematiza una instalación muy simple que puede utilizarse para acondicionar un cierto espacio. Dependiendo de los requisitos y condiciones exteriores entrarán en funcionamiento unos sistemas u otros.

enfnam numkí. cal«nt.

Fig.29

cal«nt.


Ejercicio 10.7

En un recinto entra una cierta cantidad de aire a una temperatura de 15°C. Debido a la actividad que se produce en el recinto se liberan 8 kJ/s de calor y se añaden 1,4 • 10~3 kg/s de vapor de agua saturado a 30°C. Después de estos procesos, el aire sale del recinto a 25°C de temperatura seca y 19°C de temperatura húmeda.

Determinar la temperatura húmeda del aire que entra al recinto y su volumen específico.

Solución

Este problema puede resolverse de forma analítica, como se ha hecho en otros, o de una manera más simple utilizando el diagrama psicrométrico.

De las tablas de propiedades termodinámicas del agua en saturación, la entalpia de vapor de agua a 30° C es 2556 kJ/kg.

De la ecuación (10.49a)
Q +	-£( mwhw)s
»2 — m__________e_____________«_________
U>2 ~ <¿1 E diwc y ] daWs
e	a
/&2 — ^1 U2 ~ «l
8 + 1,4 -10-3-2556 1,4 • lO"3
= 8270fc<7 / kdagua

Entrando con este valor en el gráfico adicional del diagrama psicrométrico se obtiene la pendiente de la recta sobre la que se encuentran los puntos inicial y final.

Del diagrama se obtiene un valor de

Qhúmedoi = 14°C Vi = 0,829m3/kg

Otra manera de resolver el problema es utilizando la definición del factor FCS. En este caso

FCS =-.-----^	.------
Q 4" / .(dnwhw)e /
e	s
FCS =
________8________
8+ 1,4-10~3- 2556
0,69

y entrando con este valor en el gráfico del factor FCS del diagrama psicrométrico se procede igual que antes, obteniendo un resultado análogo.



Ejercicio 10.8

Un día de verano las condiciones atmosféricas son:

a)	Presión atmosférica 985 bar.
b)	Temperatura 32°C.
c)	Humedad relativa 70%

A partir de estas condiciones se desea obtener aire a 22°C y una humedad relativa del 45%. Para ello se dispone de una unidad de refrigeración y otra de calentamiento que proporcionan aire er 'as condiciones deseadas.

Determinar:

a)	La cantidad de agua eliminada en kg/kg^¡re seco.
b)	El calor extraído por la unidad de refrigeración en kJ/kg^re seco-
c)	La cantidad de calor cedido en la sección de calentamiento en kJ¡kg^ 8eCo-

Solución:

El proceso seguido por el aire será como el representado en la Fig.27. En la solución del problema se seguirá la nomenclatura de dicha figura.

a) De la ecuación (10.4) y (10.6) se obtiene
u = 0,622
P*4>
p — p*(f>
De las tablas de propiedades termodinámicas del agua en saturación
p*(32°C) = 47,59mbar p*(22°C) = 26,45mbar
y por tanto
ui = 0,622 = 0,622
°’7-47,59	= 2,18-10 ~2kg/kg
985- 0,7-47,59 0,45-26,45
985- 0,45-26,45 La cantidad de agua eliminada es
= 7,61•10~6kg/kg
Au; = u>4 — uq = -1,42 • 10 2kg/kg



b)	De la ecuación (10.53)

Q - rha(h3 - hx) + ma(üq - u3)hi Ú = (^3 ~ hi) + (uq — u>3)h¡
Necesitamos conocer la temperatura en el punto 3 y para ello sabemos que la temperatura en el punto 3 se corresponde con la temperatura de rocío correspondiente al punto 4. De la ecuación (10.8)
Td(k, _ UK) _	295	_
M	T4(üQln04 ~~	295 -ln 0,45 ~ 282K
5121	5121
0fi = 9,O3°C'
03 = 0l = OR = 9,03°C
Además
o>3 =	— 7,61 • 10 ~3kg/kg
q = cPa(03 - #i) + h¡v(9Tef)(u3 - uq) + cPv(u303 - uq6\) + (uq - üj3)c¡6i q= 1,005(9,03 - 32) + 2501,4(7,61 • 10'3 - 2,18 • 10"2)+
+ 1,82(7,61 • 10~3 • 9,03 - 2,18 • 10~2 • 32)+
+(2,18 • 10~2 - 7,61 • 10~3) -4,18- 9,03 q = -59,19 kJ/kg
c)	De la ecuación (10.61)
Q = ma(h4 - h3)
q = (h4 ~ h3)
9 = cpa(^4 — ^3) + hiv(0ref)(uj4 — u>3) + cPv(u40 4 — u393) y puesto que u>4 = u3 queda
Q = cpa(04 ~ #3) +	u>3(94 - 93)
9 = (cPa + cPvw3)(é,4 - 93) q = (1,005 + 1,82 • 7,61 • 10_3)(22 - 9,03)kJ/kg q — 13,2kJ/kg

El problema se puede resolver fácilmente utilizando el diagrama de Mollier, obteniendo resultados análogos.
