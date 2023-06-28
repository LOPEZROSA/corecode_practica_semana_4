```Algoritmo par_Impar
	repetir
		Escribir "Ingrese un numero del 1-50"
		Leer n
		si n < 1 | n > 50 Entonces
			Escribir "Numero Invalido"
			finsi
	mientras que n<1 | n>50 
    p <- n%2=0
	
			para i=1 hasta n con paso 1 Hacer
				si i%2=0 & p entonces
					escribir i
				Finsi
				si i%2=1 & ~(p) entonces
					escribir i
				FinSi
			Finpara
FinAlgoritmo```
