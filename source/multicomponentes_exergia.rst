Exergía en mezclas: exergía química; exergía total
==================================================

Al estudiar los potenciales termodinámicos vimos que la variación del potencial de Gibbs, en un proceso es reversible, era el trabajo mínimo, distinto del *pdV*, que había que dar para realizar el proceso; esto es:

.. math::

   \partial W_{\text{min,no }pdV } = dG_{T,p}

Vemos, pues, que la variación del potencial de Gibbs para un sistema cerrado que experimente una evolución a *T* y *p* constantes, siendo éstas las del medio ambiente, representa el trabajo útil, reversible mínimo que hay que realizar sobre el sistema para llevarlo desde un estado inicial de equilibrio a otro final también de equilibrio.

Ahora ya estamos en condiciones de poder calcular el trabajo máximo que puede obtenerse de un sistema multicomponente cuando, isóbara e isotérmicamente, de forma reversible se le deja alcanzar el equilibrio en composición con el medio ambiente.

Para poder aplicar la ecuación (9.55) debemos tener un sistema cerrado. Sea éste el formado
por el sistema multicomponente y por los alrededores de éste último (es decir, la zona del medio
ambiente que se ve afectada por el intercambio de materia con el sistema multicomponente). Consideremos que en el sistema hay :math:`\sum_{i=1}^k n_i` moles con un potencial químico para cada componente :math:`\mu_i'` y en el medio ambiente hay :math:`\sum_{i=1}^k n_{oi}` moles cuyo potencial químico es :math:`\mu_{oi}` para cada componente antes mencionado. Este sistema compuesto es un sistema cerrado ya que no hay flujo de materia a través de su frontera. Suponemos que el sistema multicomponente ya ha alcanzado el equilibrio termo-mecánico con el ambiente de modo que su estado termodinámico viene definido por la temperatura y presión del medio ambiente y por la composición del sistema (:math:`T_o`, :math:`p_o`, :math:`x_i`).

Si ahora dejamos que este sistema compuesto, manteniendo la temperatura y presión constantes, alcance el equilibrio en composición de forma reversible, esto es, se deja que alcance el estado muerto, el trabajo mínimo reversible vendrá dado por la variación del potencial de Gibbs del sistema según hemos visto anteriormente [ecuación (9.55)]. Así pues, teniendo en cuenta (9.18.c):

.. math::

   W_{\text{útil,rev.}} = \sum_{i=1}^k (n_i+n_{oi}) \mu_{oi} \left( \sum_{i=1}^k n_i \mu_i' + \sum_{i=1}^k n_{oi} \mu_{oi}  \right)

de modo que:

.. math::

   W_{\text{útil,rev.}} = \sum_{i=1}^k n_i (\mu_{oi} - \mu_i' )

Y de acuerdo con la definición de exergía dada en el tema 5 se podrá poner:

.. math::

   E_{xq} =  -W_{\text{útil,rev.}} = \sum_{i=1}^k n_i (\mu_i' - \mu_{oi}) 

La expresión dada en (9.56) es lo que se conoce como exergía química.

Si el sistema está, en general, a una temperatura :math:`T \neq T_o` y a una presión :math:`p \neq p_o` y tiene una composición :math:`x_i \neq x_{oi}`, el trabajo máximo que puede obtenerse cuando se le permite alcanzar el equilibrio con el medio ambiente de modo que no haya producción de entropía durante el proceso, podemos ponerlo como suma de dos contribuciones:

a) el trabajo máximo que puede obtenerse manteniendo constante la composición y permitiendo que, sin generación de entropía, el sistema alcance el equilibrio térmico y mecánico con el medio ambiente (exergía termomecánica)

.. math::

   E_{xtm} = \left. \Phi \right)_{n_i} = \left[ (E - E_o) + p_o(V - V_o) - T_o(S - So) \right]_{n_i}

b) la exergía química dada por la expresión (9.56) pudiéndose expresar la exegía total, Ex, como:

.. math::

   E_x =  \left. \Phi \right)_{n_i} + E_{xq}
