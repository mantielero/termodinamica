Rendimiento exergético
======================

De manera análoga a como se ha hecho en el análisis energético de los sistemas donde se ha definido un rendimiento térmico o energético, en el que se relaciona la energía real consumida con la correspondiente al funcionamiento ideal, podemos definir un rendimiento exergético en la forma:

.. math::

   \epsilon = \frac{\left. e_x\right_{obtenida}}{\left. e_x\right_{suministrada}}
   
Teniendo en cuenta la relación (5.24), el rendimiento exergético se puede escribir:

.. math::

   \epsilon = 1- \frac{\left. e_x\right_{perdida}}{\left. e_x\right_{suministrada}}

En algunos casos, como se verá en el apartado siguiente, los rendimientos térmico y exergético están relacionados entre sí. Qué diferencia haya entre estos rendimientos se puede ver con el siguiente ejemplo. Supongamos un sistema cerrado que recibe una potencia térmica :math:`\dot{Q}_s` de una fuente térmica a temperatura :math:`T_s` y cede una potencia térmica :math:`\dot{Q}_u` a una temperatura de utilización :math:`T_u`. Además hay una pérdida de energía térmica hacia el medio ambiente, :math:`\dot{Q}_p`, a través de una parte de la frontera que está a :math:`T_p`.

Suponiendo un funcionamiento en régimen estacionario y que al sistema cerrado no se le transfiere energía en forma de trabajo, los balances energético y exergético (ec 5.lO.b) para el sistema son:

.. math::

   & \dot{Q}_s = \dot{Q}_u + \dot{Q}_p \\
   & \dot{Q}_u \left( 1- \frac{T_o}{T_u}\right) - \dot{Q}_s \left( 1- \frac{T_o}{T_s}\right) + \dot{Q}_p \left( 1- \frac{T_o}{T_p}\right) + T_o \sigma = 0
   

El balance energético dice simplemente que de la potencia térmica que recibe el sistema parte se utiliza y el resto se pierde.

Un rendimiento energético puede definirse en función de la potencia térmica utilizada y la suministrada, esto es:

.. math::

   \eta = \frac{\dot{Q}_u}{\dot{Q}_s}

En principio este rendimiento puede aumentarse poniendo más aislante de modo que se reduzcan las pérdidas. En el Emite de :math:`\dot{Q}_p = 0`, el rendimiento será la unidad.

Si comparamos el balance de exergía del proceso con (5.24), se ve que se suministra exergía el calor, :math:`\dot{Q}_s \left( 1 - \frac{T_o}{T_s}\right)`, y que hay una exergía que se obtiene con la potencia térmica utilizada,
:math:`\dot{Q}_u \left( 1 - \frac{T_o}{T_u}\right)` de modo que el rendimiento exergético será

.. math::

   \epsilon &= \frac{ \dot{Q}_u \left( 1 - \frac{T_o}{T_u}\right) }{ \dot{Q}_s \left( 1 - \frac{T_o}{T_s}\right) } \\
            &= \eta \frac{\left( 1 - \frac{T_o}{T_u}\right) }{ \left( 1 - \frac{T_o}{T_s}\right) }

De esta expresión se ve que es importante no sólo la energía térmica utilizada, en definitiva valores altos de g que en el límite sería la unidad, sino también la temperatura de utilización de esa energía. Así por ejemplo, suponiendo que seamos capaces de utilizar prácticamente casi toda la energía suministrada (:math:`\eta \sim 1`), si la temperatura a la que se utiliza esa energía :math:`T_u`, es próxima a la temperatura ambiente, el rendimiento exergético tiende a cero. Dicho de otra forma, cuanto más baja sea la temperatura de utilización del calor generado a alta temperatura, aunque se utilice íntegramente, peor es la utilización de esa energía. Desde el punto de vista de óptima utilización de la energía interna, con los valores más altos posibles de :math:`\eta`, una temperatura de utilización de la energía térmica lo más próxima a la temperatura de la fuente de la que se obtiene la energía térmica.

Por ejemplo, supongamos que para la calefacción de un gran edificio se ha de quemar un combustible. Mejor que generar vapor y comunicarlo a los radiadores, sería generar vapor y utilizarlo para producir energía eléctrica y sacar parte del vapor en una etapa intermedia para calefacción (este proceso se llama cogeneración).
