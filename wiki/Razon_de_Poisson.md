### Motivación
Cuando un cuerpo es sometido a una fuerza de tensión o compresión axial, no solo se alarga o acorta, sino que también su ancho se acorta o se alarga respectivamente. 

### Historia
A principios del sigo XIX el científico Francés S.D.Poisson se dio cuenta que dentro del rango elástico la razón de las deformaciones explicadas anteriormente son una constante única para cada material, a la cual llamó **razón de Poisson**

### Fórmula
$$\nu = - \frac{\epsilon_{lateral}}{\epsilon_{longitudinal}}$$

El signo negativo de la ecuación se debe a que el cambio en la deformación del cuerpo es inverso con respecto a los ejes. Es decir si un cuerpo se alarga axialmente, se acorta su ancho y vice versa. 


### Ejemplo
Una barra de acero A-36 tiene las dimensiones mostradas en la imagen. Si se le aplica una fuerza axial de P = 80 kN sobre la barra, determine el cambio en su longitud y el cambio en las dimensiones de su sección transversal después de aplicar la carga. El material se comporta elásticamente (condición necesaria para que se cumpla la constante de Poisson). 

![Ilustración](./images/Ejemplo_razon_poisson.png)

El esfuerzo normal en la barra es: 

$$  \sigma_{z} = \frac{P}{A} = \frac{80(10^3)N}{(0,1 m)(0,05 m)} = 16*(10^6) Pa $$

El  acero A-36 tiene $E = 200 $ GPa, por lo que la carga en la dirección z es:
$$ \epsilon{z} = \frac{\sigma_{z}}{E} = \frac{16(10^6)Pa}{(200)(10^9) Pa} = 80*(10^-6) mm/mm $$

Por lo tanto, el alargamiento axial de la barra es: 
$$\delta_{z} = \epsilon_{z}*L_{z} = 80(10^-6) 1,5m= 120 \mu m $$

Para el acero, la razón de Poisson es 0,32, por lo que con ella podemos calcular las deformaciones laterales en ambas direcciones: 

$$\epsilon_{x} = \epsilon_{y} = - \nu * \epsilon_{z} = -0,32[80(10^-6)] = -25,6 \mu m/m $$

Por lo tanto, los cambios en las dimensiones de la sección transversal son: 
$$\delta_{x} = \epsilon_{x}*L_{x} = -25,6(10^-6) 0,1m= -2,56 \mu m $$
$$\delta_{y} = \epsilon_{y}*L_{y} = -[25,6(10^-6)]0,05m = -2,56 \mu m $$


### Bibliografía 
Mecánica de Materiales (octava edición). R.C. Hibbeler


