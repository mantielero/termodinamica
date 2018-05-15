Aplicación a procesos cíclicos
==============================

Este análisis exergético de los ciclos, aunque lo hacemos con dispositivos poco complicados, esto es, sistemas cerrados que trabajan en un número entero de ciclos, nos va servir como una introducción para el análisis posterior de procesos más complicados y detallados que puedan hacerse con ciclos de potencia y de refrigeración. El estudio lo haremos, separadamente, para motores térmicos y para bombas térmicas y máquinas refrigerantes. El ciclo trabajará entre dos fuentes térmicas. Una será siempre el ambiente y la otra estará, en cada caso, a una temperatura especificada.

Motores térmicos
^^^^^^^^^^^^^^^^

Al tratarse un sistema cerrado cíclico, definido en la sección 3.2, la ecuación (5.10.a) se reduce a:

.. math::

   W_{util,real} = -Q_a \left( 1 - \frac{T_o}{T_a}\right) + T_o \sigma = 0

donde :math:`Q_a` es el calor que el motor toma de la fuente de alta que está a una temperatura :math:`T_a`. La otra, como ya se ha dicho, es el ambiente. En los motores el trabajo útil real es trabajo extraído, no suministrado, de modo que si ponemos  :math:`W_{util,real} = - W_{motor}` en la expresión anterior, reordenándola queda en la forma:

.. math::

   W_{motor}  - Q_a \left( 1 - \frac{T_o}{T_a}\right) + T_o \sigma = 0 

Si se compara (5.27) con (5.24) se ve que se suministra exergía al motor con el calor que éste toma de la fuente de alta; esto es, aunque de forma no muy ortodoxa, se podría hablar del contenido de trabajo disponible en el calor transferido.

El rendimiento exergético de un motor térmico, según la expresión (5.25) es:

.. math::

   \epsilon &= 1- \frac{T_o\sigma}{Q_a \left( 1- \frac{T_o}{T_a}\right)} \\
            &= \frac{W_{motor}}{Q_a \left( 1- \frac{T_o}{T_a}\right)} 

Como :math:`\frac{W_{motor}}{Q_a}` es el rendimiento energético del motor térmico, (:math:`\eta`), se podrá poner para el rendimiento exergético de un motor:

.. math::

   \epsilon = \frac{\eta}{ \left( 1- \frac{T_o}{T_a}\right) }

esto es, el rendimiento exergético es el cociente entre el rendimiento térmico del motor y el rendimiento de un motor equivalente de Carnot que trabajase entre la temperatura de la fuente de alta y la temperatura del medio ambiente.

Bombas térmicas y máquinas refrigerantes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En el caso de las bombas térmlcas, al ser éstas dispositivos que ceden una cantidad determinada de calor (:math:`Q_a` será negativo) a una fuente a una temperatura :math:`T_a` consumiendo un trabajo :math:`W_{util,real}`, que es el trabajo consumido en el compresor de la máquina (:math:`W`), la ecuación (5.10.a) quedará:

.. math::

   W = Q_a\left( 1- \frac{T_o}{T_a}\right) + T_o \sigma = 0


de la que se ve que se obtiene la exergía :math:`Q_a\left( 1- \frac{T_o}{T_a}\right)` que es la que se suministra al sistema que se ve que se está calentando.

El rendimiento exergético en este caso de bombas térmicas es:

.. math::

   \epsilon &= \frac{Q_a\left( 1- \frac{T_o}{T_a}\right)}{W} \\
            &= \frac{COP_{bomba}}{COP_{eq.Carnot}}
            

siendo :math:`COP_{eq.Carnot} = \frac{T_a}{T_a-T_o}` el coeficiente de actuación de una bomba térmica funcionando según un ciclo de Carnot entré la temperatura del recinto a calentar (:math:`T_a`) y la temperatura del medio ambiente.

Si de lo que se trata es de máquinas refrigerantes el calor involucrado es el que hay que extraer (:math:`Q_b`) del recinto a refrigerar (fuente a una temperatura :math:`T_b`). Este calor es positivo para la máquina. En cuanto al trabajo útil real, también en estos dispositivos es el trabajo consumido en el compresor de manera que (5.10.a), en este caso, será:

.. math::

   W=-Q_b \left( 1- \frac{T_o}{T_b}\right) + T_o \sigma

Como :math:`T_b<T_o`,  la ecuación anterior se puede escribir en la forma:

.. math::

   Q_b \left( \frac{T_o}{T_b} -1 \right) -W + T_o \sigma = 0

De esta ecuación se ve claramente que de una máquina refrigerante se obtiene exergía, :math:`Q_b\left( \frac{T_o}{T_b} -1 \right)` ya que :math:`T_b<T_o`, que es suministrada al sistema que se refrigera. Esta es la razón -^6 /
por la que de un sistema cerrado a tamperatura inferior a la del medio ambiente se puede obtener trabajo, o lo que es lo mismo, este sistema "frío" tiene una exergía positiva ya que se le ha dado esa exergía mientras se enfriaba.

El rendimiento exergético de un refrigerador será, pues,

.. math::

   \epsilon &= \frac{Q_b \left( \frac{T_o}{T_b} -1 \right) }{W} \\
            &= \frac{COP_{ref}}{COP_{eq.Carnot}}

siendo :math:`COP_{eq.Carnot}= \frac{T_b}{T_o-T_b}` el coeficiente de actuación de una máquina refrigerante de
Carnot qué trabajase entre las temperaturas del recinto a refrigerar (:math:`T_b`) y la temperatura ambiente.

