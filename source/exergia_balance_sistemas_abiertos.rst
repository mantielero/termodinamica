Balance de exergía para sistemas de flujo
=========================================

Para obtener el balance de exergía en sistemas dé flujo, (esto es, sistemas en los que la masa tiene una velocidad media macroscópica) se procede de manera análoga a lo hecho con los sistemas cerrados. Según vimos en el tema 4 [(4.8.a) y (4.24.b)], las ecuaciones del primer y segundo principio para sistemas abiertos en régimen no estacionario son:

* Primer principio:

  .. math::

     \sum_{i=0}^n \dot{Q}_i+\dot{W}+\sum_e\left( h+\frac{\nu^2}{2} + gz \right) \dot{m} -  \sum_s \left( h+\frac{\nu^2}{2} + gz \right) \dot{m} = \frac{d}{dt}\left( U+E_m\right)_{VC} \\


* Segundo principio:

  .. math::

     \dot{\sigma}_t = \left. \frac{dS}{dt} \right|_{VC} - \sum_{i=0}^{n} \frac{\dot{Q}}{T_i} - \sum_e s \dot{m} + \sum_s s \dot{m} \geq 0

Eliminando :math:`\dot{Q}_o` entre las ecuaciones (5.15) y 1(5.16), y como :math:`h_t = h +\frac{\nu^2}{2} + gz`, despejando :math:`\dot{W}` se obtiene:

.. math::

   \dot{W} = \frac{d}{dt} \left( U+E_m-T_oS\right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t - T_os) \dot{m} -\sum_{i=1}^n \dot{Q}_i \left( 1 - \frac{T_o}{T_i} \right) + T_o \dot{\sigma}_t

A :math:`h_t — T_os` se le suele llamar disponibilidad de flujo(*)


Al igual que en el caso de sistemas cerrados, en lo que estamos interesados es en la potencia mecánica útil, tanto real como reversible, que hay que consumir en una evolución de un sistema de flujo no estacionario. Procediendo igual que en el apartado anterior, podremos escribir:

.. math::

   \dot{W}_{útil,real} = \frac{d}{dt} \left(U + E_m + p_oV - T_oS \right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t-T_os)\dot{m}  - \sum_{i=1}^n \dot{Q}_i\left( 1- \frac{T_o}{T_i}\right) +T_o\dot{\sigma}_t


habiendo desdoblado el término de la potencia mecánica en dos: potencia útil, :math:`\dot{W}_{útil}`, y potencia debida al hecho de que las paredes del volumen de control es deformable, :math:`-p_o\frac{dV_{VC}}{dt}` que representa la potencia mecánica intercambiada con la atmósfera.

La potencia útil reversible será: 

.. math::

   \dot{W}_{útil,rev} = \frac{d}{dt} \left(U + E_m + p_oV - T_oS\right)_{VC} + \sum_s (h_t-T_os)\dot{m} - \sum_e (h_t-T_os)\dot{m}  - \sum_{i=1}^n \dot{Q}_i\left( 1- \frac{T_o}{T_i}\right) 

y la ecuación (5.18) se puede escribir:

.. math::

   \dot{W}_{útil,real} = \dot{W}_{útil,rev}+T_o\dot{\sigma}_t

(*) En algunos textos a :math:`(e + p_ov — T_os)` le llaman disponibilidad. La disponibilidad de flujo se relaciona con ésta mediante la relación :math:`a_f = a + v(p — p_o)`.


Si desde las condiciones del medio ambiente (estado muerto restringido: :math:`p_o`, :math:`T_o`, :math:`v = 0` y :math:`z = 0`) mediante un proceso en régimen estacionario (:math:`\frac{d}{dt}=0`) y teniendo como única fuente térmica la atmósfera :math:`\left(\sum_{i=1}^n \dot{Q}_i \left( 1- \frac{T_o}{T_i} \right)=0\right)` se quiere obtener una corriente con una velocidad, v, temperatura, T, presión, p y altura z determinadas, la potencia mecánica reversible útil i necesaria es :math:`m\psi` siendo :math:`\psi`  la exergía de una corriente, que se obtiene a partir de (5.19) con todas las condiciones especificadas. Esto es:

.. math::

   \psi = h -h_o + \frac{\nu^2}{2}+gz- T_o(s-s_o)

Teniendo en cuenta (5.8.a), (5.18) v (5.21) el balance de exergía para sistemas de flujo en régimen no estacionario puede expresarse en la forma:	

.. math::

   \left. \frac{d}{dt} \right|_{VC} + \sum_s \psi \dot{m} - \sum_e \psi \dot{m} - \dot{W}_{útil,real} - \sum_{i=1} \dot{Q}_i \left( 1-\frac{T_o}{T_i} \right) + T_o\dot{\sigma}_t = 0

Ecuación, que de manera análoga al caso de sistemas cerrados (5.10.b), nos indica que la variación de exergía de un recinto abierto proviene de la exergía neta que se introduce al recinto: a) con la masa a través de las fronteras permeables, (:math:`\sum_s \psi \dot{m} - \sum_e \psi \dot{m}`), b) con el trabajo, :math:`\dot{W}_{útil,real}` y con el calor, :math:`\left(\sum_{i=1}^n \dot{Q}_i \left( 1- \frac{T_o}{T_i} \right)\right)`,  a través de las fronteras impermeables restando la exergía que se destruye por irreversibilidades existentes en el proceso, irreversibilidades tanto internas al sistema como las que hay entre el sistema y el medio ambiente.

Si el proceso de flujo es estacionario, la ecuación (5.22) se reduce a:

.. math::

   \sum_s \psi \dot{m} - \sum_e \psi \dot{m} - \dot{W}_{útil,real}- \sum_{i=1} \dot{Q}_i \left( 1-\frac{T_o}{T_i} \right) + T_o\dot{\sigma}_t = 0


La expresión (5.23) puede ponerse de una forma genérica:

.. math::

   \left. \dot{e_x} \right)_{obtenida} + \left. \dot{e_x}\right)_{perdida} = \left. \dot{e}\right)_{suministrada} 


donde :math:`e_x` señala exergía. El valor de cada término habrá que asignarlo en cada caso concreto. A modo de ejemplo, supongamos la actuación de una turbina funcionando en régimen estacionario a la que se suministran :math:`\dot{m} kg\cdot s^{-1}` de vapor en condiciones (:math:`p_1`, :math:`T_1`), que sen de la misma en condiciones (:math:`p_2`, :math:`T_2`) y proporciona una potencia :math:`\dot{W}`. En este caso particular:

.. math::

   \dot{e}_x\bracevert_{obtenida} &\text{ es la potencia } \dot{W} \\
   \dot{e}_x\bracevert_{suministrada} &\text{ es } \dot{m}\psi_e


y de (5.24) se sigue que:

.. math::

   \dot{e}_x\bracevert_{perdida} = \dot{m} \psi_e - \dot{W} = \dot{m} \psi_s + T_o \dot{\sigma}_t 

¿Cómo se modificarían estas expresiones si el flujo músico de salida se utilizase en un dispositivo para calefacción saliendo del dispositivo en condiciones del ambiente (p0, T0)1.

De manera análoga, la expresión (5.lO.b) y la (5.22) una vez integrada, pueden expresarse, también, en la forma:

.. math::

   \dot{e}_x\bracevert_{obtenida} + \dot{e}_x\bracevert_{perdida} = \dot{e}_x\bracevert_{suministrada}
