Cálculo de las propiedades termodinámicas de una sustancia
----------------------------------------------------------

Una vez estudiado el comportamiento de las sustancias puras en las transiciones de fase, puede efectuarse el cálculo completo de las propiedades de las sustancias, que como se sabe, resultan necesarias a la hora de aplicar los principios de la termodinámica a los sistemas en estudio.

Así, pueden obtenerse expresiones anak'ticas que reflejen el comportamiento observado. También pueden construirse tablas de propiedades con un espaciado conveniente entre puntos, muy útiles en los cálculos técnicos. Además, puede reflejarse de forma completa el comportamiento p - v — T de las sustancias en diagramas tridimensionales en coordenadas rectangulares, donde cada estado de equilibrio corresponde a un punto de la superficie p — v — T. En las proyecciones de estos diagramas, es decir, en los diagramas planos correspondientes, pueden representarse también las diversas isotermas, isoentálpicas, isócoras...en las distintas regiones, de forma que las propiedades térmicas y energéticas pueden leerse conjuntamente.

.. note::

   (3)Callen K.B.Thermodyna.mics and an Introduction to Thermostatistics 2nd ed. Wiley & Sons New York 1985 Cap. 10.
   (4)Kirillin V.A., nota a pie de página 2.

En este apartado, se habla del cálculo de las propiedades termodinámicas de las sustancias mediante la obtención de expresiones analíticas adecuadas y en el siguiente apartado, se estudian con algún detalle las tablas y los diagramas de uso frecuente.

Hasta no hace mucho tiempo la evaluación de las propiedades termodinámicas de los gases se basaba en la formulación de ecuaciones (p, v, T), que eran obtenidas mediante el análisis estadístico de datos experimentales (p, :math:`\rho`, T o p, v, T).

Algunas de estas ecuaciones, como la de Benedict-Webb-Rubin, utilizaban hasta 30 coeficientes característicos de las sustancias, que se obtenían por ajuste de los datos experimentales adecuados.

Una vez conocida con suficiente precisión la ecuación térmica de estado, mediante las correspondientes ecuaciones generalizadas, podían evaluarse las propiedades termodinámicas requeridas.

En la actualidad se sustituye la ecuación térmica de estado por un potencial termodinámico, que es el que hay que modelar con gran precisión y, a partir de él, se determinan por derivación las propiedades que interesen.

La ecuación elegida para modelar es la función específica" de Helmholtz, deducida en física estadística por el método de Ursell-Mayer, modificada para tener en cuenta el comportamiento del gas a densidades elevadas y muy bajas.

La función o se expresa utilizando las variables :math:`\rho` y *T* en vez de *v* y *T*

.. math::

   a(\rho, T) = a_{\text{teórica}}(\rho, T) + a_{\text{residual}}(\rho, T) + a_{\text{ideal}}(T)
   
en la que :math:`a_{\text{residual}}` corresponde al comportamiento a densidades elevadas y :math:`a_{\text{ideal}}` corresponde al comportamiento a densidades muy bajas, en esta zona los otros términos se anulan y este sólo es función de *T*.

El cálculo de *a* se hace a partir de los valores correspondientes de *u* y *s*. Es decir, a partir de la integración de las ecuaciones generalizadas para *u* y *s*, determinamos :math:`u(T, v)` y :math:`s(T, v)`, con lo que:

.. math::

   a = t(T,v) - T_o s(T,v)

Recuérdese que:

.. math::

  du = c_v dT + \left[ T\left( \frac{\partial p}{\partial T}\right)_v -p\right]dv\\
  ds = \frac{c_V dT }{T} + \left( \frac{\partial p}{\partial T}\right)_v dv


Cuando se trata de agua líquida-vapor de agua y de otros sistemas multifase, se ha seguido un procedimiento ligeramente distinto. En estos casos es mejor tener un modelo para determinar la forma general de la expresión analítica y entonces aplicar las técnicas de cuadrados mínimos a esta ecuación. Un buen ejemplo de esto puede ser la utilización de ecuaciones del tipo de la de Clausius-Clapeyron para representar la relación entre la presión y temperatura de saturación.
