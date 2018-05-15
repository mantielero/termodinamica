Sistemas Multicomponentes. Mezclas No Reactivas de Gases
========================================================


Antonio Sánchez Sánchez

Pablo de Assas Marinez de Morentin

.. toctree::
   :maxdepth: 1
   :caption: Contenido:
   
   multicomponentes_gases_reales


TEMA 9
SISTEMAS MULTICOMPONENTES. MEZCLAS NO REACTIVAS DE GASES
Introducción : descripción de la mezcla.	1
9.1	Propiedades molares parciales.	2
9.2	Potenciales termodinámicos para sistemas multicomponentes. Potencial químico.	6
9.3	Fugacidad y coeficiente de fugacidad.	10
9.3.1	Sistemas monocomponentes.	10
9.3.2	Evaluación de la fugacidad para gases a partir de datos p, v, T.	12
9.3.3	Evaluación de la fugacidad cuando el sistema se presenta como líquido o sólido. 13
9.3.4	Sistemas multicomponentes.	15
9.4	Disolución ideal	17
9.4.1	Potencial químico para disoluciones ideales.	19
9.5	Exergía en mezclas: exergía química; exergía total.	20
9.6	Mezcla de gases ideales:	21
9.6.1	Relaciones p, v, T para mezcla de gases ideales.	21
9.6.2	Propiedades termodinámicas de la mezcla de gases ideales.	23
9.6.3	Procesos de mezclado en los que intervienen gases ideales.	24
9.6.4	Variaciones de las propiedades termodinámicas.	26
9.7	Mezcla de gases reales:	27
9.7.1	Relaciones p, v, T para mezcla de gases reales.	28
9.7.2	Propiedades termodinámicas para la mezcla ideal de gases reales.	29






Introducción: descripción de la mezcla
--------------------------------------

Hasta ahora hemos fijado nuestra atención en sistemas homogéneos monocomponentes. En este tema se considerarán algunos aspectos generales de las propiedades de un sistema con dos o más componentes. El interés primordial está en el caso de mezcla de gases, pero el método que se desarrolla también se aplica a disoluciones. Cuando lo que se considera objeto de estudio son líquidos o sólidos, se usa el término de disolución en vez de mezcla. La discusión presente se limita a mezclas no reactivas o disoluciones en una sola fase. El efecto de reacciones químicas y el equilibrio entre diferentes fases se consideran más adelante.
Para describir los sistemas multicomponentes se debe incluir la composición en nuestras relaciones térmodinámicas. Esto lleva a la definición y desarrollo de conceptos, algunos ya mencionados en temas anteriores y otros nuevos, que incluyen las propiedades molares parciales, el potencial químico y la fugacidad. Posteriormente se considerará el caso particular de la mezcla ideal de gases suponiendo que éstos tienen un comportamiento primero ideal y luego se extiende el estudio a gases reales. Para estas mezclas ideales de gases se dan las relaciones p, v, T y la variación de las propiedades termodinámicas energía interna, entalpia y entropía.
Descripción de la mezcla
La determinación del estado termodinámico de una mezcla precisa del conocimiento de la composición y del valor de dos propiedades intensivas independientes tales como la temperatura y la presión. El objetivo de esta sección es el considerar los modos de describir la composición de una mezcla.
Consideremos un sistema cerrado que consiste en una mezcla gaseosa de dos o mas componentes. La composición de la mezcla puede describirse dando la masa o el número de moles de cada componente presente. La masa, número de moles y la masa molar del componente i están relacionados por:
Tli =

Mi
(9.1)
del componente i
siendo
: cantidad de sustancia m,' : la masa Mi : la masa molar
Cuando se expresa en kg, ti¿ viene expresada en kmol.
La masa total de la mezcla, m, es la suma de las masas de sus componentes:
k
771 = 7711 + 7712 + • • • mk =	771*
Í=1
(9.2)
2
Sistemas multicomponentes. Mezcla no reactiva de gases
La cantidad relativa de cada componente presente en la mezcla queda especificada por la fracción másica xm¡:
m;
%mi —
m
(9.3)
Cuando una mezcla se describe con las fracciones másicas de los componentes se habla de análisis gravimétrico.
Dividiendo cada miembro de (9.2) por m, y haciendo uso de (9.3):

% mi
» = 1
esto es, la suma de todas las fracciones másicas de los componentes de una mezcla es igual a la unidad.
El número de moles en la mezcla, n, es la suma del número de moles de cada uno de los componentes:
= ni + 7í2 + • • • nk = ^ ni
(9.4)
»=i
Las fracciones molares- de cada componente es:
Xi =
1____
de modo que 1 =
¡=i
Cuando una mezcla se especifica por las fracciones molares de los componentes se habla de análisis molar.
La masa molar media (aparente) de una mezcla, M, se define como:
k

n n
'YjUíMí
M
i=i
= XíMí
(9.5)
í=i
esto es, la masa molar de la mezcla es una media ponderada de las masa molares de cada componente.








Propiedades molares parciales
-----------------------------

En la presente discusión se introducirá el concepto de propiedad molar parcial y se verá su aplicación. Este concepto juega un papel importante en el análisis de los sistemas multicomponentes.
Una propiedad termodinámica extensiva X de un sistema monocomponente y monofásico es una función de dos propiedades intensivas independientes y de la cantidad de sustancia del sistema. Eligiendo como variables independientes la presión y la temperatura y el número de
Sistemas multicomponentes. Mezcla no reactiva de gases
3
moles como medida de la cantidad de sustancia, tendremos X = X(T,p,n). Para un sistema monofásico-multicomponente, la propiedad extensiva X será, pues, función de la temperatura, la presión y del número de moles de cada componente, X = X(T,p, ) (i = 1,2, • • • , k)
Si cada número de moles de cada componente se multiplica por un factor a, la cantidad de sustancia del sistema quedará multiplicada por el mismo factor y así también el valor de la propiedad extensiva X. Esto es:
X(T,p, ani,an2 ■ • ■ ank) = aX(T,p, ri{)
Esta ecuación nos indica que X es una función homogénea de grado uno en los de modo que por el teorema de Euler de las funciones homogéneas podemos escribir
dX	dX
+ ••• + -—nk = X
OTl\	ouk
o lo que es lo mismo

*=1
=-1 í
"LAs
ij J X
X i s
T,p,n j
H:/’/'/ijt
(9.6)
* ÜA,.
donde el subíndice nj indica que todos los n excepto se han mantenido fijbs durante la diferenciación.	/
La propiedad molar parcial x; es por de^nición:
8X

j tcJüX . .
Xi = —	j Í i /	(9.7)
T,p,n,
Xi es una propiedad de la mezcla y no simplemente una propiedad del componente i; es decir, Xi depende, en general de la temperatura, presión y composición de la mezcla, = Xi(T,p, n¿). Las propiedades molares parciales son propiedades intensivas de la mezcla.
A la vista de la ecuación (9.7), la ecución (9.6) se puede escribir en la forma:
k
X = ^2 ni^i	(9-8)
i
Esta ecuación muestra que la propiedad X puede expresarse como una suma ponderada de las propiedades molares parciales x¡.
Eligiendo que la propiedad extensiva en (9.8) sea el volumen, la energía interna, la entalpia y entropía respectivamente, se tendrá:
k	k	k	k
V —	U =	H —	S =	(9.9)
t	i	i '	i
donde ñ¿, ü¿, hi y representan el volumen, la energía interna, la entalpia y la entropía molar parcial. Expresiones análogas pueden escribirse para la función de Gibbs, G, y la función de Helmholtz, A.
Las propiedades molares parciales pueden evaluarse de varias formas. En primer lugar, si
( AXS
la propiedad X puede medirse, x, puede obtenerse extrapolando el gráfico que da
An¡
frente a An;. esto es,
T,p,n,
4
Sisteméis multicomponentes. Mezcla no reactiva de gases
x; =
dX
drii
T,p,nj
= i- ¥■
Ani-»0 A
T,p,rij
Si se conoce una expresión para X en función de sus variables independientes, X{ puede evaluarse por diferenciación. La derivación puede ser analítica si la función viene expresada analíticamente o numérica si la función está dada en forma tabular.
Un procedimiento gráfico de fácil aplicación para evaluar las propiedades molares parciales, cuando se dispone de datos experimentales, es el método-dé las intersecciones. Este método puede aplicarse para la evaluación de cualquier propieddad molar parcial. A título de ejemplo se puede considerar la determinación del volumen molar parcial en el caso de una disolución formada por dos componentes A y B.
La curva experimental que muestra el volumen molar de la disolución en función de la fracción molar del componente B, para una temperatura y presión determinadas, puede ser como la representada en la figura 9.1. En esta curva se representa en ordenadas el volumen molar de la mezcla, v = V/n, y en abscisas la fracción molar del componente B. Como puede verse en la gráfica, el punto de intersección de la curva con el eje en A, representa el volumen molar correspondiente al componente puro A en las condiciones (p, T) de la mezcla, ya que en ese punto xB
Figura 9.1
es igual a cero. Lo mismo se puede decir con la intersección con el eje B, respecto a ese componente.
De acuerdo con (9.9), el volumen de la mezcvla vendrá dado por:
V = nAvA +nBvB
en la que vA y vB son los volúmenes molares parciales de A y B respectivamente.
También se puede dar el volumen de la mezcla en función del volumen molar medio de la misma, representado en la figura 9.1, mediante la expresión:
V = v(nA +nB)
Teniendo en cuenta esta última expresión y la definición de volumen molar parcial, se puede obtener como valor del volumen molar parcial para el componente A, por ejemplo, la expresión:
OV
Va dnt
= v + (nA +nB)
dv
dnt
T,p,n,
" T,PlnB
A fin de poder utilizar la gráfica que se ha mencionado, se tendrá que referir la expresión anterior a la fracción molar del componente B, para lo que se realizan las transformaciones siguientes:
dV
Va dnt
= v+(nA + nB)
dv
T,p,n
dxt
dx.
T,p,n.
dnÁ
T,p,n.
Sistemas multicomponentes. Mezcla no reactiva de gases
5
Téngase en cuenta que aunque nB se mantiene constante, xB también depende de nA. Para calcular dxB/dnA |x,p,nB, se parte de la definición de xB:
nc
n, + nF
por lo que:
dxB _	nB
dnA (nA + nB)2
Sustituyendo en vA, se obtiene:

dV
dn.
= V — X-í
dv
T,p,nE

..*\
T,p,nB J
Teniendo en cuenta la figura 9.1 y esta expresión, puede verse con facilidad que vA vendrá dada por la intersección de la tangente en el punto considerado (xB,v) con el eje de ordenadas en A. Para el otro componente se puede obtener una expresión análoga.
Se debe tener en cuenta, como ya se ha indicado y en la gráfica se ve con claridad, que para valores determinados de temperatura y presión, vA y vB dependen de xB y no son iguales a los correspondientes valores molares de A o B puros, representados en la figura por vA y vB respectivamente y que sólo son función de la temperatura y presión.
Vamos a concluir el presente análisis evaluando el cambio en el volumen de una mezcla de componentes puros que están a la misma presión y temperatura, resultado para el que se da una aplicación más adelante. El volumen total de los componentes puros antes de la mezcla es:
I
k
Vcom.puro — ^ ' TliV{
<=1
donde v¡ es el volumen específico molar del componente puro i. El volumen de la mezcla es:
k
Vmezcla = ^ ^ i=l
donde es el volumen molar parcial del componente i en la mezcla. El cambio de volumen debido a la mezcla es:
o
A14
V - V
* m.p.z Y c
comp.puro
k	k
- Y^TliVi Í=l	i=l
k
AVme, = £><(* - *0	(9.10)
-L	¿=i
Resultados análogos pueden obtenerse para otras propiedades extensivas, por ejemplo:
6
Sistemas multicomponentes. Mezcla no reactiva de gases
k
mezcla. — ^ ' Tljjüi ~ U¿) i=l
k
&Hmezcla = ^	~ h{)	(9.11)
1=1 k
ASmezcla — ^ ^ ^i(^t	^t)
t=l
En las ecuaciones (9.11),	/i¿ y s,- representan la energía, entalpia y entropía molar del
componente puro i. Los símbolos ñ¿, y s, representan las respectivas propiedades molares parciales.






Potenciales termodinámicos para sistemas multicomponentes
---------------------------------------------------------

Como ya se ha visto cualquier potencial termodinámico proporciona una descripción completa del estado termodinámico de un sistema. En principio, todas las propiedades de interés pueden determinarse a partir de ese potencial mediante un tratamiento matemático adecuado.
Ya se vio en el tema anterior que la energía interna de un sistema multicomponente puede ser considerada como potencial termodinámico si se expresa en función de la entropía y el volumen del sistema así como del número de moles de cada componente; esto es:
u	■_
U = t/(5,E,n¿)
Diferenciando esta función obtenemos:
dU =
3U_
dS
V,n
is+dv
S,n	i=1	*
drii
(9.12)
sy,n,
Esta diferencial nos expresa la variación de la energía interna del sistema cuando varía la entropía, el volumen y el número de moles de cada componente. El subíndice n en los dos primeros términos indica que todas las n permanecen fijas durante la diferenciación. Como esto implica composición fija, se sigue que:
L dU			du
ds	V,n	y	-p=dv
dU
(9.13) , recibe el nom-
E1 tercer término del segundo miembro de la ecuación (9.7),	.
v ' dniJs’v’n>‘
bre de potencial químico y se lo denota con el símbolo gj. Este potencial químico es una propiedad intensiva al igual que la presión y la temperatura. Contabiliza la variación de la e-nergía interna de un sistema multicomponente debida a la variación de la cantidad de sustancia de cada uno de los componentes si se deja variar la cantidad de materia del mismo componente considerado y se mantienen constantes las propiedades termodinámicas que definen el sistema, es decir, la entropía, el volumen y el número de moles de los restantes componentes.
Sistemas multicomponentes. Mezcla no reactiva de gases
7
Así, pues, la ecuación (9.12) podemos escribirla en la forma:
k
dU = TdS - pdV + y^jijdnj
(9.14)
«=i
La función U es una homogénea de grado uno en S, V y ya que
U (otS, aV, arii) = aU(S,V,m)
y basándonos en el teorema de Euler de funciones homogéneas obtenemos:
dU U = ——
ds
V,n
S+dJL
+ dv
v+^Z
S,n i=i Un'
Ui
(9.15)
S,V,nj
y teniendo en cuenta las relaciones (9.13) podemos poner:
) —
U = TS - pV +
A esta última ecuación se la conoce como ecuación de Euler de la energía Si diferenciamos (9.16) obtenemos:
(9.16)
dU = TdS - pdV +	+
¿=i
SdT -Vdp+ ^2 nidpi
¿=i
y comparándola con (9.14) obtenemos la relación
k
^2nídpi = —SdT -\-Vdp
:=1
(9.17)
ue se conoce como ecuación de Gibbs-Duhem. Esta ecuación nos da las restricciones existentes ntre las posibles variaciones de las variables intensivas T, p, y
funciones de la forma A(T, V, n¡), H(S,p,n¡) y G(T,p, n¿) también sirven como potenciales termodinámicos para sistemas multicomponentes.
Estas funciones se obtienen aplicando la transformación de Legendre a U, de manera que las ecuaciones de Euler del potencial de Helmholtz, la entalpia y del potencial de Gibbs resultan:
—jj»2*
A = U - TS H = U+pV : G = U -TS + pV
-pV + ^2 Tiní i= 1 k	(9.18.a)
TS + 2>ni ¿=i k	(9.18.6)
52^ni i=i	(9.18.c)
8
Sistemas multicomponentes. Mezcla no reactiva de gases
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





Fugacidad y coeficiente de fugacidad
------------------------------------

Hemos visto que la energía libre de Gibbs, y por tanto el potencial químico p desempeñan un papel muy importante en el estudio de los sistemas multicomponentes. Otra magnitud, relacionada con la anterior, y que también conviene tenerla en cuenta en este estudio es la denominada fugacidad.
La definiremos a partir de la consideración de sistemas monocomponentes y posteriormente ampliaremos esta definición a sistemas multicomponentes.
9.3.1	Sistemas monocomponentes
Vamos a comenzar por el caso más sencillo de un sistema que consta de un solo componente. En este caso, la ecuación (9.18.c) se reduce a:_.
"X.......
o lo que es lo mismo:
(28)
= h-Ts
Esto es, para un componente puro el potencial químico es igual a la función de Gibbs por mol. Con esto, la ecuación
/V
escrita en base molar queda en la forma:
Sistemas multicomponentes. Mezcla no reactiva de gases
11
dp
dp
- v
(9.29)
Para el caso particular de un gas ideal, pv = RUT y la ecuacción (9.29) toma la forma:
dp^ = RuTd(\n p)
(9.30)
donde con (*) se indica gas ideal. Integrando a temperatura constante la ùltima ecuación se
obtiene:
\
V;
jp* = RuT\np + C(T)	(9.31)
donde C(T) es una función de integración. Como la presión puede tomar valores comprendidos entre cero e infinito, el término ln p de esta expresión y, por lo tanto el potencial químico, tiene f un intervalo de valores entre —oo y +oo. La ecuación (9.31) muestra también que el potencial químico puede determinarse a falta de un parámetro dependiente de la temperatura.
Para un gas real (en general para una sustancia compresible simple), y a fin de mantener el formalismo matemático utilizado para los gases ideales, definimos p mediante la expresión:
dpj = RUT -j-= RuTd(ln /)
La integracióñ'dé esta ecuación proporciona:
én la qpé / es la fugacidad
(9.32)
p - RUT ln / + C(T) j
(9.33)
j|Comparando las ecuaciones (9.33) y (9.31), se ve que la fugacidad juega, en el caso de gases
Ísales, el mismo papel que la presión en el caso de un gas ideal. La fugacidad tiene la mismas imensiones que la presión.

Sustituyendo (9.32) en (9.29) se tiene:
RUT
din f
dp

(9.34)
La integración de (9.34), manteniendo constante la temperatura, nos determina la fugacidad con sólo una constante indeterminada. Sin embargo, como el comportamiento de gas ideal se da cuando la presión tiende a cero, el término constante puede determinarse exigiendo que la fugacidad de un componente puro sea igual a la presión en el h'mite p -> 0. Esto es:
lim -p-*o p
(9.35)
Las ecuaciones (9.34) y (9.35) determinan, pues, completamente la función fugacidad.
12
Sistemas multicomponentes. Mezcla no reactiva de gases
9.3.2 Evaluación de la fugacidad para gases a partir de datos p, v, T
Consideraremos ahora cómo puede evaluarse la fugacidad partir de la correspondiente
ecuación térmica de estado. Si a la ecuación (9.34) le restamos RUT
din p
dp
RUT
se ob-
tiene:
din—
RUT-
dp
= v —
RUT
Al cocienteI—/se le conoce como coeficiente de fugacidad y se le denota con el símbolo v
\P¡	------------------------
(o <f>). de modo que la ecuación anterior puede escribirse en la forma-
RuT
din v
dp
= v —
RUT
T	P —J '
Integrando desde p —>• 0 hasta la presión considerada a T constante (para p —* 0 v = 1), se obtiene:

‘"r‘ Lfe - ;)dp 6)
Esta ecuación nos permite obtener v y por lo tanto / una vez conocida la relación p — y (p(v,T). ¡ Si lo que queremos es utilizar el modelo de estados correspondientes con : = R^T' |
t r '/íiVrl /li /»«íi'/y	r\/M* nr\ 1 ^ non ^ ei /vn nntnrmr	--------
multiplicando y dividiendo por p la ecuación anterior
> ;n
„ ln v = í (z — l)d(ln p)
Jo
/V
P
Si esta ecuación la expresamos en términos de la presión reducida, Pr = —, nos queda:
Pe
rPR
In V = / (z - l)d(ln pR) Jo

(9.36)
Dado que el factor de compresibilidad z depende de la temperatura reducida Tr y de la
presión reducida pR, se tiene que el segundo miembro de (9.36) va a depender sólo de esas
jropiedades. Así pues, ln v o ln — es sólo función de esas dos propiedades reducidas. Haciendo
P
uso de la ecuación de estado generalizada que da z en función de Tr y pR, ln— puede evaluarse
P
fácilmente con un ordenador. Disponiendo del diagrama de u generalizado puede utilizarse para el cálculo de esta magnitud empleando como variables de entrada pR y Tr.
Para ilustrar el uso de esa representación gráfica, consideremos dos estados del CCI2F2 a la misma temperatura de 420 K. En el estado inicial la presión es de 2 MPa y en el estado v final de 4 MPa. El cambio en el potencial químico entre estos dos estados puede determinarse haciendo uso de la ecuación (9.33):
Sistemas multicomponentes. Mezcla no reactiva de gases
13
M2 - Pl = RuTlny-Ji
= RuTln
h P2 Pi P2 Pi h.
Haciendo uso de los valores críticos de la temperatura y presión del CCI2F2 (Tc = 385 K, pc = 41,2 bar):
estado 1 estado 2
/
Pri — 0,5 PR2 = 0,99
Tri = 1,09 Tr\ = 1,09
f/p = 0.89
f !p — o, 77
Los valores de — se han obtenido del gráfico generalizado de fugacidad. Así pues P2 ~
P
- 1915 kJ-kmol 1.
Para un componente puro el potencial químico es igual a la función de Gibbs por mol, p = g = h — Ts. Como la temperatura es la misma en los estados 1 y 2, el cambio en el potencial j químico puede expresarse como P2 — pi = /12 — h\ — T(s2 — -Si). Haciendo uso de los datos tabulares para el CCI2F2, obtenemos el valor de 1927,6 kJ-kmol-1 que es un valor muy próximo al calculado con el diagrama generalizado del coeficiente de fugacidad.
9.3.3 Evaluación de la fugacidad cuando el sistema se presenta como líquido o sólido
Ya hemos visto un procedimiento para la evaluación de la fugacidad de un sistema cuyo estado de agregación es el de gas. La importancia de la fugacidad en el estudio de disoluciones es de tal naturaleza que se hace imprescindible disponer de métodos que nos permitan calcularla en el caso de que el sistema se presente como líquido o sólido.
Para ello recurramos a la ecuación (9.32!) y consideremos un pequeño cambio a temperatura constante.
Si aplicamos esta expresión para calcular el cambio de p a T constante cuando el sistema pasa de la fase I (supongamos gas) a la fase II (líquido), coexistiendo ambas fases en equilibrio, integrando (9.32):

PlL.
H = RUT ln ^
^— h
Pero cuando se produce el paso de una fase a otra en equilibrio, ya vimos que se cumple
l que pn = pi, por lo que
U-D

RUT ln 4^ = 0
fi
fu = X
>>
) / Por lo tanto la fugacidad de un líquido en condiciones de saturación es igual a la fugacidad /del vapor en las mismas condiciones y ésta ya la sabemos calcular.
Consideremos ahora el caso de un/líquido comprimido./ Haciendo aplicación de la ecuación (9.34) se tendrá:
14
Sistemas multicomponentes. Mezcla no reactiva de gases
¿Hn//
dp
nj
R¿r
Teniendo esto en cuenta imaginemos un sistema que evoluciona isotérmicamente desde una presión muy baja, p*, hasta la presión p pasando por un valor intermedio correspondiente a la presión de saturación a esa temperatura, psat.
i Despejando de la expresión anterior d(ln /) e integrando entre p* y p (recuérdese que para tp~ —► 0, p* = /* y para el valor p corresponde el valor //) se obtendrá:
U't)
i»ít= fJ^+f ^p
p- ]r.
Para evitar problemas de falta de continuidad en el límite cuando p* ambos miembros de la ecuación la expresión:
0, restemos a
OJ ln
Psat _ r’al i
p*	Jp*	p
dp
con lo que se obtendrá la ecuación:
ln — = Í (j%~^]dP+ í ~Prdp Psat Jpm \RuT Pj Jp9at Ru _________________'
Esta ecuación puede aplicarse directamente.
En el caso déláilidos.ol procedimiento a seguir es completamente análogo.
Como aplicación vamos a determinar la fugacidad del agua líquida a 200 °C y 50 bars.
De las tablas de propiedades termodinámicas del agua obtenemos, para 200 °C y las pre-

especifican, los siguientes valores:
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
, para el	0,08314 agua es	bar-m3/kg-K.
,-i
Tomando como valor de (v/RT — l/p) la media, -5,833T0 3, de la última expresión obtenemos para la primera integral el valor:
f (
) dp = -5,833 • 10~3 • 15,54 = -9,14-10
RUT p
-2
Sistemas multicomponentes. Mezcla no reactiva de gases
15
Para la segunda integral
-^=dp = 5,283 • 10-4(50 - 15,54) = 0,0182
Rr/l
Por lo que obtendríamos para la fugacidad del agua en las condiciones dadas:
esto es:
ln
j±_
Psat
-0,073
= 15,54 • e-0,073 = 14,44bar
Por otro lado, si consideramos como fugacidad del líquido la correspondiente al vapor saturado a la temperatura del líquido y utilizamos para su determinación el diagrama de fugacidad generalizado, obtenemos:
15,54
220,9
0,0703 Tr
473
647,3
0,731
v = 0,96 =
/
15,54
/ = 14,92 bar
Vemos que el valor de la fugacidad del líquido saturado difiere en menos de un 4% del valor obtenido para el líquido comprimido, por lo que es frecuente utilizar como valor de la fugacidad del líquido comprimido el correspondiente al vapor saturado a la temperatura del líquido comprimido.
9.3.4	Sistemas multicomponentes
La fugacidad del componente i en una mezcla puede definirse por un procedimiento en todo análogo al seguido para el de un componente puro. La fugacidad /¿ para el componente i se introduce con:
/pi = RuT\nfi + C{T)
(9.37)
que es pareja a la (9.33). El par de ecuaciones que, en este caso de sistema multicomponente, nos permiten evaluar son:
RUT-
ln /«• - / ¡s ~VÍ dP T,n	(9.38.a)
lim = 1 P—0 Xip	(9.38.b)
E1 símbolo /^representa la fugacidad del componente i en la mezcla y debe distinguirse claramente en lo que sigue de /T)el cual representa Ja fugacidad del componente puro i a la misma presión y temperatura.
/i
Sistemas multicomponentes. Mezcla no reactiva de gases
16 y
í/¡7^
Refiriéndonos a la ecuación (9.38.b), hay que destacar que en el límite de gas, ideal, la fugacidad /¿.fio se exige que sea igual a la presión, como en el caso de un componente puro, sino que es igual a la cantidad xív. /Para ver que ésta es la cantidad límite apropiada, consideremos un sistema que consiste en una mezcla de gases que ocupa un volumen V a una presión p y temperatura T. Si toda la mezcla se comporta como un gas ideal, podemos escribir:
P =
nRT
~V~
siendo n es el número total de moles de la mezcla. Ya que un gas ideal puede considerarse como compuesto de moléculas que ejercen, unas sobre otras, fuerzas despreciables y cuyo volumen (el de las moléculas) es despreciable frente al volumen total, podemos pensar que cada componente i se comporta como un gas ideal que estuviese él solo a la temperatura T ocupando todo el volumen V. Así, la presión ejercida por cada componente i no sería la de la mezcla p, sino la presión dada por:
n{RT Vi = —
siendo n¿ el número de moles del componente i. Dividiendo estas dos últimas expresiones se obtiene:
de donde despejando
Pi = Xip	(9.39)
Sumando en ambos miembros de (9.39) sobre todos los componentes obtenemos:
^p¡ =	= pj>
i=i
¿=i
i=i
w o, como la suma de las fracciones molares es igual a la unidad,
4
(9.40)
Dicho en palabras, la ecuación (9.40) establece que la suma de las presiones es igual a la presión de la mezcla. De este hecho surge la denominación de presión parcial para p¿/ Con esto vemos que la ecuación (9.38.b) exige que la fugacidad del componente i se aproxíme a la presión parcial del componente i cuando la presión p tiende a cero.
Vamos a considerar a continuación, cómo puede expresarse la fugacidad de un componente i en una mezcla en función de cantidades evaluables. Para un componente puro i, la ecuación (9.34) da:
Sistemas mult¡componentes. Mezcla no reactiva de gases
17
RT
d(ln /,)
dp	= Vi T
(9.41)
donde V{ es el volumen específico molar de la sustancia pura i. Restando (9.41) de (9.38.a),
(9.42)
din (ft/fi)
dp	= Vi - Vi T,n
Integrando desde p* (que es una presión lo suficientemente baja como para considerar el comportamiento de gas ideal) a p, manteniendo constante la temperatura y la composición de
la mezcla,
	RT ln	(/)]	v rP = / (Vi- Vi)dp j
	tendrá:		p* Jp’ 1
En el límite p* —► 0, se 1 i
jU/RT	ln (i)
Como , cuando limp-_^o /« -		p*	y fi-+ xiP*7~'\
J

Ir
Así pues, podemos escribir:
RT ln ^ j'j - ln x,J = J (v¡ - v{)dp
.


(9.43)
en donde /¿ es la fugacidad del componente i en la mezcla, de composición, presión y temperatura dadas, y /¿ es la fugacidad del componente puro a la misma presión y temperatura. La ecuación
(9.43)	expresa la relación entre /¿ y /, en función de la diferencia entre y que es una cantidad mensurable.








La disolución ideal
-------------------

La tarea de evaluar las fugacidades de los componentes en una mezcla se simplifica con-
.Jsiderablemente cuando la mezcla puede modelizarse como una mezcla o disolución ideal. Una disolución ideal es una mezcla en la que:

(9.44)
La ecuación (9.44), conocida comoíjregla de Lewis-Randall|f establece que la fugacidad de cada componente en una disolución es igual al producto de su fracción molar por la fugacidad
18
Sistemas multicomponentes. Mezcla no reactiva de gases
¡ del componente puro a la misma presión, temperatura y estado de agregación (gas, líquido o I sólido) que la mezcla. Como consecuencia de la definición de disolución ideal, introduciendo
(9.44)	en (9.42), el primer miembro se anula dando	= 0 ó
(9.45)
Así, pues, el volumen molar parcial de cada componente en una disolución ideal es igual al volumen específico molar del correspondiente componente puro a la misma presión y temperatura. Cuando introducimos (9.45) en (9.10) podemos concluir que no hay cambio de volumen al mezclar los componentes puros para formar la disolución ideal.
Se puede mostrar, también, que la energía interna molar parcial de cada componente en una disolución ideal es igual a la energía interna molar del correspondiente componente puro a la misma presión y temperatura. Un resultado análogo se obtiene para la entalpia. En símbolos:
Ui = U{, hi = h{	(9.46)
Con estas expresiones se puede concluir, a partir de la ecuación (9.11), que no hay cambio en la energía interna o en la entalpia al mezclar los componentes puros para formar una disolución ideal. [Sin embargo, es de esperar un incremento en la entropía como resultado de la mezcla ^adiabática espontánea de los diferentes componentes puros ya que tal proceso es irreversible:¿a ' separación de la mezcla en sus componentes puros nunca puede suceder espontáneamente. El cambio de entropía en una mezcla adiabática se tratará más detenidamente para el caso especial de mezcla de gases ideales.
Con la ecuación (9.45), el volumen de una disolución ideal es:
V =	^ V¿ (disolución ideal)	(9-47)
¿=i	¿=l	»=i
donde V,- es el volumen que cada componente puro ocuparía a la temperatura y presión de la mezcla . Con (9.46), la energía interna y la entalpia de una disolución son:
k	k
U =	y H = ^2nihi (disolución ideal)	(9.48)
U i=1	¿=1
donde y h{ denotan, respectivamente, la energía interna molar y la entalpia molar del componente puro i a la temperatura y presión de la mezcla. Muchas mezclas gaseosas a presiones bajas o moderadas se puden modelizar adecuadamente por la regla de Lewis-Randall. Las mezclas de gases ideales, de las que nos ocuparemos más adelante, son una clase importante y especial de tales mezclas. Algunas disoluciones Líquidas también se pueden modelizar con la regla de Lewis-Randall.
La regla de Lewis-Randall exige que la fugacidad del componente i de la mezcla se evalúe en términos de la fugacidad del componente puro i a la misma temperatura y presión que la
mezcla y en mismo estado de agregación. Por ejemplo, si la mezcla es gas a T y p, entonces /¿
j
Sistemas multicomponentes. Mezcla no reactiva de gases
19
debe determinarse para el componente puro como gas a T y p. No obstante a algunas presiones [ y temperaturas de interés un componente gaseoso de una mezcla puede ser, como sustancia pura, Kquido o sólido. Un ejemplo es una mezcla de aire-vapor de agua a 20 °C y 1 bar. A esta temperatura y presión, el agua existe no como vapor sino como líquido, pudiéndose definir, no obstante, un estado hipotético en el que tengamos vapor de agua a 1 bar y 20 °C..
9.4.1	Potencial químico para disoluciones ideales
El análisis de sistemas multicomponentes lo vamos a terminar con las expresiones que permitan evaluar el potencial químico para disoluciones ideales, que utilizaremos más tarde.
Para ello se considera un estado de referencia, al que se denomina estado estándar, en el i que el componente i de un sistema multicomponente es una sustancia pura a la temperatura T . y a la presión p° (por lo general 100 kPa). La diferencia en el potencial químico de i entre un estado especificado del sistema multicomponente y el estado de referencia se obtiene a partir de la ecuación que nos da el potencial químico del componente i en la mezcla (9.37):
Pi = RT\n fi + C(T)j ^
de donde:
gi - g° = RT ln
T
SL
(9.49)
donde el supraíndice ° indica valores de la propiedad en el estado estándar. El cociente de fugacidades que aparece en el término logarítmico se conoce como actividad, a, del componente i en la mezcla; esto es:
(9.50)
Para aplicaciones posteriores es sufuciente con considerar el(taso de mezclas gaseosas. /Para mezclas gaseosas p° es 1 bar, de modo que g° y f° son, respectivamente el potencial químico y la fugacidad del componente puro a la temperatura T y 1 bar.
Teniendo en cuenta (9.50), la ecuación (9.49) podemos escribirla en la forma:
gi = g° + RT ln a,
(9.51)
siendo g° = g° la función de Gibbs por mol del componente puro evaluada a la temperatura T y a la presión de 1 bar.
Para una disolución ideal, se aplica la regla de Lewis-Randall y la actividad es
(9.52)
donde ¡fjjes la fugacidad del componente pufü~3Tla temperatura T y presión p. Llevando (9.52) a (9.51) se obtiene:
20
Sistemas multicomponentes. Mezcla no reactiva de gases
ó
Pi = Pi + RT ln + RT ln X{
J t
Pi — P¡ + RT ln
fi] (f\p_
PJ \fi)p°
+ RT ln xí
(9.53)
En principio los cocientes entre las fugaciades y presiones subrayadas en (9.53) pueden evaluarse a partir de la ecuación (9.36) o del diagrama generalizado del coeficiente de fugacidad desarrollado a partir de la misma ecuación. Si el componente i se comporta como gas ideal tanto
fi f9
a T y p como a T y p°, — = — = 1 y la ecuación (9.53) se reduce a:
p p°
Pi — Pi + RT ln----b .RTln X{
(9.54)








Exergía en mezclas: exergía química; exergía total
--------------------------------------------------

Al estudiar los potenciales termodinámicos vimos que la variación del potencial de Gibbs, en un proceso es reversible, era el trabajo mínimo, distinto del pdV, que había que dar para realizar el proceso; esto es:
swmin
,nopdV — dGT,P	(9.55)
Vemos, pues, que la variación del potencial de Gibbs para un sistema cerrado que experimente una evolución a T y p constantes, siendo éstas las del medio ambiente, representa el trabajo útil, reversible mínimo que hay que realizar sobre el sistema para llevarlo desde un estado inicial de equilibrio a otro final también de equilibrio.
Ahora ya estamos en condiciones de poder calcular el trabajo máximo que puede obtenerse de un sistema multicomponente cuando, isóbara e isotérmicamente, de forma reversible se le deja alcanzar el equilibrio en composición con el medio ambiente.
Para poder aplicar la ecuación (9.55) debemos tener un sistema cerrado. Sea éste el formado
por el sistema multicomponente y por los alrededores de éste último (es decir, la zona del medio
ambiente que se ve afectada por el intercambio de materia con el sistema multicomponente).
k
Consideremos que en el sistema hay moles con un potencial químico para cada componente
i=i
k
p\ y en el medio ambiente hay ^n0¡ moles cuyo potencial químico es /i01- para cada componente
¿=i
antes mencionado. Este sistema compuesto es un sistema cerrado ya que no hay flujo de materia a través de su frontera. Suponemos que el sistema multicomponente ya ha alcanzado el equilibrio termo-mecánico con el ambiente de modo que su estado termodinámico viene definido por la temperatura y presión del medio ambiente y por la composición del sistema (T0,	p0,	x¡).
Sistemas multicomponentes. Mezcla no reactiva de gases
21
Si ahora dejamos que este sistema compuesto, manteniendo la temperatura y presión constantes, alcance el equilibrio en composición de forma reversible, esto es, se deja que alcance el estado muerto, el trabajo mínimo reversible vendrá dado por la variación del potencial de Gibbs del sistema según hemos visto anteriormente [ecuación (9.55)]. Así pues, teniendo en cuenta (9.18.c):
de modo que:
k
W^úíti.reu = ^	noi)Poi ~
i=l
k
W^útil,rev = ^ ^ rii(poi —
t=l
Y de acuerdo con la definición de exergía dada en el tema 5 se podrá poner:
k
EXq — inútil,rev — ^ ^ ^i'(Mí Moi)	(9.56)
¿=1
La expresión dada en (9.56) es lo que se conoce como exergía química.
Si el sistema está, en general, a una temperatura T / T„ y a una presión p ^ p0 y tiene una composición x¿ xoi, el trabajo máximo que puede obtenerse cuando se le permite alcanzar el equilibrio con el medio ambiente de modo que no haya producción de entropía durante el proceso, podemos ponerlo como suma de dos contribuciones:
a) el trabajo máximo que puede obtenerse manteniendo constante la composición y permitiendo que, sin generación de entropía, el sistema alcance el equilibrio térmico y mecánico con el medio ambiente (exergía termomecánica)
Extm = *)„,= [(£ - E0) + p0(V - v0) - To(S - So)]Bi	(9.57)
b) la exergía química dada por la expresión (9.56) pudiéndose expresar la exegía total, Ex, como:
Ex — $)n. + Exq
(9.58)










