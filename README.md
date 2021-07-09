# Semana-10
Proceso  Ejercicio_numero_positivo
	Definir numero_positivo,raiz_cuadrada, potencia Como Real
	Escribir "Ingresa un número positivo"
	Leer numero_positivo
	si (numero_positivo > 0) Entonces
		raiz_cuadrada=rc (numero_positivo)
		Escribir "La raiz cuadrada de un número positivo es:", raiz_cuadrada
	SiNo
		potencia=numero_positivo ^2;
		Escribir "El cuadrado de dicho número es negativo es:", potencia
	FinSi
FinProceso

Proceso Ejercicio_par_no_par
	Escribir "Indique un número"
	Leer numero	
	si numero MOD 2 = 0 Entonces
		Escribir numer,' es par'
	SiNo
		Escribir numero,' no es par'
	FinSi
FinProceso

Proceso Inicio_de_sesion
	Definir usuario,contraseña Como Caracter
	Escribir 'Ingrese su usuario'
	Leer usuario
	Escribir 'Ingresa tu contraseña'
	Leer contraseña
	Si usuario='Pier' Entonces
		Si contraseña="Pier123" Entonces
			Escribir 'DATOS CORRECTOS'
		SiNo
			Escribir 'Contraseña incorrecta'
		FinSi
	SiNo
		Escribir 'Usuario incorrecto'
	FinSi
FinProceso
