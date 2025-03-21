  Algoritmo NumerosPrimo
    Definir n, contador, i Como Entero
    Escribir "Ingrese un digito:"
    Leer n
    Si n < 2 Entonces
        Escribir n, " no es un número primo."
    Sino
        contador <- 0
        Para i <- 2 Hasta n - 1 Con Paso 1
            Si (n mod i) = 0 Entonces
                contador <- contador + 1
            FinSi
        FinPara
        Si contador = 0 Entonces
            Escribir n, " es un número primo."
        Sino
            Escribir n, " no es un número primo."
        FinSi
    FinSi
FinAlgoritmo

