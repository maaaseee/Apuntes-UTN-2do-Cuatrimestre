> Se puede definir como los subconjuntos **NO** ordenados de ***n*** elementos que pueden seleccionarse de un conjunto de ***m*** elementos. En mucho casos, nos interesamos en el número de formas posibles de seleccionar ***n*** elementos de un total de ***m*** elementos sin importar el orden. Tales selecciones se llaman combinaciones y se denotan con la expresión ${C_(m,n)}$

### Fórmula:
# $C_{(m,n)} = {\frac{V_{(m,n)}}{P_m}} = {\frac{m!}{n!.(m-n)!}}$

	Permutaciones de m elementos tomados de a n elementos. (m>n)

### Ejemplos

### 1. Tenemos 5 puntos no alineados en un plano:

- Cuantas rectas determinan?
La recta la determinan dos puntos distintos, lo mismo que el segmento, sin importar el orden de consideración de esos puntos. Serán 
## $C_{(5,2)} = 10$

- Cuantos triángulos determinan?
El triangulo lo determinan tres puntos distintos, serán 
## $C_{(5,3)} = 10$

### 2. Un niño le pide a su madre que le lleve 5 cartuchos de Game-boy de su colección de 10 juegos de aventuras y 5 de deportes. 

¿De cuantas maneras podría su madre elegir 3 juegos de aventuras y 2 de deportes?. Podemos ver que no importará el orden en el que serán seleccionados siempre y cuando sean juegos de una clase o de la otra.

En primer lugar debemos tomar ***n*** = 3 elementos de ***m*** = 10 elementos de la clase A (juegos de aventuras). =>

# $C_{(10,3)} = {\frac{V_{(10,3)}}{P_{10}}} = {\frac{10!}{3!.(10-3)!}} = {\frac{3.628.800}{30.240}} = 120$

En segundo lugar debemos tomar ***n*** = 2 elementos de un total de ***m*** = 5 elementos de la clase B (juegos de deportes). =>
# $C_{(5,2)} = {\frac{V_{(5,2)}}{P_{(5}}} = {\frac{5!}{2!.(5-2)!}} = {\frac{120}{12}} = 10$

#### Finalmente, si utilizamos la regla de la multiplicación con $n_1$ = 120 y $n_2$ = 10, tendremos un total de $n_1 . n_2 = 120 . 10 = 1200$ formas distintas de elegir los 5 juegos donde 3 son de aventuras y 2 de deportes.