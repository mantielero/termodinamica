La disolución ideal
===================

La tarea de evaluar las fugacidades de los componentes en una mezcla se simplifica considerablemente cuando la mezcla puede modelizarse como una mezcla o disolución ideal. Una disolución ideal es una mezcla en la que:

.. math::

   \overline{f_i} = x_i f_i

La ecuación (9.44), conocida comoíjregla de Lewis-Randall|f establece que la fugacidad de cada componente en una disolución es igual al producto de su fracción molar por la fugacidad del componente puro a la misma presión, temperatura y estado de agregación (gas, líquido o I sólido) que la mezcla. Como consecuencia de la definición de disolución ideal, introduciendo (9.44)	en (9.42), el primer miembro se anula dando	:math:`\overline{v_i}-v_i= 0` ó

.. math::

   \overline{v_i} = v_i
   
Así, pues, el volumen molar parcial de cada componente en una disolución ideal es igual al volumen específico molar del correspondiente componente puro a la misma presión y temperatura. Cuando introducimos (9.45) en (9.10) podemos concluir que no hay cambio de volumen al mezclar los componentes puros para formar la disolución ideal.

Se puede mostrar, también, que la energía interna molar parcial de cada componente en una disolución ideal es igual a la energía interna molar del correspondiente componente puro a la misma presión y temperatura. Un resultado análogo se obtiene para la entalpia. En símbolos:

.. math::

   \overline{v_i} = v_i \\
   \overline{h_i} = h_i


Con estas expresiones se puede concluir, a partir de la ecuación (9.11), que no hay cambio en la energía interna o en la entalpia al mezclar los componentes puros para formar una disolución ideal. [Sin embargo, es de esperar un incremento en la entropía como resultado de la mezcla _adiabática espontánea_ de los diferentes componentes puros ya que tal proceso es irreversible: La separación de la mezcla en sus componentes puros nunca puede suceder espontáneamente. El cambio de entropía en una mezcla adiabática se tratará más detenidamente para el caso especial de mezcla de gases ideales.

Con la ecuación (9.45), el volumen de una disolución ideal es:

.. math::

   V = \sum_{i=1}^k n_i \overline{v_i} = \sum_{i=1}^k n_i v_i = \sum_{i=1}^k V_i \hspace{2cm} \text{(disolución ideal)}

donde *V*, es el volumen que cada componente puro ocuparía a la temperatura y presión de la mezcla . Con (9.46), la energía interna y la entalpia de una disolución son:

.. math::

   U = \sum_{i=1}^k n_i u_i \\
   H = \sum_{i=1}^k n_i h_i  \hspace{2cm} \text{(disolución ideal)}

donde :math:`ui` y :math:`h_i` denotan, respectivamente, la energía interna molar y la entalpia molar del componente puro i a la temperatura y presión de la mezcla. Muchas mezclas gaseosas a presiones bajas o moderadas se puden modelizar adecuadamente por la regla de Lewis-Randall. Las mezclas de gases ideales, de las que nos ocuparemos más adelante, son una clase importante y especial de tales mezclas. Algunas disoluciones Líquidas también se pueden modelizar con la regla de Lewis-Randall.

La regla de Lewis-Randall exige que la fugacidad del componente *i* de la mezcla se evalúe en términos de la fugacidad del componente puro *i* a la misma temperatura y presión que la
mezcla y en mismo estado de agregación. Por ejemplo, si la mezcla es gas a *T* y *p*, entonces 
:math:`\overline{f_i}` debe determinarse para el componente puro como gas a *T* y *p*. No obstante a algunas presiones y temperaturas de interés un componente gaseoso de una mezcla puede ser, como sustancia pura, Kquido o sólido. Un ejemplo es una mezcla de aire-vapor de agua a 20°C y 1bar. A esta temperatura y presión, el agua existe no como vapor sino como líquido, pudiéndose definir, no obstante, un estado hipotético en el que tengamos vapor de agua a 1bar y 20°C.

Potencial químico para disoluciones ideales
-------------------------------------------

El análisis de sistemas multicomponentes lo vamos a terminar con las expresiones que permitan evaluar el potencial químico para disoluciones ideales, que utilizaremos más tarde.

Para ello se considera un estado de referencia, al que se denomina *estado estándar*, en el *i* que el componente i de un sistema multicomponente es una sustancia pura a la temperatura *T* y a la presión :math:`p^o` (por lo general 100kPa). La diferencia en el potencial químico de *i* entre un estado especificado del sistema multicomponente y el estado de referencia se obtiene a partir de la ecuación que nos da el potencial químico del componente *i* en la mezcla (9.37):

.. math::

   \mu_i = RT\ln \overline{f_i}+C(T)

de donde:

.. math::

      \mu_i - \mu_i^o = RT\ln \frac{\overline{f_i}}{f_i^o}

donde el supraíndice ° indica valores de la propiedad en el estado estándar. El cociente de fugacidades que aparece en el término logarítmico se conoce como actividad, :math:`a_i`, del componente *i* en la mezcla; esto es:

.. math::

   a_i = \frac{\overline{f_i}}{f_i^o}


Para aplicaciones posteriores es suficiente con considerar el caso de mezclas gaseosas. Para mezclas gaseosas :math:`p^o` es 1bar, de modo que :math:`g^o` y :math:`f^o` son, respectivamente el potencial químico y la fugacidad del componente puro a la temperatura *T* y 1bar.

Teniendo en cuenta (9.50), la ecuación (9.49) podemos escribirla en la forma:

.. math::

      \mu_i = \mu_i^o + RT\ln a_i
      
siendo :math:`\mu_i^o = f_i^o` la función de Gibbs por mol del componente puro evaluada a la temperatura *T* y a la presión de 1bar.

Para una disolución ideal, se aplica la regla de Lewis-Randall y la actividad es

.. math::

   a_i = \frac{x_i f_i}{f_i^o}

donde :math:`f_i` es la fugacidad del componente puro a la temperatura *T* y presión *p*. Llevando (9.52) a (9.51) se obtiene:

.. math::

   \mu_i = \mu_i^o + RT\ln \frac{f_i}{f_i^o}  + RT \ln x_i

ó

.. math::

   \mu_i = \mu_i^o + RT \ln \left[ \left( \frac{f_i}{p} \right) \left( \frac{p^o}{f_i^o} \frac{p}{p^o} \right) \right] + RT \ln x_i

En principio los cocientes entre las fugaciades y presiones subrayadas en (9.53) pueden evaluarse a partir de la ecuación (9.36) o del diagrama generalizado del coeficiente de fugacidad desarrollado a partir de la misma ecuación. Si el componente *i* se comporta como gas ideal tanto a *T* y *p* como a *T* y :math:`p^o`, :math:`\frac{f_i}{p} = \frac{f_i^o}{p^o}=1` y la ecuación (9.53) se reduce a:

.. math::

   \mu_i = \mu_i^o + RT \ln \frac{p}{p^o} + RT \ln x_i
   
