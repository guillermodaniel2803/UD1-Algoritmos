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


Algoritmo Ej10
	Definir calificacion1, calificacion2, calificacion3, promedio_parciales, examen_final, trabajo_final, calificacion_final Como Real
    // Pedimos las tres calificaciones parciales
    Escribir "Introduce la primera calificación parcial:"
    Leer calificacion1
    Escribir "Introduce la segunda calificación parcial:"
    Leer calificacion2
    Escribir "Introduce la tercera calificación parcial:"
    Leer calificacion3
    // Calculamos el promedio de las calificaciones parciales
    promedio_parciales <- (calificacion1 + calificacion2 + calificacion3) / 3
    // Pedimos la calificación del examen final y el trabajo final
    Escribir "Introduce la calificación del examen final:"
    Leer examen_final
    Escribir "Introduce la calificación del trabajo final:"
    Leer trabajo_final
    // Calculamos la calificación final
    calificacion_final <- (promedio_parciales * 0.55) + (examen_final * 0.30) + (trabajo_final * 0.15)
    // Mostramos el resultado
    Escribir "La calificación final en Algoritmos es: ", calificacion_final
FinAlgoritmo
