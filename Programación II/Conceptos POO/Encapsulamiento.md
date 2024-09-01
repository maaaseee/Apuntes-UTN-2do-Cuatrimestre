###### En el paradigma estructurado, si quisiéramos trabajar con una persona, y almacenar datos, deberíamos hacerlo de maneral tal:

nombre_1 = "Pedro"
apellido_1 = "Sánchez"
peso_1 = 85
edad_1 = 28

###### Y así con cada una de las personas que quiera ingresar.

---------------------------------------------------------------------------

###### Otra manera de realizarlo (en un lenguaje como Python) es con un diccionario, lo mas parecido a un objeto.

{"nombre": "Pedro", "apellido": "Sánchez", "peso": 85, "edad": 28}

---------------------------------------------------------------------------

##### Para las clases, se guardan los datos/características en atributos, tal que así:

**Class Persona(nombre, apellido, peso, edad):**
	self.nombre = nombre
	self.apellido = apellido
	self.peso = peso
	self.edad = edad

**persona_1 = Persona("Pedro", "Sánchez", 85, 28)**

##### Además, podremos modificar los datos de esta personas, utilizando los llamados métodos:

**def subir_peso(self, peso):**
	self.peso += peso

**persona_1.subir_peso(10)**

