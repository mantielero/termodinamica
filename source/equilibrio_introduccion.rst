Introducción
------------

En el estudio que hemos de realizar sobre los sistemas termodinámicos es imprescindible disponer de criterios adecuados para definir sus estados de equilibrio y la posibilidad de que estos estados de equilibrio se mantengan, es decir, que sean estables. Por lo tanto deben formularse criterios de equilibrio y estabilidad de sistemas que sean inequívocos y de fácil aplicación. La combinación de los principios primero y segundo, así como los potenciales termodinámicos, de los que hemos hablado, nos permiten formular claramente estos criterios.

Es importante recordar nuestras definiciones de sistema homogéneo y heterogéneo, así como estado de agregación y fase.

Vimos que un sistema se denominaba homogéneo cuando su composición química y propiedades físicas eran iguales en todos sus puntos o variaban de un modo continuo de un punto del sistema a otro. El ejemplo más paradigmático puede ser una columna de aire atmosférico: en esta columna y debido a la acción de la gravedad, habrá un cambio continuo de propiedades físicas y composición química.

Llamamos heterogéneo al sistema integrado por dos o más partes homogéneas distintas. Cada una de estas partes homogéneas se denomina fase. Cada fase está separada de la otra por una superficie de separación (interfase) de modo que al atravesar esta superficie hay un cambio brusco de propiedades físicas o composición química, o de ambas simultáneamente. En general la interfase no es una superficie matemática, sino una capa delgada en la que las propiedades de una fase se transforman rápidamente en las de la otra fase.

Aunque generalmente las fases se relacionan con los tres estados de agregación fundamentales: sólido, líquido y gas, pueden existir fases distintas en un mismo estado de agregación. Así, en el hielo se han descrito hasta siete fases distintas (de las cuales sólo se ha confirmado la existencia de seis, pues no hay evidencia experimental comprobada de la existencia del hielo IV). A veces al sistema homogéneo, o a alguna de las fases, constituido por varias sustancias puras se denomina disolución o mezcla.


Hasta ahora hemos considerado la variación de propiedades termodinámicas suponiendo que la cantidad de sustancia del sistema cerrado se mantenía constante. Al estudiar sistemas de masa constante constituidos por más de una fase también interviene en el cambio de propiedades termodinámicas la variación de la cantidad de sustancia (suele medirse en moles) en cada fase.

Para tener en cuenta la influencia de la variación del número de moles en el valor de una propiedad introducimos la magnitud denominada **potencial químico**, que consideraremos con mayor detenimiento cuando realicemos el estudio de mezclas.

Supongamos que deseamos evaluar la variación de energía interna de un sistema en el que puede variar el número de moles, es decir, consideramos que U es función de n, además de serlo de S y V:

.. math::

   U = U(S,V,n_1,n_2, ...) \\
   dU = \left( \frac{\partial U}{\partial S}	\right)_{V,n_i} dS  +  \left( \frac{\partial U}{\partial V}	\right)_{V,n_i} dV + \sum_i \left( \frac{\partial U}{\partial n_i}	\right)_{S,V,n_j} dn_i ,, j\neq i

donde :math:`n_j` representa todas las especies presentes menos aquella respecto a la que derivamos.

Si realizamos una transformación en la que no variamos la composición ni el número total de moles:

.. math::

   dU = \left( \frac{\partial U}{\partial S}	\right)_{V,n_i} dS + \left( \frac{\partial U}{\partial V}	\right)_{V,n_i} dV

Pero en este caso el sistema se comporta como uno cerrado de composición constante, por lo que, si sólo consideramos trabajo :math:`pdV`:

.. math::

   \left( \frac{\partial U}{\partial S}	\right)_{V,n_i} = T \\
   \left( \frac{\partial U}{\partial v}	\right)_{S,n_i} = -p


Sustituyendo en (8.1), obtenemos:

.. math::

   dU = TdS -pdV + \sum_i \left( \frac{\partial U}{\partial n_i}	\right)_{S,V,n_j} dn_i

que es una expresión general para el cambio de energía interna de un sistema en el que pueden cambiar tanto S y V como las cantidades de sustancia de las distintas especies químicas en la mezcla, si sólo se considera trabajo pdV.

Recordemos que definimos G, H y A como funciones que venían dadas por una determinada agrupación de variables y por lo tanto son aplicables a cualquier tipo de sistema. Consi-deremos la definición de G:

.. math::

   G = U + pV -TS

entonces:


.. math::

   dG = dU + pdV + Vdp - TdS - SdT

y sustituyendo dU se tiene:

.. math::

   dG = TdS-pdV+\sum_i \left( \frac{\partial U}{\partial n_i}	\right)_{S,V,n_j} dn_i + pdV+Vdp-TdS-SdT

de donde:

.. math::

   dG = -SdT+Vdp+\sum_i \left( \frac{\partial U}{\partial n_i}	\right)_{S,V,n_j} dn_i

Pero esta expresión resulta análoga a la que obtendríamos al considerar G función de T, p, :math:`n_1`, :math:`n_2`, ..., :math:`n_c`, es decir:

.. math::


   dG = \left( \frac{\partial G}{\partial T} \right)_{p,n_i} dT + \left( \frac{\partial G}{\partial p}	\right)_{T,n_i} dp + \sum_i \left( \frac{\partial G}{\partial n_i}	\right)_{T,p,n_j} dn_i

Conforme lo hemos definido, (8.7) y (8.8) representan la misma magnitud en función de las mismas variables, por lo que identificando coeficientes homólogos, tendremos:
Í) ~*(t) =v’-(£'
9T J p Ui	V Op ) T,nt	\driiJ S,V,ri] \9tIí / T,p,n3
por lo que (8.7) podríamos expresarla mediante:
dG= -SdT + Vdp+Y	dnt
i VWr.p.n,
(8.9)
(8.10)

A la magnitud que represéntala última igualdad de las (8.9) la denominamos potencial químico y suele representarse por /í¿, de forma que podemos escribir:
dU — TdS — pdV -f y>,dn,
(8.11)
6

Equilibrio de los sistemas termodinámicos. Transiciones de fase
dG = -SdT + Vdp + Yl M»dn¡
(8.12)

De forma análoga encontraríamos:
dH = TdS + Vdp + ^2 trìdui dA — —SdT - pdV + y^pidrij
(8.13)
7/'/
(8.14)
i ^ " /' * ^
/ /ppr&ííy- jAv/di,^- >

Teniendo en cuenta las variables en las que se expresen los potenciales termodinámicos,
el potencial químico vendrá expresado por:
(JjiW
0’
_ (^L\	- (02.}	_ fdH\ = fdA\
/X‘ \dni)s,v,nj wn¡/T,p,nj \dni)s,p,nj \dnt)T,v,nj
(8.15)

En este tema estudiaremos las condiciones de equilibrio y estabilidad de los sistemas termodinámicos, veremos la ecuación de Clausius-Clapeyron aplicable en los cambios de fase y finalmente veremos cómo pueden calcularse, para su tabulación, las distintas propiedades termodinámicas de uso más frecuente.
