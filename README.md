# UD1-Algoritmos

Algoritmo Ej1
	Escribir "¿Cual es tu nombre?"
	Leer nombre
	Escribir "Saludos " nombre 
FinAlgoritmo

Algoritmo Ej2
	Leer base 
	Leer altura
	area <- base*altura 
	Mostrar area
	perimetro <- 2*area + 2*base
	Mostrar perimetro
FinAlgoritmo

Algoritmo Ej3
	Definir cateto1, cateto2, hipotenusa Como Real
	// Pedimos los valores de los catetos
	Escribir "Introduce el valor del primer cateto:"
	Leer cateto1
	Escribir "Introduce el valor del segundo cateto:"
	Leer cateto2
	// Calculamos la hipotenusa usando el teorema de Pitágoras
	hipotenusa = Raiz(cateto1^2 + cateto2^2)
	// Mostramos el resultado
	Escribir "La hipotenusa del triángulo es: ", hipotenusa
FinAlgoritmo

Algoritmo Ej4
	Leer n1
	Leer n2
	suma<- n1+n2
	resta<- n1-n2
	multiplicar<- n1*n2
	dividir<- n1/n2
	Mostrar suma
	Mostrar resta
	Mostrar multiplicar
	Mostrar dividir
FinAlgoritmo

Algoritmo Ej5
	Escribir "introduce los grados farenheit: "
	leer gradosF
	gradosC <- (gradosF-32) * 5/9
	Escribir gradosC
FinAlgoritmo

