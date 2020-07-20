Cuando un eje se somete a un par de torsión se puede generar una fórmula para calcular el ángulo de giro en algún punto del eje. 

### Desarrollo
Tomaremos el par de torsión resultante $T(x)$ , dependiente de x, ya que el par de torsión puede variar a lo largo del eje. 

Producto de T(x) el disco girará produciendo una rotación relativa $d \phi$ entre la sección donde se ejerza el par de torsión y la sección que queramos medir (sección a una distancia x). 

Entonces un elemento de materia ubicado a $\rho$  (arbitrario), experimentará una deformación $\gamma$. 

Estos valores se relacionan de la siguiente manera: 

(I) $$ d \phi = \gamma * \frac{dx}{\rho}$$

La Ley de Hooke nos dice que $\gamma = \frac{\tau}{G}$. Además el esfuerzo cortante se puede expresar en términos del par de torsión aplicado, usando la fórmula de torsión $\tau = T(x) * \frac{\rho}{J(x)} $. 
Sustituyendo todo esto en la fórmula (I) , nos queda que el ángulo de giro para el disco es: 

$$ d\phi = \frac{T(x)}{J(x)G} dx$$

Si integramos a lo largo de la longitud L del eje, obtenemos el ángulo de giro para todo el eje: 

$$ \phi = \int_{0}^{L}  \frac{T(x) dx}{J(x)G}$$


### Par de torsión constante y área de la sección transversal
Para este caso,  como el par de torsión y el momento polar son constantes a lo largo del eje, la ecuación anterior nos queda: 

$$ \phi = \frac{TL}{JG}$$

### Ejercicio
(Ejemplo 5.6 Hibbeler) 
Los dos ejes sólidos de acero mostrados en la figura 1 se acoplan entre sí mediante engranajes dentados. Determine el ángulo de giro del extremo A del eje AB cuando se aplica el par de torsión T = 45 N * m. Considere G = 60 Gea. El eje AB gira libremente en los cojinetes E y F, mientras que el eje DC está fijo en D. Caja eje tiene un diámetro de 20mm. 

![Figura 1](./images/ejercisio_angulo_de_giro_1.png)

En las siguientes figuras se muestran los diagramas de cuerpo libre para cada eje. 
![Figura 2](./images/ejercisio_angulo_de_giro_2.png)

![Figura 3](./images/ejercisio_angulo_de_giro_3.png)

**Par de torsión interno: **Si se suman los momentos a lo largo de la línea central x del eje AB, se obtiene la reacción tangencial entre los engranajes de F = 45 N * m / 0,15m = 300N. Si se suman los momentos respecto a la línea central x del eje DC, se observa que esta fuerza crea un par de torsión de (Td)x = 300 N (0,075 m) = 22,5 N * m sobre el eje DC. 

**Ángulo de giro: ** Para resolver el problema, primero se calcula la rotación del engranaje C debido al par de torsión de 22,5 N * m en el eje DC, de la última figura. Este ángulo de giro es: 

$$ \phi_{C} = \frac{T L_{DC} }{JG} = \frac{(22,5 N * m) (1,5 m)}{(\frac{\pi}{2})(0,01 m)^4[80(10^9) N/m^2]} = 0,0269 rad $$

Como los engranajes en el extremo del eje están endentados, la rotación $\phi_{C}$ del engranaje C ocasiona que el engranaje B gire $\phi_{B}$, (en la segunda figura), donde :

$$  $$ \phi_{B} (0,15 m) = (0,0269 rad) (0,075 m) $$

$$  $$ \phi_{B} = 0,0134 rad $$

Ahora se determinará el ángulo de giro en el extremo A con respecto al extremo B del eje AB causado por el par de torsión de 45 N * m, (segunda figura). Se tiene: 

$$ \phi_{A/B} = \frac{T_{AB} L_{AB} }{JG} = \frac{(45 N * m) (2 m)}{(\frac{\pi}{2})(0,01 m)^4[80(10^9) N/m^2]} = 0,0716 rad $$

Por lo tanto, la rotación del extremo A, se determina mediante la suma de $\phi_{B}$ y $\phi_{A/B}$ puesto que ambos ángulos tienen la misma dirección (figura 2). Resulta: 

$$   \phi_{A} = \phi_{B} + \phi_{A/B} = 0,0134 rad + 0,0716 rad = 0,085 rad $$


### Bibliografía 
Mecánica de Materiales (octava edición). R.C. Hibbeler

### Autor
Daniel Lyon
