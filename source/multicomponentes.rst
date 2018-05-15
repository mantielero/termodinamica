Sistemas Multicomponentes. Mezclas No Reactivas de Gases
========================================================


Antonio Sánchez Sánchez

Pablo de Assas Marinez de Morentin

.. toctree::
   :maxdepth: 1
   :caption: Contenido:

   multicomponentes_disolucion_ideal
   multicomponentes_exergia
   multicomponentes_gases_ideales
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




























