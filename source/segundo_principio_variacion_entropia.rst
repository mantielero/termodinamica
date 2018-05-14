Variación de entropía en sustancias incompresibles y en gases perfectos
=======================================================================


Se calcula mediante:

.. math::

   s_2-s_1 = c_v \ln \frac{T_2}{T_1} + R\ln \frac{v_2}{v_1} \text{   } (J\cdot kg^{-1} \cdot K^{-1})
   
Demostración
------------


Para calcular la variación de entropía de una sustancia determinada no hay más que aplicar la ecuación de Gibbs reordenada en la forma:

.. math::

   dS = \frac{dU+pdV}{T}

que referida a la unidad de masa o a la unidad de sustancia se escribe:

.. math::

   ds = \frac{du+pdv}{T}

Para sustancias incompresibles :math:`dv = 0` y :math:`du = cdT` siendo c el calor específico de la sustancia incompresible. Con esto la ecuación (3.24.b) queda:

.. math::

   ds = c\frac{dT}{T} \rightarrow s_2-s_1 = c \ln \frac{T_2}{T_1} \text{   } (J\cdot kg^{-1}\cdot K^{-1})

Para el modelo de gas perfecto:

.. math::

   du = c_v dT \text{  y  } p=R_g\frac{T}{v}

con :math:`c_v` constante. Así pues, la variación de entropía en un gas perfecto se obtendrá sustituyendo en (3.24) las relaciones (3.26) e integrando entre el instante inicial y final obteniendo:

.. math::

   s_2-s_1 = c_v \ln \frac{T_2}{T_1} + R\ln \frac{v_2}{v_1} \text{   } (J\cdot kg^{-1} \cdot K^{-1})

(*) Sí además del trabajo :math:`—pdV` hay otras formas de trabajo cuasi-estático, la ecuación (3.23) se escribirá con más generalidad, en la forma :math:`dU = T dS + \sum_k Y_k dX_k`, siendo :math:`Y_kdX_k` cada uno de los posibles trabajos cuasi-estáticos (ver tema 2).

Se podría actuar de forma análoga para obtener las correspondientes expresiones :math:`S= S(p, T)` y :math:`S=S(p, F)`. Es conveniente que realicen las transformaciones adecuadas a fin de obtener expresiones análogas a la (3.27) en función de las variables :math:`(p, T)` y :math:`(p, F)`.
