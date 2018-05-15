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

