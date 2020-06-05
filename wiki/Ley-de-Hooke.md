# Ley de Hooke

La ley de Hooke es una ley física que se cumple en todos aquellos materiales que son deformables. Recibe su nombre en honor a
Robert Hooke, un físico inglés contemporáneo a Isaac Newton que hizo grandes aportes a la arquitectura en su época.

La ley en sí establece que **la fuerza aplicada sobre un resorte es directamente proporcional a la deformación aplicada en él**, 
matemáticamente vista de la siguiente forma:

$$\vec{F} = -k \delta$$

Donde $$k$$ es la constante de elasticidad del resorte medida en $$N/m$$ y $$\delta$$ la deformación del resorte.
Posteriormente esta ley fue generalizada para elementos esbeltos de la siguiente forma:

 - Resortes en serie: se tiene que para una misma fuerza $$\vec{F}$$ aplicada a $$n$$ resortes en serie con igual $$k$$: 
 $$\Delta l\ \propto\ #número\ de\ resortes$$ es decir, al largo total del sistema.
 
 - Resortes en paralelo: se tiene que para una misma fuerza $$\vec{F}$$ aplicada a $$n$$ resortes en paralelo con igual $$k$$:
 $$\Delta l\ \propto\ \frac{1}{#número\ de\ resortes}$$ es decir, inversamente proporcional al área ocupada por los resortes.
 
Luego, para materiales que no fueran resortes se introdujo un nuevo parámetro $$E$$ llamado **módulo de Young** en honor al 
científico inglés Thomas Young que tuvo noción de esto pero la idea fue completamente desarrollada por Leonhard Euler más tarde.
Así, la ley de Hooke se deduce de la forma:

$$\Delta l \propto \frac{\vec{F} l}{A} -> \frac{\vec{F}}{A} = E \frac{\Delta l}{l}$$

Donde claramente se puede apreciar que el valor $$E$$ corresponde a una constante de proporcionalidad para poder establecer la
igualdad.
