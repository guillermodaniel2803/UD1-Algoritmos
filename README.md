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

Algoritmo Ej6
	Definir num1, num2, num3, media Como Real
    // Pedimos los tres números al usuario
    Escribir "Introduce el primer número:"
    Leer num1
    Escribir "Introduce el segundo número:"
    Leer num2
    Escribir "Introduce el tercer número:"
    Leer num3
    // Calculamos la media
    media <- (num1 + num2 + num3) / 3
    // Mostramos el resultado
    Escribir "La media de los tres números es: ", media	
FinAlgoritmo

Algoritmo Ej7
 	Definir minutos, horas, minutos_restantes Como Entero
   	 // Pedimos la cantidad de minutos al usuario
   	 Escribir "Introduce la cantidad de minutos:"
   	 Leer minutos
	    // Convertimos los minutos a horas y minutos restantes
    	horas <- minutos / 60  // División entera para obtener las horas
   	 minutos_restantes = minutos % 60  // El residuo son los minutos restantes
    	// Mostramos el resultado
    	Escribir minutos, " minutos son ", horas, " horas y ", minutos_restantes, " minutos."
FinAlgoritmo

Algoritmo Ej8
	Definir sueldo_base, venta1, venta2, venta3, comision, total_mensual Como Real
	    // Pedimos el sueldo base y las tres ventas realizadas
   	 Escribir "Introduce el sueldo base del vendedor:"
    	Leer sueldo_base
   	 Escribir "Introduce el valor de la primera venta:"
    	Leer venta1
    	Escribir "Introduce el valor de la segunda venta:"
   	 Leer venta2
    	Escribir "Introduce el valor de la tercera venta:"
    	Leer venta3
    	// Calculamos la comisión del 10% sobre el total de las ventas
    	comision = (venta1 + venta2 + venta3) * 0.10
    	// Calculamos el total mensual (sueldo base + comisiones)
    	total_mensual = sueldo_base + comision
    	// Mostramos las comisiones y el total mensual
    	Escribir "La comisión obtenida por las ventas es: $", comision
	    Escribir "El total que recibirá en el mes es: $", total_mensual
FinAlgoritmo

Algoritmo Ej9
	Definir total_compra, descuento, total_final Como Reales
   	 // Pedimos el total de la compra al cliente
   	 Escribir "Introduce el total de la compra:"
   	 Leer total_compra
    	// Calculamos el descuento del 15%
   	 descuento <- total_compra * 0.15
   	 // Calculamos el total final a pagar
   	 total_final <- total_compra - descuento
   	 // Mostramos el descuento y el total final
   	 Escribir "El descuento es: $", descuento
	    Escribir "El total a pagar después del descuento es: $", total_final	
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
	
Algoritmo Ej11
	Definir numero1, numero2, distancia Como Real
   	 // Pedimos los dos números al usuario
   	 Escribir "Introduce el primer número:"
    	Leer numero1
    	Escribir "Introduce el segundo número:"
    	Leer numero2
    	// Calculamos la distancia (valor absoluto de la diferencia)
   	 distancia <- Abs(numero1 - numero2)
    	// Mostramos el resultado
    	Escribir "La distancia entre los dos números es: ", distancia
FinAlgoritmo

Algoritmo Ej12
	Definir x1, y1, x2, y2, distancia Como Real
    	// Pedimos las coordenadas del primer punto
   	 Escribir "Introduce la coordenada x1 del primer punto:"
    	Leer x1
   	 Escribir "Introduce la coordenada y1 del primer punto:"
    	Leer y1
	    // Pedimos las coordenadas del segundo punto
   	 Escribir "Introduce la coordenada x2 del segundo punto:"
   	 Leer x2
   	 Escribir "Introduce la coordenada y2 del segundo punto:"
    	Leer y2
    	// Calculamos la distancia entre los dos puntos
   	 distancia <- Raiz((x2 - x1)^2 + (y2 - y1)^2)
    	// Mostramos el resultado
    	Escribir "La distancia entre los dos puntos es: ", distancia
FinAlgoritmo

Algoritmo Ej13
Definir numero, raiz_cuadrada, raiz_cubica Como Real
    // Pedimos el número al usuario
    Escribir "Introduce un número:"
    Leer numero
    // Calculamos la raíz cuadrada
    raiz_cuadrada <- Raiz(numero)
    // Calculamos la raíz cúbica usando potenciación
    raiz_cubica <- numero ^ (1/3)
    // Mostramos los resultados
    Escribir "La raíz cuadrada de ", numero, " es: ", raiz_cuadrada
    Escribir "La raíz cúbica de ", numero, " es: ", raiz_cubica
FinAlgoritmo

Algoritmo Ej14
Definir numero, decenas, unidades, numero_invertido Como Entero
    // Pedimos al usuario que introduzca un número de dos cifras
    Escribir "Introduce un número de dos cifras:"
    Leer numero
    // Obtenemos las decenas y unidades
    decenas <- numero / 10  // División entera para obtener las decenas
    unidades <- numero / 10  // Módulo para obtener las unidades
    // Invertimos el número
    numero_invertido <- (unidades * 10) + decenas
    // Mostramos el número invertido
    Escribir "El número invertido es: ",numero_invertido
FinAlgoritmo
