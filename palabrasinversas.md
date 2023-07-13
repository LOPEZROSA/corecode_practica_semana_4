```
funcion palabrafinal<-inversa(string)
	definir palabrafinal Como Caracter
	palabrafinal = "";
	Para i = Longitud(string) Hasta 0 Con Paso -1 Hacer
		letras = Subcadena(string,i,i);
		SI letras = Mayusculas(letras) Entonces
			letras = Minusculas(letras)
		SiNo
			letras = Mayusculas(letras)
		FinSi
		palabrafinal = concatenar(palabrafinal,letras)
		fin para
FinFuncion

Algoritmo Direccion_inversa
imprimir inversa("BUEN DIA")
	
FinAlgoritmo```
