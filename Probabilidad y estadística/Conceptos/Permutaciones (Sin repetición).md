> Una permutación puede definirse como los distintos ordenamientos que pueden realizarse en un conjunto de m elementos. Se denota mediante la expresión ${P_m}$ . Siendo un caso particular de las variaciones, donde solo podemos cambiar el orden de los elementos, ya que cada muestra contiene todos los elementos.

### Fórmula:
# $P_m = m!$

	Permutaciones de m elementos tomados de a n elementos. (m=n)

### Ejemplos

### 1. Consideramos 3 letras a, b y c. Las permutaciones posibles son: abc, acb, bac, bca, cab y cba.

Vemos que existen 6 ordenamientos o arreglos distintos. Podemos llegar a la misma respuesta sin listar los diferentes arreglos u ordenamientos.
Habrá entonces $n_1$ = 3 opciones para la primera posición, luego $n_2$ = 2 opciones para la segunda posición y finalmente $n_3$ = 1 opción para la última posición. (m=n)

- Usando la [[Regla de la multiplicación]] =>  
## $n_1 . n_2 . n_3 = 3.2.1 = 6$ 

- Usando permutaciones => 
## $P_m = 3! = 3.2.1 = 6$ 


### 2. Quiero ordenar 5 libros en un estante: 

1. Sin restricciones: son los distintos ordenamientos que pueden hacerse en un conjunto de 5 elementos es decir: 
## $P_5 = 5! = 120$

2. El libro A a la derecha: ahora solo debo ordenar 4 elementos, por lo cual tengo 
## $P_4 = 4! = 24$

3. El libro A y el B juntos: acá debo ordenar 4 elementos y considerar a A y B como un solo libro, pero a su vez ellos pueden ordenarse entre sí: 
## $P_4 . P_2 = 4! . 2! = 24 . 2 = 48$