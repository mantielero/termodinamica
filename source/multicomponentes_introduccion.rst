Introducción
============

Sistemas Multicomponentes: mezclas no reactivas de gases
--------------------------------------------------------

Hasta ahora hemos fijado nuestra atención en sistemas homogéneos monocomponentes. En este tema se considerarán algunos aspectos generales de las propiedades de un sistema con dos o más componentes. El interés primordial está en el caso de mezcla de gases, pero el método que se desarrolla también se aplica a disoluciones. Cuando lo que se considera objeto de estudio son líquidos o sólidos, se usa el término de disolución en vez de mezcla. La discusión presente se limita a mezclas no reactivas o disoluciones en una sola fase. El efecto de reacciones químicas y el equilibrio entre diferentes fases se consideran más adelante.

Para describir los sistemas multicomponentes se debe incluir la composición en nuestras relaciones térmodinámicas. Esto lleva a la definición y desarrollo de conceptos, algunos ya mencionados en temas anteriores y otros nuevos, que incluyen las propiedades molares parciales, el potencial químico y la fugacidad. Posteriormente se considerará el caso particular de la mezcla ideal de gases suponiendo que éstos tienen un comportamiento primero ideal y luego se extiende el estudio a gases reales. Para estas mezclas ideales de gases se dan las relaciones p, v, T y la variación de las propiedades termodinámicas energía interna, entalpia y entropía.

Descripción de la mezcla
------------------------

La determinación del estado termodinámico de una mezcla precisa del conocimiento de la composición y del valor de dos propiedades intensivas independientes tales como la temperatura y la presión. El objetivo de esta sección es el considerar los modos de describir la composición de una mezcla.

Consideremos un sistema cerrado que consiste en una mezcla gaseosa de dos o mas componentes. La composición de la mezcla puede describirse dando la masa o el número de moles de cada componente presente. La masa, número de moles y la masa molar del componente i están relacionados por:

.. math::

   n_i = \frac{m_i}{M_i}
   

siendo:

.. math::

   \left.
   \begin{array}
   n_i: \text{cantidad de sustancia} \\
   m_i: \text{la masa} \\
   M_i: \text{la masa molar}
   \end{array}
   \right}
   \text{del componente i}


Cuando se expresa en *kg*, :math:`n_i` viene expresada en *kmol*.

La masa total de la mezcla, *m*, es la suma de las masas de sus componentes:

.. math::

   m = m_1 + m_2 + ... m_k = \sum_{i=1}^k m_i

La cantidad relativa de cada componente presente en la mezcla queda especificada por la fracción másica :math:`x_{mi}`:

.. math::

   x_{mi} = \frac{m_i}{m}

Cuando una mezcla se describe con las fracciones másicas de los componentes se habla de análisis gravimétrico.

Dividiendo cada miembro de (9.2) por *m*, y haciendo uso de (9.3):

.. math::

   l = \sum_{i=1}^k x_{mi}

esto es, la suma de todas las fracciones másicas de los componentes de una mezcla es igual a la unidad.

El número de moles en la mezcla, *n*, es la suma del número de moles de cada uno de los componentes:

.. math::

   n = n_1 + n_2 + ... n_k = \sum_{i=1}^k n_i
   
Las fracciones molares- de cada componente es:

.. math::

   x_i = \frac{n_i}{n}

de modo que :math:`l = \sum_{i=1}^k x_i`.


Cuando una mezcla se especifica por las fracciones molares de los componentes se habla de análisis molar.

La masa molar media (aparente) de una mezcla, *M*, se define como:

.. math::

   \left.
   \begin{array}
   M=  \frac{m}{n}= \frac{\sum_{i=1}^k m_i}{n} \\
   m_i = n_i M_i
   \end{array}
   \right}
   \rightarrow
   M = \frac{\sum_{i=1}^k n_i M_i}{n} = \sum_{i=1}^k x_i M_i


esto es, la masa molar de la mezcla es una media ponderada de las masa molares de cada componente.
