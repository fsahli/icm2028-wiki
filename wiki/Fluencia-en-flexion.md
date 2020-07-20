### Fluencia de flexión

### Descripción

En la siguiente sección analizaremos como es el comportamiento de un sólido sometido a flexión, luego de superar el límite de fluencia.

-Las ecuaciones constitutivas para un sólido en flexión son:

- $$\epsilon_{x}=\frac{-y}{\rho}

- $$\epsilon_{y}=\epsilon_{z}=-\nu*\epsilon_{x}$$

Donde, y: posición en el eje vertical, $$\rho$$: Radio de curvatura, $$\nu$$: Razón de Poisson del material.

-Luego, podemos definir el momento con la siguiente expresión:

$$M=\frac{E}{\rho}*I_{zz}$$

Donde, $$I_{zz}$$ corresponde al momento de inercia del sólido con respecto al eje z.

#### Fluencia en flexión pura.

- Criterio de tresca

$$\sigma_{x}$$=Y

- Criterio de Von Mises

$$\sigma_{x}$$=Y

-Donde Y corresponde un valor de tensión obtenido experimentalmente para cada material

Como sabemos, el la tensión en el eje x es proporcional a la distancia del lugar en el que queremos calcular $$\sigma_{x}, con el eje neutro que pasa por el centroide la viga.
Por lo tanto, una viga sometida a flexión entrará en fluencia primero en el lugar más alejado del eje neutro. Por lo tanto, para encontrar una función para el momento es necesario
considerar la zona elástica y la zona en fluencia. De esta manera, obtendremos dos ecuaciones de $$\sigma_{x}$$ que podremos multiplicarlas por el brazo e integrarlas para obtener 
una función general para el momento.

- Zona elástica:

$$M=-\frac{\sigma_{x}*I_{zz}}{y}

- Zona donde empieza la fluencia:

$$\sigma_{x}=-\frac{y*Y}{y_{Y}}

Donde: y es la posición en la que queremos calcular el momento, $$y_{Y}$$ es la coordenada del eje vertical donde comienza la fluencia y Y es la tensión calculada experimentalmente 
para la cuál el material entra en fluencia.

- Con estás dos ecuaciones podemos integrar y encontrar una ecuación general para el momento.

$$\int_{0}^{y_{max} \! \sigma_{x}*y  \,dA$$

Si desarrollamos por partes esta integral, es decir, sumamos las integrales de la zona en fluencia con la zona elástica con los respectivos $$\sigma_{x}$$, obtenemos la siguiente expresión.

$$M=\frac{3}{2}*M_{Y}*(1-\frac{1}{3}*(\frac{y_{Y}{\frac{h}{2}})^2$$

Luego podemos definir que: $$\frac{y_{Y}}{\frac{h}{2}}=\frac{\rho}{\rho_{Y}}

Donde: $$\rho$$ es el radio de curvatura y $$\rho_{Y}$$ es el radio de curvatura donde comienza la flexión.

-Con esto conclimos que la ecuación de momento es:

$$M=\frac{3}{2}*M_{Y}*(1-\frac{1}{3}*(\frac{\rho}{\rho_(Y)})^2$$

Como podemos observar, esta función tiende a $$\frac{3}{2}*M_{Y}$$ cuando $$\frac{1}{\rho} tiende a infinito.


#### Referencias

-Crandall, An Introduction To The Machanics Of Solids


Autor: Cristian Alguerno












