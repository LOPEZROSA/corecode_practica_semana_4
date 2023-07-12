```
funcion valor <- preciototal(precio,iva)
	definir valor como real
	si precio > 3000 Entonces
		valor = (precio+(precio/100*iva)) / 100*90
	SiNo
		valor = (precio+(precio/100*iva))
	FinSi
	
FinFuncion
Algoritmo precio_Total
	imprimir preciototal(3500,12)
	
FinAlgoritmo```
