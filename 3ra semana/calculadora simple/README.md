Algoritmo calculadorasimple
	n1= 0;
	n2= 0;
	menu= 0;
	escribir "ingrese primer valor"
	leer n1
	escribir "ingrese segundo valor"
	leer n2
	escribir""
	escribir "¿operación a realizar?"
	escribir " 1 + "
	escribir " 2 - "
	escribir " 3 * "
	escribir " 4 / "
	Leer menu
	
	segun menu hacer
		1: escribir "procesando operacion suma"
			escribir " El Resultado es: ", n1+n2
		2: escribir "procesando operacion Resta"
			escribir " El Resultado es: ", n1-n2
		3: escribir "procesando operacion Multiplicacion"
			escribir " El Resultado es: ", n1*n2
		4: escribir " procesando operacion Division"
			escribir " El Resultado es: ", n1/n2
			escribir""
			
		De Otro Modo:
			Escribir " La Operacion No Es Valida"
	FinSegun
	FinAlgoritmo
