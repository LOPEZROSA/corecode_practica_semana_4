```Algoritmo venta_comision
	Escribir Mayusculas("Ingrese cantidad de Venta: ")
	Leer cantidadDeventa
	totalvent=0
	comision=0
	para i=1 hasta cantidadDeventa con paso 1 Hacer
			escribir "Ingresa las Ventas ", i
			leer venta
			totalvent<-totalvent+venta
		fin para
		promedio<-totalvent/venta
		Escribir"El promedio de la venta es: ",promedio
		si cantidadDeventa <= 5 Entonces
			Escribir"La Comision Obtenida es: ", totalvent*0.10
		SiNo
			Escribir "La Comision Obtenida es: ", totalvent*0.15
		FinSi
    finalgoritmo```

