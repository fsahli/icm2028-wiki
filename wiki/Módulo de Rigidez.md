El módulo de rigidez G o también llamado Módulo de Elasticidad es una constante para muchos materiales, el cual nos habla  del cambio que experimenta un material elástico cuando se le aplican esfuerzos cortantes. 

### ¿Cómo se obtiene?
Es la razón entre el esfuerzo cortante y la deformación constante en el rango del comportamiento plástico. 
Una forma de verlo más gráficamente es, la primera pendiente (comportamiento plástico) en el gráfico de esfuerzo-deformación cortante. 

![Gráfico](./images/grafico_esfuerzo_deformacion_cortante.png)

Por ende su fórmula sería: (recordar que es sólo para rangos de comportamiento plástico) 

$$ \tau = \frac{G}{\gamma} $$

Es una propiedad que se obtuvo experimentalmente a priori y que tiene las mismas unidades de medida que el módulo de tensión E (psi o ksi en unidades inglesas y Pascales en unidades S.I.) . Esto se debe a que $\gamma$ se mide en radianes, el cual es una medida adimensional. 


Los módulos de elasticidad en tensión y en cortante no son independientes entre sí, sino que están relacionados a través de la razón de Poisson, mediante la siguiente ecuación: 

$$ G = \frac{E}{2(1+\nu)}$$

### Ejemplo: 

Encuentre el módulo de rigidez del acero: 

Suponemos una razón de Poisson de 0,3 y un módulo de elasticidad de 200Gpa. 

Tenemos la fórmula: 
$$ G = \frac{E}{2(1+\nu)}$$
Reemplazamos los valores conocidos. 
$$ G = \frac{200*(20^9)}{2(1+0,3)}$$
G \thickapprox 77 GPa

### Recursos
* Mecánica de Materiales (octava edición). R.C. Hibbeler
* Mecánica de Materiales (séptima edición). James M. Gere & Barry J. Goodno

### Autor
Daniel Lyon
