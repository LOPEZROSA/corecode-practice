```Escribir "=====Saludos====="
	definir n como entero
	definir continuar como cadena
	definir saludosrealizados como  entero
	continuar <-"si"
	saludosrealizados <- 0
	mientras continuar== "si" hacer
		escribir "Ingresa la Hora (1-24hrs)"
		leer n
		si n <= 12 Entonces
			escribir "¡¡Buenos Dias!!"
			sino
				si n <= 18 Entonces
					escribir "¡¡Buenas Tardes!!"
					sino
						escribir "¡¡Buenas Noches!!"
			FinSi
		FinSi
		saludosrealizados<-saludosrealizados+1
		Escribir "Desea Continuar si/no"
		leer continuar
	FinMientras
	escribir " Saludos Realizados: " + convertirATexto(saludosrealizados)
	FinAlgoritmo```
