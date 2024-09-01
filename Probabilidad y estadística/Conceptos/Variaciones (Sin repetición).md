### Definición
Se puede definir como los subconjuntos ordenados de n elementos que pueden seleccionarse de un conjunto de ***m*** elementos. Se denota mediante $V_{m, n}$ . Aquí nos importa tanto el orden de los elementos como su clase o naturaleza. (¿Cuáles y en qué orden?)

### Fórmula:
# $V_{(m,n)} = {\frac{m!}{(m-n)!}}$

	Variaciónes de m elementos tomados de a n elementos. (m>n)

### Ejemplos

### 1. ¿De cuantas maneras distintas pueden sentarse 4 personas (Pablo, Adolfo, Esteban y Carlos) en 3 butacas contiguas numeradas?

- Usando la [[Regla de la multiplicación]] => 4.3.2.1 = 24 maneras distintas.
- Usando variaciones => ${V_{(4,3)} = {\frac{4!}{(4-3)!}}}$ = 24
### 2. Dispongo de tela de 7 colores distintos y quiero armar una bandera de 3 franjas horizontales. De cuantas maneras puedo hacerlo si: 

a) No tengo restricciones.
b) La de arriba debe ser blanca. 
c) La primera y la tercera son iguales.

a) Tengo que elegir ordenadamente 3 colores de los 7 que tengo =>
## ${V_{(7, 3)} = {\frac{7!}{(7-3)!}}} = 210$ 

b) Ahora solo selecciono 2 colores de los 6 que quedan => 
## ${V_{(6, 2)} = {\frac{6!}{(6-2)!}}} = 30$  

c) Ahora solo elijo dos colores es decir que el tercero quedo elegido al elegir el primero => 
## ${V_{(7, 2)} = {\frac{7!}{(7-2)!}}} = 42$ 