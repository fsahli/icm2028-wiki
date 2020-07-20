### Fluencia en torsión

##### Descripción 

En la siguiente sección, se analizará el proceso de fluencia para un sólido sometido a torsión. Para comenzar es importante señalar los supuestos a considerar en el momento
de analizar un cuerpo sometido a torsión, estos son:

1) El eje de longitud no cambia de largo
2) La sección recta permanece recta
3) El diámetro de una sección recta permanece recto y sólo rota

Con estos supuestos podemos obtener en coordenadas cilindricas las siguientes ecuaciones de deformacion:


$$\epsilon_{r}=\epsilon_{\theta}=\epsilon_{z}=0$$

$$\gamma_{r\theta}=\gamma_{zr}=0$$

$$\gamma_{\thetaz}=r*\frac{d\phi}{dz}


Con estas ecuaciones podemos expresar ahora los criterios de fluencia.  

-**Criterio de Von Mises:**

$$\sqrt{(\sigma_{1}-\sigma_{2})^2+(\sigma_{1}-\sigma_{3})^2+(\sigma_{2}-\sigma_{3})^2}=\sqrt{2}*Y$$

-**Criterio de tresca:**

$$\sigma_{1}-\sigma_{3}=Y$$

**Donde:** 

$$\sigma_{1}=\tau_{thetaz}$$

$$\sigma_{2}=-\tau_{\thetaz}$$

$$\sigma_{3}=0

Y: Valor obtenido experimentalmente

##### Inicio de fluencia

En un sólido sometido a torsión, la fluencia empieza primero en las zonas del material donde la tensión es máxima. Es por esto, que existen una zona que aún está en rango elástico 
y otra que está en fluencia. De esta manera, si integramos el valor del esfuerzo de corte por el radio en toda el áres del sólido, podremos obtener una expresión general para el momento. En este caso,
consideraremos un eje macizo, con sección transversal circular de radio R.

-Ecuación zona elástica:

$$\tau=\frac{M*r}{I}

-Ecuación para zona en fluencia

$$\tau_{y}=\frac{M_{Y}*r}{I}

Sea $$r_{Y}$$ el valor del radio donde empieza la fluencia. De esta manera, con las dos expresiones para el valor del esfuerzo de corte, podemos integrar dentro del área para obtener la ecuación de momento.

$$M = \int_{0}^{r_{Y}} \! \tau*r  \,dA + \int_{r_{Y}^{R} \! \tau_{y}*r  \,dA$$

Si desarrollamos esta ecuación llegamos a que:

$$M = \frac{4}{3}*M_{Y}*(1-\frac{\phi_{Y}^3}{4*\phi^3}$$

-**Donde:**

$$\phi_{Y}$$: Ángulo en donde comienza la fluencia

$$\phi$$: Ángulo en el que queremos encontrar el momento.

Si analizamos esta expresión de momento, podemos concluir que cuando el ángulo $$\phi$$ crece, el momento converge a $$\frac{4}{3}$$.

#### Ejemplo

Consideremos un eje macizo de radio $$R=20 mm$$, con $$Y=70 MPa$$, $$L=1m$$, $$G=54$$ obtener la expresión del momento luego de iniciada la fluencia utilizando el criterio de tresca.}

##### Solución
- Primero calculamos el momento de inercia polar (I) de un eje macizo de diametro 40 mm

$$ I=\frac{\pi*D^4}{32}=2.52*10^(-7)

- Del criterio de tresca obtenemos que:

$$\tau_{y}=0.5*Y=35 MPa$$

- Luego con esta expresión obtenemos que:

$$M_(Y)=\frac{\tau_{y}*I}{R}=441 NM

$$\phi_{Y}=\frac{\tau_{y}*L}{G*R}=32.41

-**Por lo tanto, la ecuación de momento en función del ángulo es:**

$$M = \frac{4}{3}*441*(1-\frac{32.41^3}{4*\phi^3}$$


#### Referencias

Crandall, An Introduction To The Machanics Of Solids


Autor: Cristian Alguerno












