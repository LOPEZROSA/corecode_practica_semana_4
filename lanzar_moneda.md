```Algoritmo lanzar_la_moneda
	definir moneda como entero
	Escribir "Ingresa tu nombre primer Jugador"
	leer nombre
	Escribir"Ingresa un valor"
	leer valor
	Escribir"Ingresa tu nombre segundo Jugador"
	leer nombre2
	escribir"Ingresa un valor"
	leer valor2
	
	si aleatorio(1,2) = 1 entonces 
		escribir mayusculas(nombre)," ","valor determinado: ", valor
	SiNo
		escribir mayusculas(nombre2)," ","valor determinado: ", valor2
	FinSi
	SI valor <= 0 | valor2 <= 0 Entonces
		SI valor <= 0 & valor2 <= 0 Entonces
			Imprimir "Juego Cancelado"
		SiNo
			SI valor <= 0 Entonces
				Imprimir "Jugador que gana: ", Mayusculas(nombre), " cantidad ganada: 0"
			SiNo
				Imprimir "Jugador que gana: ", Mayusculas(nombre2), " cantidad ganada: 0"
			FinSi
			finsi
		FinSi
	FinAlgoritmo```
