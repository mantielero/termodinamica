Magnitudes de remanso
=====================

Definimos las magnitudes de remanso como las magnitudes termodinámicas que se obtendrían decelerando el fluido desde la velocidad :math:`\boldsymbol{\nu}` hasta el reposo en las siguientes condiciones:

a)	estacionariamente
b)	sin fuerzas másicas(*) de viscosidad
c)	adiabáticamente (sin calor)
d)	sin paredes móviles en el volumen de control (sin trabajo)


(*) No se consideran posibles efectos disipativos debido al flujo de materia en las mismas secciones de entrada o salida.

(*) Fuerzas músicas son aquellas proporcionales a la masa como las fuerzas gravitatorias y las fuerzas de inercia dabidas al movimiento del sistema de referencia

Teniendo en cuenta estas condiciones y las ecuaciones (4.8.b) y (4.21), obtenemos:

.. math::

   h_o &= h + \frac{\nu^2}{2} \\
   s_o &= s

donde el subíndice *o* denota magnitud de remenso.

Si la sustancia de trabajo es un *gas perfecto*, como para estas sustancias :math:`h = c_pT`, de la primera de las igualdades de (4.26) se obtiene la relación entre la temperatura de remanso y la temperatura estática; esto es:

.. math::

   T_o = T + \frac{\nu^2}{2c_p}

La segunda de las igualdades se reduce a:

.. math::

   s_o = s \rightarrow c_p ln \frac{T_o}{T} - R \ln \frac{p_o}{p}  = 0 \Rightarrow \frac{p_o}{p} = \left( \frac{T_o}{T} \right)^\frac{\gamma}{\gamma-1}

Si se trata de una *sustancia incompresible* (un líquido por ejemplo), de la segunda de las igualdades (4.26) se obtiene:

.. math::

  \Delta s = c \ln \frac{T_o}{T} = 0 \rightarrow T_o = T

ya que para este modelo de sustancias la variación de entropía sólo es función de la temperatura [ver (3.29)].

Al ser la temperatura de remanso igual a la estática, de (4.26) y de la definición de entalpia, :math:`h = u + pv`, obtenemos:

.. math::

   p_o = p +\frac{1}{2}\rho \nu^2

.. warning:: 

   Hay que señalar que las expresiónes (4.27) a (4.30) sólo son válidas para los modelos de sustancias señalados. Para cualquier otro comportamiento de las sustancias, habrá que resolver las ecuaciones (4.26) junto con la ecuación térmica de estado correspondiente a la sustancia particular.
